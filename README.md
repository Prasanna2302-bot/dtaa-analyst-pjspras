# dtaa-analyst-pjspras
Descriptive Analysis of Bikeway Speed Limits in Vancouver
Project Title
Analyzing Bikeway Speed Limits and Snow Removal Patterns in Vancouver

Objective
The primary objective of this project is to perform a descriptive analysis of bikeways in Vancouver to:

Determine the average speed limits for different types of bikeways.
Explore how speed limits affect the frequency of snow removal.
Dataset
The analysis utilizes the bikeways2.csv dataset, which includes:

Bikeway types and their attributes.
Speed limit data for each bikeway.
Snow removal records for different streets.
Methodology
Part 1: Descriptive Analysis

Descriptive Question: "What is the average speed limit of bikeways in Vancouver by type of bikeway?"
Data Ingestion:
Upload the bikeways2.csv dataset to an AWS S3 bucket.
Organize the data into Raw folders for unprocessed storage.
Data Profiling:
Use AWS Glue DataBrew to identify missing values and assess data quality.
Data Cleaning:
Fill missing speed limits and remove irrelevant columns.
Store the cleaned data in the S3 bucket under System and User folders.
Data Pipeline Design:
Use AWS Glue to create an ETL pipeline.
Calculate the average speed limit for each bikeway type and save results in System and User folders.
Part 2: Exploratory Analysis

Exploratory Question: "How do speed limits impact the frequency of snow removal on different types of bikeways?"
Data Ingestion:
Load the cleaned dataset from S3 for further analysis.
Data Profiling:
Assess data quality and identify gaps affecting snow removal.
Data Cleaning:
Address data inconsistencies and prepare for advanced queries.
Data Pipeline Design:
Use AWS Glue to filter and aggregate data by bikeway type.
Analyze snow removal frequency and its relationship with speed limits.
Data Visualization
Visual representations include:
Bar Charts: Comparing speed limits across bikeway types.
Heatmaps: Frequency of snow removal by geographic location and bikeway type.
Tools and Technologies
AWS S3: Storage for raw and processed datasets.
AWS Glue: ETL pipelines for data transformation.
AWS Glue DataBrew: Data profiling and cleaning.
Visualization Tools: Charts comparing bikeway speed limits and snow removal.
Deliverables
Descriptive and Exploratory Analysis Reports:
Detailed findings on bikeway speed limits and snow removal patterns.
ETL Workflow Designs:
Automated pipelines for data processing.
Data Visualizations:
Insights presented through bar charts and heatmaps.
Impact
This project enables the City of Vancouver to:

Optimize bikeway management by understanding speed limit trends.
Improve operational efficiency for snow removal services.
Enhance urban infrastructure planning with actionable insights.
