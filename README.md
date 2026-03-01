# Global Developer Trends Analysis (Stack Overflow Survey)

## Project Overview
This project provides a comprehensive statistical analysis of global developer trends based on the Stack Overflow Annual Developer Survey. The analysis focuses on key industry metrics, including programming language adoption (Python), remote work trends, compensation benchmarking across different geographies, and the impact of education on earning potential.

## Key Insights
* **Technology Adoption:** Identified that **37.54%** of developers currently work with Python.
* **Work Modalities:** Found that **22.22%** of the global workforce operates in a fully remote environment.
* **Geographical Salary Benchmarking:** Conducted a median salary analysis across 40+ countries, identifying the **USA, Israel, and Switzerland** as the top-paying regions for Python developers.
* **Education Impact:** Discovered that the highest-paid specialists predominantly hold **Master’s or Bachelor’s degrees**, highlighting the correlation between formal education and high-tier compensation.

## Tasks Performed
- **Data Cleaning & Integrity:** Processed a large-scale dataset using Pandas to ensure data completeness and handle missing values.
- **Statistical Analysis:** Calculated measures of central tendency (mean, median, mode) for professional work experience to understand the industry's seniority distribution.
- **Trend Analysis:** Filtered and aggregated data to determine the popularity of specific technologies and learning paths (e.g., online courses vs. formal education).
- **Compensation Analysis:** Grouped and analyzed global salary data, applying filters for specific developer roles and locations.
- **Education Profiling:** Analyzed the educational background of the top 5th percentile of earners to identify patterns among high-compensation specialists.

## Tech Stack
* **Language:** Python
* **Library:** Pandas (Data manipulation and aggregation)
* **Environment:** Jupyter Notebook / Google Colab
* **Data Source:** Stack Overflow Developer Survey Dataset

## Project Structure
* `Analysis.ipynb`: The main Jupyter Notebook containing data cleaning, processing logic, and visualization.
* `survey_results_public.csv`: (Optional/Link) Raw survey data.
* `survey_results_schema.csv`: Metadata describing the survey questions.

## How to Run
1. Clone this repository.
2. Ensure you have `pandas` installed:
   ```bash
   pip install pandas
