# Mallinath  Patil – Data Engineering Portfolio

Welcome to my **Data Engineering Portfolio** – a curated collection of real-world data projects and case studies showcasing my expertise in building scalable, efficient, and reliable data pipelines using Python, PySpark, AWS, Databricks, and more.

> 🚀 **Transforming complex data into business value — one pipeline at a time.**

## 👨‍💻 About Me

I’m a **Results-driven Data Engineer** with over **5 years** of experience designing and optimizing ETL/ELT pipelines, handling large-scale structured and semi-structured data, and implementing cloud-native solutions. I specialize in:

- Building robust data pipelines using **Python, PySpark, SQL**
- Working across modern cloud stacks: **AWS Glue, Lambda, S3, EC2**
- Developing scalable solutions on **Databricks and Snowflake**
- Orchestrating workflows with **Apache Airflow**
- Driving **data quality**, performance tuning, and cost-optimized design

I bring a proven track record of enhancing data pipeline performance (up to 30% reduction in runtime) and delivering highly reliable (99.9% uptime) solutions that impact business decisions.

## Education	 			        		
- B.E. | BMS College of Engineering (2014-2018)

### Work Experience
**Publicis Sapient, Hyderabad, India**
**Sr. Data Engineer(2024-Present)**
### 🎧 Podcast Listener Analytics – Audience platform data lake implementation 
**Tech Stack**: PySpark, Databricks, AWS S3, AWS Lambda  
###The Audience platform was built as a single source of truth data lake serving all business units. It centralizes audience and podcast listener data and enables enterprise-wide reporting, advanced analytics, and data science model training.
- Built scalable ingestion and transformation pipelines for podcast listener data.
- Designed multi-layer architecture: **Landing → Silver → Analytical**
- Implemented listener mapping algorithms across multiple data sources.
- Orchestrated ETL workflows using **Databricks Workflows** with minimal manual intervention.
- Improved query performance through **tuning of PySpark jobs and SQL transformations**.
---
### 🔄 Redshift to Salesforce Migration  
**Tech Stack**: AWS Glue, AWS S3, Python Bulk API v2, PySpark  

- Delivered **end-to-end data migration** for 17M+ member records across key Salesforce objects.
- Used **AWS Glue workflows** and config-based design for flexibility and scalability.
- Implemented **bulk insert and upsert** logic with Python Bulk API v2.
- Achieved <1% error rate in production and received a **Certificate of Excellence** from the client.

  ---
**Ernst & young – Bangalore, India**
**Data Engineer (2022-2024)**
### 🧮 IFRS17 Compliance Platform – Financial Services  
**Tech Stack**: AWS Glue, PySpark, Athena, RDS, Airflow  

- Built and deployed pipelines to support IFRS17 regulatory requirements.
- Used **Athena + RDS** for efficient data querying and storage.
- Automated workflows with **Apache Airflow**, reducing manual effort.
- Established **robust data validation frameworks** and collaborated with QA/UAT teams for successful rollout.

---

# Customer & Order Analytics Platform on GCP

**Tech Stack:** Google Cloud Platform (GCP), Cloud Composer (Apache Airflow), Python, Google Cloud Storage (GCS), BigQuery, SQL, Looker Studio

---
## Project Description
Built a cloud-native analytics platform on Google Cloud to serve as a **centralized source of truth** for customer and order data. The platform automates daily ingestion, transformation, and loading of raw data into BigQuery, enabling reliable business reporting and analytics. The solution emphasizes **scalability, data quality, and minimal manual intervention** through workflow orchestration with Apache Airflow.

---

## Key Responsibilities & Achievements
- Designed and implemented an **end-to-end ETL pipeline** on Google Cloud to process daily customer and order datasets.
- Orchestrated workflows using **Apache Airflow (Cloud Composer)** for automated ingestion, transformation, and loading.
- Ingested raw files from **Google Cloud Storage (GCS)** with automated file detection and validation.
- Developed **Python-based data cleaning and transformation logic**, including column standardization, missing value handling, and schema consistency.
- Loaded curated datasets into **BigQuery** using optimized load jobs with schema autodetection and configurable write modes.
- Created **analytical SQL transformations** in BigQuery to join customer and order data for reporting use cases.
- Implemented **error handling, retries, and task dependencies** to ensure reliable and fault-tolerant pipeline execution.
- Enabled **business intelligence and reporting** by exposing analytics-ready datasets to **Looker Studio**.
- Monitored and scheduled pipelines via **Cloud Composer**, reducing operational overhead.

---

## Architecture Overview
![Architecture Diagram](assets/architecture.png)

*Centralized flow from data ingestion in GCS → Airflow ETL → BigQuery → Looker Studio dashboards.*

## Architecture Overview
```mermaid
flowchart LR
    A[Customer & Order Data] --> B[GCS - Raw Zone]
    B --> C[Cloud Composer<br>Apache Airflow]
    C --> D[Data Transformation<br>Python / PySpark]
    D --> E[BigQuery<br>Analytics Tables]
    E --> F[Looker Studio<br>Dashboards & Reports] ```

---

## Data Flow
![Data Flow Diagram](assets/data_flow.png)
*Daily customer and order files are detected, validated, transformed, and loaded into BigQuery.*

---

## Pipeline Workflow
![Pipeline Workflow](assets/pipeline_workflow.png)
*High-level overview of ETL steps, including ingestion, cleaning, transformation, and loading.*

---

## DAG Execution Flow
![DAG Flow](assets/dag_execution.png)
*Task orchestration flow handled by Cloud Composer (Airflow), including error handling and retries.*

---

## Future Enhancements
- Add **streaming ingestion** for near real-time updates.  
- Introduce **dbt transformations** for modular and testable analytics pipelines.  
- Implement **data lineage & observability** dashboards.  
- Integrate **machine learning pipelines** for predictive analytics.




### 📊 Metadata Dashboard Automation – BI4BI  
**Tech Stack**: Power BI, SQL Server, Python, REST APIs  

- Automated metadata ingestion using Python + REST APIs.
- Delivered **Power BI dashboards** to visualize key data trends and business KPIs.
- Enabled actionable insights through data modeling and transformation using **Pandas and SQL**.

---
**Subtle Solutions Pune, India**
**Data Engineer (2019-2022)**
###E-Commerce Analytics & Data Platform on AWS
**Tech Stack**: AWS Glue, PySpark, Python, AWS S3, Amazon RDS, AWS Lambda, Amazon Athena, EC2, SQL
**Project Description**
Developed a scalable data platform on AWS to support analytics, reporting, and operational insights for a growing e-commerce business. The platform ingests and transforms large volumes of transactional and customer data using distributed processing, enforces data quality standards, and delivers analytics-ready datasets to downstream systems. The solution focuses on performance optimization, reliability, and seamless integration across AWS services.

Key Responsibilities & Achievements
--Designed and implemented scalable ETL pipelines using AWS Glue, PySpark, and Python to process high-volume e-commerce data.
--Ingested and transformed data from multiple commerce source systems and loaded curated datasets into Amazon RDS and analytics stores.
--Implemented data quality checks and validation rules to ensure data completeness, accuracy, and consistency across the pipeline.
--Optimized PySpark jobs and SQL queries using partitioning, efficient joins, and caching to reduce processing time and resource usage.
--Managed complex data mapping and schema alignment to standardize data from disparate source systems.
--Utilized AWS Lambda for automation tasks and Amazon Athena for ad-hoc analysis and data validation.
--Monitored production pipelines, analyzed PROD issues, identified root causes, and deployed fixes with minimal downtime.
--Collaborated in Agile/Scrum ceremonies, including daily stand-ups and sprint planning, and participated in weekly client meetings for requirement gathering and delivery updates.
--Supported downstream reporting and analytics use cases by delivering reliable, analytics-ready datasets.
