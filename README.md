# Data Professional Survey Dashboard

An interactive Power BI dashboard analyzing a survey of 630 data professionals: roles, salaries, favorite programming languages, countries, job satisfaction, and how hard it was to break into data.

![Dashboard](dashboard.png)

## Tools
- Power BI
- Power Query

## Data Cleaning (Power Query)
- Removed unused columns
- Split columns by delimiter to strip the "Other (Please Specify)" prefixes
- Filtered out unusable entries
- Built a numeric Average Salary column from the text salary bands (e.g., "41k-65k") by splitting into lower and upper bounds and averaging them

## Dashboard Visuals
- KPI cards: number of survey takers and average age
- Bar chart: average salary by job title
- Column chart: favorite programming language by job title
- Treemap: country of survey takers
- Donut chart: difficulty breaking into data
- Gauges: happiness with salary and with work/life balance

## Key Findings
- Python is the favorite programming language (about 67% of respondents)
- Salary is the lowest-rated satisfaction factor (4.3/10) compared with work/life balance (5.7/10)

## Files
- `Data_Professional_Survey_Dashboard.pbix`: the Power BI report
- `Power_BI_-_Final_Project.xlsx`: the raw survey data
