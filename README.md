Crowdfunding ETL Mini Project

This project is part of a one-week ETL (Extract, Transform, Load) mini project, where you will practice building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform data. After transforming the data, you’ll create CSV files, build an Entity-Relationship Diagram (ERD), define table schemas, and load the data into a Postgres database.

Project Overview

The goal of this project is to work with a partner to extract and transform data from Excel files, generate multiple CSV files, create an ERD, and load the data into a PostgreSQL database. By the end, you will have created an ETL pipeline and database schema for crowdfunding data.

Key Tasks

1. Data Extraction and Transformation

	•	Extract data from crowdfunding.xlsx and contacts.xlsx.
	•	Use Python, Pandas, and either dictionary methods or regular expressions to clean and transform the data.
	•	Create multiple DataFrames (for categories, subcategories, campaigns, and contacts).
	•	Split the name column in the contacts into first_name and last_name.

2. CSV File Creation

	•	Export the transformed data to four CSV files:
	•	category.csv
	•	subcategory.csv
	•	campaign.csv
	•	contacts.csv

3. ERD and Table Schema

	•	Create an ERD to design the relationship between the tables.
	•	Use the ERD to create a Postgres-compatible table schema, defining primary keys, foreign keys, and constraints.
	•	Save the schema as crowdfunding_db_schema.sql.

4. Database Creation

	•	Create a PostgreSQL database called crowdfunding_db.
	•	Create tables in the correct order to account for foreign key relationships.
	•	Load the data from the CSV files into the Postgres database.
	•	Verify the integrity of the data by running SELECT queries on each table.
