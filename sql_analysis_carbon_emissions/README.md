# SQL Carbon Emissions Analysis

## Project Overview
This project analyzes industry-level carbon emissions using SQL to identify which company contribute the most in the recent year of available data.  

It demonstrates SQL proficiency in filtering, grouping, aggregating, sorting, and exploring data quality issues that often arise in real-world datasets.


## Dataset
- **Source**: [The Carbon Catalogue](https://www.nature.com/articles/s41597-022-01178-9)  
- This project is based on a practice project from [DataCamp](https://www.datacamp.com/).
- Duration: 2013–2017  
- Countries: 28
- **Key Columns:**
  - `year` – Year of measurement
  - `product_name` – Name of the product
  - `company` – Company producing the product
  - `country` – Country of the company
  - `industry_group` – Industry category
  - `carbon_footprint_pcf` – Product Carbon Footprint (in CO₂ equivalent)

## Objective
- Rank industries by unique company count and total carbon footprint (latest year).  
- Detect and highlight reporting gaps across countries and years.  
- Practice end-to-end SQL workflow: query writing, result interpretation, and documentation.

## Key Takeaways
- Not all countries have yearly emission records.  
- Highlighting such gaps is key for reliable analysis.  
- Query Result: `queries/incomplete_emission_records.sql.png`


## SQL Query
- Count of unique companies per industry group
- Total carbon footprint (rounded to 1 decimal)
- Sorted by footprint (descending)

## Categories
- **SQL Scripts**: `carbon_emissions_analysis.sql.txt`  
- **Outputs**: `queries_carbon_emissions_analysis/` (query result screenshots)  

