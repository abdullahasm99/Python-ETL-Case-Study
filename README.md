# Bicycle Store ETL Pipeline

This project aims to develop an Extract, Transform, Load (ETL) pipeline for a bicycle store using Python. 
The pipeline will facilitate the integration of data from diverse sources including databases, data lakes, and APIs, enabling seamless data processing and analysis.

## Objective

The primary objective of this project is to design and implement an end-to-end ETL process tailored specifically for a bicycle store. 
By leveraging Python programming, the pipeline will efficiently handle data extraction, transformation, and loading tasks, ensuring the creation of a structured data model suitable for insightful analytics.

## Features

- **Database and Data Lake Setup:** Initialized a PostgreSQL database with schemas and tables for order and item data storage. Configured folders within a the device for storing additional data files.
  
- **Data Extraction:** Extracted data from PostgreSQL using custom SQL queries, read files from the data lake folder structure, and integrated real-time exchange rates fetched from APIs.

- **Data Quality Checks:** Performed null checks, duplicate checks, and data validation to ensure data integrity and consistency. Prepared, cleaned and validated data for staging.

- **Data Transformation:** Implemented various transformations including currency conversion, delivery metrics calculation, and locality flag determination. Utilized lookup tables for resolving ambiguous columns and stage transformed data for further processing.

- **Data Modeling and Visualization:** Integrated orders, items, and product details into a unified dataset for in-depth analysis. Developed visualizations to illustrate key metrics and trends, and document modeling techniques and visualization choices.

![image](https://github.com/abdullahasm99/Python-ETL-Case-Study/assets/153215733/339f4187-8909-437b-ac12-b645611c3859)
![image](https://github.com/abdullahasm99/Python-ETL-Case-Study/assets/153215733/82a809ee-7ef9-4d13-812e-319b14a3a83a)
![image](https://github.com/abdullahasm99/Python-ETL-Case-Study/assets/153215733/2e1a99aa-1ebe-488f-9583-25ab61f6f5e3)


## License

This project is licensed under the [MIT] License.
