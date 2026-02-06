
# Credit Risk Data Warehouse & Analytics

This project demonstrates an end-to-end **ETL and SQL-based data warehouse**
implementation using a real-world credit risk dataset.

The primary focus of the project is **data modeling, SQL analytics, and ETL
pipeline design**, rather than visualization or dashboarding.

## Project Overview
- Build a structured data warehouse from raw CSV data
- Apply ETL principles using Python and SQL
- Design dimension and fact tables (star schema)
- Generate analytical KPIs using pure SQL
  
## Tech Stack
- Python (Pandas, NumPy)
- SQLite
- SQL
- Kaggle Dataset (UCI Credit Card Default)


## ETL Pipeline
### Extract
- Raw credit card data loaded from CSV into Pandas

### Transform
- Column name standardization
- Business logic applied for risk segmentation
- Data normalization through dimension tables

### Load
- Transformed data loaded into a SQLite data warehouse
- Staging, dimension, and fact tables created using SQL


## Data Model
- **RAW_CREDIT** – staging table
- **DIM_CUSTOMER** – customer demographic dimension
- **DIM_RISK** – credit risk segmentation dimension
- **FACT_CREDIT** – transactional and behavioral metrics

This schema follows a **star schema design** to support analytical queries.

## Key SQL Analytics
- Customer distribution by risk segment
- Default rate by risk category
- Average credit limit per risk group
- Credit behavior analysis using payment and billing metrics

All KPIs are generated using **SQL queries executed on the data warehouse**.


## Key KPIs
- Customer distribution by risk segment
- Default rate by risk level
- Average credit limit per risk group

## Project Scope
This project is intended to demonstrate:
- SQL proficiency
- Data warehouse design skills
- ETL pipeline implementation
- Analytical thinking using structured data

## How to Run
1. Download the dataset from Kaggle (UCI Credit Card Default)
2. Place the CSV file in the data directory
3. Run the notebook in the `notebooks/` folder to execute the ETL pipeline


