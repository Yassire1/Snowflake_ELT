# Snowflake DBT Project

This project demonstrates how to use dbt to perform data transformations on the `SNOWFLAKE_SAMPLE_DATA` database. It uses the `orders` and `lineitems` tables to create an aggregated table with renamed columns.

## Project Overview

- **Source Database**: `SNOWFLAKE_SAMPLE_DATA`
- **Source Tables**: `orders`, `lineitems`
- **Transformation Tool**: [dbt (Data Build Tool)](https://www.getdbt.com/)
- **Objective**: Aggregate data from the `orders` and `lineitems` tables, rename columns, and create a new table with the transformed data.

## Prerequisites

Before starting, make sure you have:

- A Snowflake account with access to `SNOWFLAKE_SAMPLE_DATA`.
- dbt installed locally and set up with Snowflake. Refer to the [dbt setup guide](https://docs.getdbt.com/docs/installation) if you need help.

## Setup

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
