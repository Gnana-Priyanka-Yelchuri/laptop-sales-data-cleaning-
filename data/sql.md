## Data Import into SQL Server

To perform data analysis using SQL, the laptop sales dataset was imported into Microsoft SQL Server Management Studio (SSMS).

The dataset was loaded using the **Flat File Import Wizard**, which provides a simple method for importing CSV files into SQL Server tables. During the import process, SQL Server automatically detected column names and inferred appropriate data types based on the source data.

After the import was completed, the data was validated to ensure that all records were successfully loaded into the database table. Initial SQL queries were executed to verify row counts, inspect sample records, and confirm that the imported data matched the original dataset used in Python.

Using SQL Server allowed the dataset to be explored and analyzed through SQL queries, providing an additional perspective alongside Python-based analysis.

## Data Profiling Using SQL Server

Before performing any cleaning operations, the dataset was profiled using SQL queries to understand its structure and quality.

The profiling process focused on:

* Verifying the total number of records.
* Inspecting sample data.
* Investigating potential duplicate records.
* Understanding the distribution of key attributes.

The objective of this stage was to understand the dataset before making any cleaning decisions. This approach helps prevent unnecessary data loss and ensures that cleaning actions are supported by evidence rather than assumptions.
