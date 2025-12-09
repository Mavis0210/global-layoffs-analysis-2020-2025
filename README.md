# Global Layoffs: 2020–2025 Dashboard



This project analyzes worldwide layoffs between 2020 and 2025. I cleaned the dataset in SQL, exported the final table as a CSV, and used it to build a Power BI dashboard that highlights key trends, year-to-year changes, and the companies and regions most affected.



## Data Preparation (SQL)



Before creating the dashboard, I ran a full cleaning process in SQL, which included:

- fixing inconsistent date formats

- converting text-based numeric fields

- trimming extra spaces

- removing duplicates

- handling missing or incomplete entries

- creating the final staging table for export

The cleaned table was then exported as layoffs\_cleaned.csv for use in Power BI.



## Dashboard Contents



The dashboard includes:



- Total Layoffs by Year (line chart)

- KPI Card: Total Layoffs

- Company Dropdown (Slicer)

- Top Companies by Total Layoffs (bar chart)

- Country-Level Layoffs Map

- Continent Slicer

- Year-to-Year Summary Table with YoY % Change



The aim was to keep the layout clear and focused on the main insights.



## How to Use



1. Download or clone the repository
2. Open Layoffs.pbix in Power BI Desktop
3. Keep the CSV file in the same folder so Power BI can find it
4. Refresh the data model if needed



## Dashboard Preview



![Dashboard](/screenshots/dashboard.png)


## Key Insights

- Layoffs peaked in 2023 with over 213,000 layoffs, followed by a decline in 2024 and 2025.  
- Intel and Amazon are the companies with the highest layoffs across the period.  
- North America experienced the largest share of layoffs, followed by Asia, then Europe.  
- Although 2023 had the highest total layoffs, the strongest year-over-year growth occurred in 2022 (+8.51%), while growth was modest in 2023 (+0.42%).  

## Recommendations

- Organizations should monitor layoff trends to anticipate market shifts, talent availability, and industry changes.  
- Policymakers and stakeholders could consider supporting retraining/upskilling programs in regions most affected by layoffs.    


## Notes / Next Steps



If I expand this project in the future, I may:



- connect Power BI directly to the SQL database

- add more DAX measures (rolling metrics, forecasts, industry breakdowns)

- build drill-down pages for companies or countries



## Purpose of This Project



The goal of this project was to take a messy raw dataset, clean it properly using SQL, and turn it into a clear and interactive dashboard in Power BI. It forms part of my broader data analytics portfolio.

