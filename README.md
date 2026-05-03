# U.S. Data & IT Job Market Analysis

## Project Overview

This project analyzes U.S. occupational employment and wage data to compare salary levels, job concentration, and geographic opportunities for data and IT-related roles. The goal was to better understand how data roles compare within the broader IT job market and identify states that may offer strong opportunities based on salary and job concentration.

## Business Questions

1. What does the overall salary landscape look like across all occupations?
2. How do data roles compare to broader IT roles in terms of salary and distribution?
3. Among the states I am interested in working in, which ones offer the best combination of salary and job concentration for data roles?

## Data Source

The dataset comes from the U.S. Bureau of Labor Statistics Occupational Employment and Wage Statistics data. It includes occupational wage, employment, location, and job concentration information across U.S. states.

## Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Methods

- Cleaned and prepared occupational wage data
- Renamed columns for readability
- Converted salary, employment, and job concentration fields to numeric formats
- Created regional groupings for geographic analysis
- Classified selected occupations into data-specific and broader IT roles
- Calculated employment-weighted job concentration by state
- Built visualizations to compare salary distributions and geographic opportunity

## Key Findings

- Data roles are generally competitive within the broader IT job market.
- Database Architects and Data Scientists ranked near the top of the selected IT salary distribution.
- Salary alone does not fully explain job market opportunity; job concentration also matters.
- Among the highlighted states, North Carolina appeared to offer a strong combination of competitive salary and above-average job concentration.

## Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis
- Feature engineering
- Weighted average calculations
- Data visualization
- Salary and labor market analysis
- Communicating insights from data

## Files

- `data_it_job_market_analysis.ipynb` — full notebook analysis
- `cleaned_bls_oews_2024.csv` — cleaned dataset used for analysis
- `images/` — exported project visualizations
