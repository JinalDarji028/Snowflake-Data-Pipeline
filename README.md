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
```bash
conda env create -f environment.yml
conda activate snowflake_demo
```bash

**Option 2: **
```bash
pip install -r requirements.txt




