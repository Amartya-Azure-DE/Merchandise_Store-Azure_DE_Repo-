# End-to-End Azure_DE_Project
Jujutsu is a merchandise store and planning to migrate it's on-prem SQL server data to Azure. Designing a pipeline which will migrate the data from On Prem Server to Azure SQL server. 
There are 8 tables for which we need to migrate the data.

Agenda or Purpose of this project-
♣ Data Pipeline should incrementally load the data from on prem to azure.
♣ Design the pipeline in such a way that if we want to add or remove any table from the list of tables, no changes to the pipeline are required.
♣ Optimize the performance of the Pipeline.
♣ Use Azure DevOps to deploy the pipeline to Test and Prod.
♣ Make sure that data is consistent in on prem and azure

Take Aways:-
♦ Troubleshooting Performance Issues and tips to resolve.
♦ Design and develop an end-to-end Meta Data Driven Pipeline using the Data Factory.
♦ Design and develop data factory CI/CD Pipeline.

Tech Stack used - 
•Azure Data Factory for
  - Integration Runtime(Azure & Self Hosted)
  - Linked Service
    - On-Prem to ADF(via SHIR)
    - Azure SQL Server/Database to SSMS(Azure-IR)
•Databricks for-
  - Cluster Making
  - Spark Session
•SSMS(SQL Server Management Studio) for-
  - Managing On-Prem and Azure SQL server
  - Querying Data using SQL


 Methods Used for
 Building a pipeline which will ingest csv files into Silver/CSV and JSON to Silver/Json
 ○ Get Metadata
 ○ Exception Handling in ADF
 ○ Logic App 
 ○ Azure Functions 
