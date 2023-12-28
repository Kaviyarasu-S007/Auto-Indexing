# Auto-Indexing Project with PostgreSQL

## Overview

This project demonstrates an auto-indexing mechanism for PostgreSQL databases using Python and the Faker library to generate sample data. The goal is to dynamically create indexes based on query workload analysis, optimize performance, and provide insights into query execution.

## Prerequisites

- Python 3.x
- PostgreSQL
- psycopg2 library (`pip install psycopg2`)
- Faker library (`pip install Faker`)

## Setup

1. **Database Configuration:**

   Make sure you have PostgreSQL installed and running. Update the connection details (host, port, database, user, password) in the provided Python scripts.

2. **Run the Scripts:**

   Execute the provided Python scripts in the following order:

   - `connection.py`: Establishes a connection to the PostgreSQL database.
   - `table_creation.py`: Creates sample tables (users, movies, genres, ratings, subscriptions).
   - `insert_values.py`: Inserts sample data into the tables.
   - `print_table_values.py`: Prints the values of the created tables.
   - `cost_based_algorithm.py`: Implements a cost-based algorithm for query workload analysis.
   - `verification_1.py` to `verification_3.py`: Verify and analyze the impact of the indexing strategy.

3. **Test and Validation:**

   - `test_and_validation.py`: Tests the execution time of sample queries with and without indexes.

4. **Visualization:**

   - `visualization.py`: Generates plots for index usage statistics.
     ![image](https://github.com/Kaviyarasu-S007/Auto-Indexing/assets/151661034/a6bb14b7-e542-47bd-9843-259e351c4042)
     ![image](https://github.com/Kaviyarasu-S007/Auto-Indexing/assets/151661034/092d314d-d312-49f1-94dc-73aee5b564e4)



5. **Monitor and Refine:**

   - `monitor_and_refine.py`: Monitors query execution time over iterations, allowing for refinement.

6. **Cleanup:**

   - `drop_table.py`: Drops the created tables.

## Results

- The project provides insights into the query workload, index usage, and execution time improvements.

## Notes

- Adjust the number of sample records and queries as needed for your testing.
- This is a basic template, and you can expand it based on your specific requirements and database schema.
