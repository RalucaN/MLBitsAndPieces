# SQL Project: Exploring the World's Oldest Businesses

## Project Description

This project was initially completed on [DataCamp](https://app.datacamp.com/learn/projects/worlds_oldest_businesses) and has been improved upon. The enhancements include adding Python code to create the database, SQL tables, and functions to streamline the process of querying the database.

The project explores data from BusinessFinancing.co.uk on the world's oldest businesses. The data, contained in several different datasets, is analyzed using SQL techniques to merge and manipulate the data. This provides insights into these historic businesses, their longevity, and the industries they operate in.

## Project Structure

The project is structured as follows:

- `notebook.ipynb`: This Jupyter notebook contains the SQL queries and analysis for the project.
- `datasets/`: This directory contains the data for the project in CSV format.
- `datasets/createdb.sql`: This SQL script creates the database for the project.

## Libraries

The project uses the following Python libraries:

- `sqlite3`: This library provides a lightweight disk-based database that doesn't require a separate server process. It's used to interact with the SQL database.
- `pandas`: This library provides high-performance, easy-to-use data structures and data analysis tools. It's used to load the CSV data and analyze the results of the SQL queries.

## Aim

The aim of this project is to understand the longevity of businesses and the industries they belong to. By exploring data on the world's oldest businesses, we can gain insights into how businesses survive changing market conditions.

## Tasks

The main tasks in this project include:

1. **How many businesses were founded before 1000?** This task involved finding the count of businesses that have been around for more than a millennium.
2. **Which businesses were founded before 1000?** This task provided more detail on the businesses that have survived for over a thousand years.
3. **Exploring the categories:** This task involved joining the `businesses` and `categories` tables to get a better understanding of the industries these old businesses operate in.
4. **Counting the categories:** This task involved analyzing the most common industries among the world's oldest businesses.
5. **Oldest business by continent:** This task involved joining the `businesses` and `countries` tables to find out how old the oldest business is on each continent.
6. **Joining everything for further analysis:** This task involved joining all three tables (`businesses`, `categories`, and `countries`) to create a comprehensive dataset for further analysis.

## Outcome

The outcome of this project is a detailed analysis of the world's oldest businesses, providing insights into their longevity and the industries they operate in.
