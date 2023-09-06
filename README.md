# Crowdfunding_ETL #
## Overview
This is a practice project aimed at building an ETL (Extract, Transform, Load) pipeline using Python, Pandas, Python dictionary methods, and regular expressions. This pipeline extracts data from two given raw datasets (crowdfunding.xlsx and contacts.xlsx), transforms this data, and finally loads it into a Postgres database. Four CSV files are generated in the process and used for creating an Entity-Relationship Diagram (ERD) and a table schema.

## Project Structure
- **ETL_Mini_Project_APontelli_CZhuang.ipynb**: The main Jupyter Notebook script that orchestrates the ETL process.
- **crowdfunding_db_schema.sql**: Database table Schema.
- **QuickDBD**: A scratch of Database schema.
- **/Resources**: Folder containing the raw datasets crowdfunding.xlsx, contacts.xlsx and generated four .csv files.

## Features
- Creates the Category, Subcategory, and Campaign DataFrames from crowdfunding.xlsx.
- Creates the Contacts DataFrame from contacts.xlsx.
- Creates a Crowdfunding Database based on the four DataFrames generated.
- Generates four CSV files(category.csv, subcategory.csv, campaign.csv, contacts.csv) used for creating an ERD and a table schema.
