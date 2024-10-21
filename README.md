# Vehicle-Insurance-Data-Analytics-Project
This repository contains the source code and resources for a comprehensive data analytics project related to the vehicle insurance domain. The project focuses on analyzing customer data, claims, risk factors, and fraud detection using a combination of modern data processing, visualization, and cloud technologies.


Table of Contents
1.Technologies Used
2.Project Structure
3.Data Sources
4.ETL Process
5.Data Storage
6.Data Analysis
7.Visualizations
8.How to Run
9.Future Enhancements
---------------------------------------------------------------------------------------------------------------------
Technologies Used
Languages: Python, SQL
Data Processing: Apache Hadoop, Apache Spark, Hive
Database Management: SQL (PostgreSQL, MySQL), MongoDB
Streaming: Apache Kafka
Visualization: Power BI, Tableau
Cloud Platform: Google Cloud Platform (GCP)
APIs/Webservices: RESTful APIs for data collection
Big Data Tools: HDFS for distributed storage, Spark for distributed data processing
--------------------------------------------------------------------------------------------------------------------
Project Structure
bash
Copied!
📂 vehicle-insurance-data-analytics
├── 📂 data                # Raw data and processed data files
├── 📂 scripts             # Python scripts for data processing
├── 📂 notebooks           # Jupyter notebooks for exploratory analysis
├── 📂 visualizations      # Power BI and Tableau dashboards
├── 📂 config              # Configuration files for APIs, Kafka, etc.
└── README.md
-------------------------------------------------------------------------------------------------------------------
Data Sources
Customer Data: Demographic information of policyholders, vehicle details, and insurance policy records from relational databases (SQL).
Claim Data: Collected via RESTful APIs from third-party services providing claim history and statuses.
Sensor Data: Real-time vehicle sensor data ingested using Kafka for analysis of driving behavior and risk profiling.
Fraudulent Claims: Flagged by machine learning models and stored in MongoDB.
-------------------------------------------------------------------------------------------------------------------
ETL Process
Extract: Data is extracted from multiple sources, including APIs, SQL databases, and real-time Kafka streams.
Transform: Python and Spark scripts perform data cleaning, aggregation, and transformation for meaningful analysis.
Load: Data is stored in PostgreSQL, MySQL, Hive, and MongoDB for structured and unstructured data storage.
-------------------------------------------------------------------------------------------------------------------
Data Storage
SQL: Structured data such as customer information and policy details are stored in PostgreSQL and MySQL databases.
Hive: Used for large-scale query and analysis of data stored on HDFS.
MongoDB: NoSQL database for storing unstructured data like sensor logs and API call logs.
HDFS: For distributed storage of large datasets.
-------------------------------------------------------------------------------------------------------------------
Data Analysis
Customer Segmentation: Identifying high-risk customers and providing personalized policy suggestions.
Claims Analysis: Understanding claim patterns and fraud detection using predictive models.
Risk Profiling: Using real-time sensor data and driving history to calculate risk scores.
-------------------------------------------------------------------------------------------------------------------
Visualizations

1.Power BI Dashboard:
	-Claims history
	-Risk score analysis
	-Fraud detection
	-Premium trends
2.Tableau Dashboard:
	-Customer demographics
	-Vehicle details
	-Real-time sensor data visualizations
	-Policy renewal trends
-------------------------------------------------------------------------------------------------------------------

How to Run

1.Clone the repository:

bash
git clone https://github.com/yourusername/vehicle-insurance-data-analytics.git
cd vehicle-insurance-data-analytics
-------------------------------------------------------------------------------------------------------------------
2.Install required packages:

bash
pip install -r requirements.txt
-------------------------------------------------------------------------------------------------------------------
3.Run ETL pipeline:

bash
python scripts/etl_pipeline.py
-------------------------------------------------------------------------------------------------------------------
4.Run Jupyter Notebooks for exploratory analysis:

bash
jupyter notebook notebooks/exploratory_analysis.ipynb
-------------------------------------------------------------------------------------------------------------------
5.View Power BI and Tableau Dashboards:

Open the files located in the visualizations folder using respective software.
-------------------------------------------------------------------------------------------------------------------










