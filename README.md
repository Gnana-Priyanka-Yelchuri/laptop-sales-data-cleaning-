# Data Cleaning Challenges:
The dataset contains information about laptop sales and specifications from multiple brands.
## Dataset Size
1.Total Rows: 1,020
2.Total Columns: 29

## Key Attributes:
1. Laptop Name
2. Brand
3. Price
4. Rating
5. Processor Details
6. RAM Capacity and Type
7. Storage Capacity and Type
8. Graphics Specifications
9. Display Information
10. Touch Screen Availability
11. Operating System

## Why Data Cleaning Is Important:
Data cleaning is often associated with removing null values or replacing them with mean, median, or mode values. However, applying these techniques without understanding the dataset can lead to loss of information and inaccurate analysis.
### For example:
1) Dropping all rows containing null values may significantly reduce the dataset size.
2) Replacing missing values using mean or median may not be appropriate for hardware specification columns.
3) Some columns may have missing values because the information is not applicable rather than missing.
4) Certain attributes require business understanding before deciding how they should be handled.
#### Therefore, before performing any cleaning operation, the dataset will be profiled to understand:
1) Number of rows and columns.
2) Data types.
3) Missing value distribution
4) Duplicate records
5) Unique value counts
6) Column relevance
7) Potential data quality issues
   
### Cleaning Strategy:
The objective of this project is not to immediately remove records or replace values using common cleaning techniques. Before applying any transformation, the dataset will be investigated to understand its structure and quality.

#### Questions that will be explored include:
- How many rows and columns are present in the dataset?
- What are the data types of each column?
- Which columns contain missing values?
- How many duplicate records exist?
- Are all columns useful for analysis?
- What would happen if rows containing missing values were removed?
- Would replacing values using mean, median, or mode be appropriate for every column?
- How would different cleaning decisions affect the final dataset?

The cleaning process will be performed using both SQL Server (SSMS) and Python. The objective is to compare how different tools can be used to profile, investigate, and improve data quality within the same dataset.

#### The goal is to make informed cleaning decisions rather than applying standard cleaning techniques without understanding their impact on the dataset.

#### Dataset Source: Laptop Sales Dataset from Kaggle

