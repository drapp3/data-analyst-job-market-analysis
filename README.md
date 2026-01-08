# Data Analyst Job Market Analysis

Analysis of 2,250+ data analyst job postings using Python and Tableau to identify in-demand skills and market segments.

**[View Interactive Dashboard](https://public.tableau.com/views/DataAnalystJobPostingAnalysis_17636024090960/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

## Key Findings

- SQL (62%) and Excel (61%) dominate across all experience levels
- Python (28%) and Tableau (28%) tied for 3rd/4th most requested
- Machine Learning mentioned in 21% of postings
- Only 5% of jobs explicitly labeled "Entry Level"

## Cluster Analysis

Applied k-means clustering to segment the job market by skill mix, seniority, and location:

| Cluster | Description | Top Skills |
|---------|-------------|------------|
| SAS/Legacy | Healthcare/pharma roles | SAS, SQL, Excel |
| Traditional BI | Largest segment | SQL, Excel, Statistics |
| Python-focused | Technical analyst roles | Python, SQL, Excel |
| Big Data | Engineering-adjacent | Spark, SQL, Python |

## Tools & Technologies

- **Python**: pandas, numpy, scikit-learn
- **Visualization**: Tableau
- **Analysis**: K-means clustering, text parsing, feature engineering

## Project Files

- `data_analyst_cleaning.ipynb` - Data cleaning, analysis, and clustering pipeline

## Dataset

2,252 Data Analyst job postings from Glassdoor  
Location: United States (Top states: CA, TX, NY)
