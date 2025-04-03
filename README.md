# Querying Files Using a Serverless SQL Pool 

## About the studying

This studying demonstrates how to query data files using **serverless SQL pools** in **Azure Synapse Analytics**. Serverless SQL pools allow you to query data files directly, eliminating the need for infrastructure management while enabling fast data queries. In this project, I performed queries on files in different formats (CSV, Parquet, JSON) and visualized the results using Power BI.

## Technologies Used

- **Azure Synapse Analytics**
- **Serverless SQL Pools**
- **Azure Data Lake Storage**
- **T-SQL (Transact-SQL)**
- **Azure Blob Storage**
- **Power BI (Data Visualization)**

## Studying Steps

### 1. **Provisioning an Azure Synapse Analytics Workspace**
   - The first step was to create an **Azure Synapse Analytics workspace**, which serves as the central platform for managing data integration and analysis.

### 2. **Connecting to Data Sources**
   - Data files stored in **Azure Data Lake Storage** and **Azure Blob Storage** were connected for querying via serverless SQL pools.

### 3. **Using Serverless SQL Pools**
   - **Serverless SQL pools** were used to query the data directly, without the need to manage any infrastructure. This made it possible to quickly access data and perform queries.

### 4. **Querying Data Files**
   - **Querying CSV Files Using SQL**: Data stored in CSV files was accessed, and SQL queries were executed for analysis.
   - **Querying Parquet Files Using SQL**: Parquet files were queried efficiently using serverless SQL pools.
   - **Querying JSON Files Using SQL**: SQL queries were executed on JSON formatted data.

### 5. **Accessing External Data and Querying**
   - **Creating an External Data Source**: External data sources were created within Azure Synapse Analytics to query data from external systems or databases.
   - **Creating an External Table**: External tables were created from the external data sources, making it possible to query them via serverless SQL pools.

### 6. **Data Visualization**
   - Data query results were visualized using Power BI. This step transformed the data into meaningful visual insights, supporting decision-making processes.

### 7. **Deleting Azure Resources**
   - After the project was completed, all Azure resources used during the project were cleaned up to avoid unnecessary costs.

## Studying Outcomes

This studying demonstrates how **serverless SQL pools** in Azure Synapse Analytics can be used to query large data files in a cost-effective and efficient way. Queries were performed on files in various formats (CSV, Parquet, JSON), and data analytics and visualizations were completed. Integration with external data sources allowed for more comprehensive data analysis.

## Requirements

- An **Azure Synapse Analytics** account
- Data files in **Azure Data Lake Storage** or **Azure Blob Storage**
- Power BI (for data visualization)

## Usage

To run this studying on Azure Synapse, follow these steps:

1. **Create an Azure Synapse Analytics workspace.**
2. Upload your data files to **Azure Data Lake Storage** or **Azure Blob Storage**.
3. Create a **serverless SQL pool** and connect it to your data.
4. Query your data files using SQL queries for analysis.
5. Use **Power BI** to visualize the query results.



