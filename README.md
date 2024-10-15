# Snowflake Sample Data Transformation Project

## Overview

This project uses **Snowflake's sample data** database, focusing on the `orders` and `lineitems` tables. It employs **dbt (data build tool)** to perform data transformations, aggregating data from the two tables and creating a new table with enhanced data for analysis.

## Requirements

- **Snowflake Account**
- **dbt** (data build tool)

## Setup

1. Clone the repository and navigate to the project directory.
2. Configure your Snowflake connection in `profiles.yml`.
3. Install dbt dependencies and run the models with `dbt run`.

## Transformation Process

1. **Data Aggregation**: Join and aggregate data from the `orders` and `lineitems` tables.
2. **Column Renaming**: Rename certain columns for improved clarity.
3. **Create Final Table**: Generate a new table with the transformed data for further analysis.

## Running Tests

Use `dbt test` to validate the data transformations.
