# NBA Performance Analytics Project

## Overview
This project involves extracting and analyzing NBA player statistics using an API. The process is divided into two main phases: data scraping and data analysis.

## Data Scraping

### Setup
- **Libraries Used:** `requests` for HTTP requests, `pandas` for data manipulation, and `json` for JSON parsing.
- **Configuration:** Defined the base URL and parameters for the API requests.

### API Requests
- Implemented robust functions to manage API requests with error handling.
- Retrieved player statistics and team information from the NBA API.

### Data Extraction and Cleaning
- Parsed JSON data and extracted relevant information.
- Transformed data into a DataFrame and performed cleaning operations like removing duplicates, handling missing values, and type conversions.

### Data Storage
- Cleaned data was saved locally in CSV or Excel formats for offline analysis.

## Data Analysis

### Data Loading
- Data loaded from local files into DataFrames.

### Exploratory Data Analysis (EDA)
- Conducted statistical analyses and created visualizations like histograms, scatter plots, and box plots to explore data distributions and relationships.

### Advanced Analysis
- Performed complex analyses such as trend analysis and player performance comparison using statistical methods like regression and clustering.

### Reporting Results
- Compiled the analysis results into a readable format with visualizations.
- Summarized insights and conclusions, highlighting actionable findings.

## Results and Conclusion
This project showcased a structured approach to data gathering and analysis, demonstrating effective data-driven decision-making in sports analytics. The insights derived from the data have potential applications in predicting player performances and evaluating team strategies.

## How to Use This Repository
- **Data Scraping:** Navigate to the `scraping` directory to find the scripts used for data extraction.
- **Data Analysis:** Analysis scripts can be found in the `analysis` directory.


