# Olympics
This is End-to-end Data Engineering project from data Ingestion, Data orchestration and Data dumping
Phase 1: Completed
1. GitHub Repository
•	Create a new public GitHub repository for this project.
•	Upload the four provided datasets (teams.csv, medals.csv, coaches.csv, and athletes.csv) to this repository.
•	Commit your changes and include a clear README.md file that briefly describes the project.
2. Azure Storage
•	Create an Azure Storage Account with a Data Lake Storage Gen2 enabled.
•	Inside the storage account, create a file system (e.g., olympic-data).
•	Within this file system, create the following folder structure to represent your data layers:
o	bronze/ (for raw, untransformed data)
o	silver/ (for cleaned and standardized data)
o	gold/ (for aggregated and ready-to-report data)
3. Data Ingestion Pipeline (Azure Data Factory)
•	Create an Azure Data Factory (ADF) instance.
•	Build a data pipeline in ADF that ingests the four CSV files directly from your GitHub repository and copies them into the bronze folder of your Azure Data Lake.
•	Make sure to configure the pipeline to handle the CSV format correctly.
