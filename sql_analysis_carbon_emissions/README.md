# SQL Carbon Emissions Analysis

## 📌 Project Overview
This project analyzes industry-level carbon emissions using SQL to identify which sectors contribute the most in the most recent year of available data.  
Applied SQL skills in filtering, grouping, aggregating, and sorting results.

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
Analyze carbon emissions by industry group, counting unique companies and total carbon footprint for the most recent year.

## SQL Query
- Count of unique companies per industry group
- Total carbon footprint (rounded to 1 decimal)
- Sorted by footprint (descending)

## Files
- `carbon_emissions_analysis.sql.txt` – SQL query script
- `image_carbon_emissions_analysis/` – Query result screenshots
