# data_engineering_pipeline_project
I have created a simple data engineering pipeline using Azure and used Spark ML to build a data science model for fraud detection using machine learning.
![1](https://github.com/hiteshg1318/data_engineering_pipeline_project/assets/68686869/a3c2d547-d232-43a0-bd26-d90e1770b645)



Step 1. Create Data pipe line in azure data factory with the CSV files that I have provided in this project. Pull the data into azure storage account (data lake gen 2) to raw container. See the image below for reference
<img width="1280" alt="2" src="https://github.com/hiteshg1318/data_engineering_pipeline_project/assets/68686869/4cac41a4-2f40-4127-9967-6b2bf2c9c439">

Step 2: Create pipeline from raw container in azure data lake to azure data bricks. Use the before transformation code. In the end the cleaned data is sent to transformed container in azure data lake

Step 3. Create pipeline to pull cleaned data in another workspace in azure data bricks from transformed container. Build machine learning models.
![4](https://github.com/hiteshg1318/data_engineering_pipeline_project/assets/68686869/7c590c63-2f7e-4ab5-af41-8263264b3d6f)
![5](https://github.com/hiteshg1318/data_engineering_pipeline_project/assets/68686869/c7782eb4-1daf-43fe-897e-c14ca600804d)
![6](https://github.com/hiteshg1318/data_engineering_pipeline_project/assets/68686869/cf9a968d-639d-4e14-ab2b-8bc3cde61a25)


Step 4. Build dashboard for analytics by connecting Power BI desktop to azure data lake.
<img width="956" alt="8" src="https://github.com/hiteshg1318/data_engineering_pipeline_project/assets/68686869/9a8c4de3-092c-4ae1-84bd-70d42eca8edc">

