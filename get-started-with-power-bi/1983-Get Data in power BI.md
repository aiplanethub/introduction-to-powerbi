Before you can create reports, you must first extract data from the various data sources.

**A data source is where the data in a dataset comes from**. For example, the data could come from:

* An online service like Google Analytics or QuickBooks
* A database in the cloud like Azure SQL Database
* A database or file on a local computer or server in your own organization.
---


**1. Get data from files**

A flat file is a type of file that has only one data table and every row of data is in the same structure. The file does not contain hierarchies. You may be familiar with the most common types of flat files:

- Comma-separated values (.csv) files
- Delimited text (.txt) files
- Fixed-width files
- Microsoft Excel workbooks (.xlsx)


In Power BI, on the Home tab, select **Get data**. In the list that displays, select the option that you require, such as **Text/CSV** or **XML**. For this example, you will select **Excel**.

**NOTE:** The Home tab contains quick access data source options, such as Excel, next to the Get data button. 
![2-get-data-excel-ssm.png](https://dphi-live.s3.amazonaws.com/media_uploads/2-get-data-excel-ssm_de4cbf76d62446ffa1e04e8211f09d6b.png)


**2. Get data from databases**

Databases in the Cloud - From the Power BI service, you can connect live to:

* Azure SQL Database
* Azure Synapse Analytics (formerly SQL Data Warehouse)
* Spark on Azure HDInsight

Connections from Power BI to these databases are live. Let's say you connect to an Azure SQL Database. You then begin exploring its data by creating reports in Power BI. Whenever you slice your data or add another field to a visualization, Power BI makes a query right to the database.