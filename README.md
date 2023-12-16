# data_engineering_pipeline_project
I have created a simple data engineering pipeline using Azure and used Spark ML to build a data science model for fraud detection using machine learning.


Step 1. Create Data pipe line in azure data factory with the CSV files that I have provided in this project. Pull the data into azure storage account (data lake gen 2) to raw container. See the image below for reference
<img width="1280" alt="2" src="https://github.com/hiteshg1318/data_engineering_pipeline_project/assets/68686869/4cac41a4-2f40-4127-9967-6b2bf2c9c439">

Step 2: Create pipeline from raw container in azure data lake to azure data bricks. Use the before transformation code. In the end the cleaned data is sent to transformed container in azure data lake

Step 3. Create pipeline to pull cleaned data in another workspace in azure data bricks from transformed container. Build machine learning models.

Step 4. Build dashboard for analytics by connecting Power BI desktop to azure data lake.
