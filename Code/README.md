# SQL Code & Notebooks

This folder contains SQL transformation code used in the project.

## Notebooks

### Silver Layer Transformation
- File: `Silver_Transformation.sql`
- Purpose: Clean and parse raw data from Bronze
- Key operations:
  - Timestamp parsing
  - Nested JSON extraction
  - Data validation

### Gold Layer Star Schema
- File: `Gold_StarSchema.sql`
- Purpose: Create optimized star schema
- Tables created:
  - fact_consumption
  - dim_date
  - dim_hour
  - dim_usergroup

## Data Pipeline
- Configuration details for Fingrid API integration
- Pagination handling
- Authentication setup
