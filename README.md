# Project 2

# Crowdfunding ETL Mini-Project
---

This repository contains the code and files for the Crowdfunding ETL (Extract, Transform, Load) mini-project. The project involves building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform data from Excel files. The transformed data is then used to create a PostgreSQL database.

## Project Overview

In this mini-project, we work with a partner to:

- Extract and transform data from crowdfunding.xlsx and contacts.xlsx Excel files.
- Create four CSV files based on the transformed data.
- Use the CSV data to create an Entity-Relationship Diagram (ERD) and define a table schema.
- Create a PostgreSQL database named crowdfunding_db and import the CSV data into corresponding tables.
- Verify the data import by running SELECT queries on each table.

## Project Structure

The project is divided into the following sections:

1. **Create the Category and Subcategory DataFrames**
   - Extract and transform data from crowdfunding.xlsx to create category.csv and subcategory.csv.

2. **Create the Campaign DataFrame**
   - Extract and transform data from crowdfunding.xlsx to create campaign.csv.

3. **Create the Contacts DataFrame**
   - Extract and transform data from contacts.xlsx to create contacts.csv.

4. **Create the Crowdfunding Database**
   - Sketch an ERD and define a table schema.
   - Create the crowdfunding_db database and import CSV data into corresponding tables.
   - Verify data import using SELECT queries.

## Files Included

- **ETL_Mini_Project_NRomanoff_JSmith.ipynb**: Jupyter notebook containing the Python code for the ETL pipeline.
- **Resources**: Folder containing the crowdfunding.xlsx and contacts.xlsx files.
- **category.csv**: Transformed data file containing category information.
- **subcategory.csv**: Transformed data file containing subcategory information.
- **campaign.csv**: Transformed data file containing campaign information.
- **contacts.csv**: Transformed data file containing contact information.
- **crowdfunding_db_schema.sql**: PostgreSQL database schema file.

## Instructions for Running the Project

1. Clone the repository to your local machine.
2. Open the ETL_Mini_Project_NRomanoff_JSmith.ipynb notebook in Jupyter Notebook or JupyterLab.
3. Follow the instructions in the notebook to execute the code cells and complete the ETL process.
4. After completing the ETL process, you can explore the generated CSV files and the database schema file.
5. Create a PostgreSQL database named "crowdfunding_db" and execute the crowdfunding_db_schema.sql script to create the required tables.
6. Import the CSV files into the corresponding tables in the PostgreSQL database.
7. Verify the data import by running SELECT queries on each table.



### Versions Used
- Python: 3.9.7
- Pandas: 1.3.3

---

This README provides an overview of the project, setup instructions, and information about the versions of the programs used. Let me know if you need any further adjustments!

