# Snowflake-Data-Pipeline

## 🔑 Key Insights

**Purpose of the Project**  
Demonstrate how Snowflake can be leveraged as a unified platform for **data engineering and analytics**, with seamless integration to GitHub for version control and CI/CD. The aim was to show how organizations can automate data pipelines, incorporate external datasets, and streamline workflows for faster, more reliable insights.

**Strategic Value**  
- **Operational Efficiency**: Automated deployment of notebooks and pipelines reduced manual effort and improved reproducibility across DEV and PROD environments.  
- **Data Freshness**: Integration with Snowflake Marketplace (Weather Source data) ensured continuously updated datasets without maintenance overhead.  
- **Scalability**: Orchestrated task DAGs using Snowpark Python API provided a foundation for scalable, dependency-driven workflows.  
- **Governance & Reproducibility**: Version control via GitHub and environment standardization through `requirements.txt` and `environment.yml` supported transparent, auditable, and collaborative workflows.  

**Technologies Applied**  
- **Snowflake**: Role-based access, warehouses, schemas, event tables, pipelines  
- **GitHub**: Repository integration and CI/CD branching (dev → main)  
- **Snowpark Python API**: Task DAG orchestration for workflow automation  
- **Snowflake Marketplace**: External weather data integration for live insights  
- **Excel Ingestion**: Loading structured datasets into Snowflake tables  

**Key Outcomes**  
- Streamlined end-to-end data engineering workflows from ingestion to orchestration  
- Enabled continuous data integration (weather + Excel metrics)  
- Established CI/CD deployment practices aligned with enterprise governance  
- Showcased how Snowflake can serve as a single hub for **data-driven decision-making**  

---

## ⚙️ Environment Setup

You can set up the Python environment in two ways:

**Option 1: Conda**
conda env create -f environment.yml  
conda activate snowflake_demo  

**Option 2: pip**
pip install -r requirements.txt  

---

## 📂 Repository Contents
- **00_start_here.ipynb** → Main notebook 
- **requirements.txt** → Python dependencies (pip)  
- **environment.yml** → Conda environment file  

---

## 🔄 Project Flow

flowchart LR  
    A [GitHub Repo<br/>Version Control + CI/CD] --> B[Snowflake Setup<br/>Roles, Warehouses, Schemas]  
    B --> C[Pipeline Deployment<br/>Excel + City Metrics]  
    C --> D[External Data<br/>Weather Marketplace Integration]  
    D --> E[Task DAG Orchestration<br/>Snowpark Python API]  
    E --> F[Business Outcomes<br/>Reliable, Scalable, Fresh Data]  

---

## 📖 References
- [Snowflake Quickstart: Data Engineering with Notebooks](https://quickstarts.snowflake.com/guide/data_engineering_with_notebooks/index.html)  
- [Snowflake Docs – Execute Immediate From](https://docs.snowflake.com/en/sql-reference/sql/execute-immediate-from)  
- [Snowflake Python Management API](https://docs.snowflake.com/en/developer-guide/snowflake-python-api/snowflake-python-overview)  


