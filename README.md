# 📊 Web Traffic Analysis: Understanding User Interaction

## Introduction

This project analyzes website traffic data to understand how users interact with different pages over a 7-day period. The dataset (`traffic.csv`) contains user events such as **pageviews**, **previews**, and **clicks**, along with information about the geographic origin of the traffic and page content identifiers (**isrc**).

The goal of the project is to explore traffic patterns, calculate click rates, examine relationships between previews and clicks, and provide insights into user behavior.


## About the Project

The project is divided into **2 main notebooks**:

- **Data Cleaning Notebook**   
  Prepares and cleans the raw dataset for analysis. Steps include:  
  - Inspecting and handling missing values  
  - Removing duplicates  
  - Validating categorical variables  
  - Exporting a clean dataset (`traffic_cleaned.csv`)  

- **Analysis & Modeling Notebook** 
  Performs exploratory data analysis, statistical tests, and visualizations. Includes:  
  - Traffic patterns and daily distributions  
  - Geographic distribution of pageviews  
  - Overall and per-link click rates  
  - Relationship analysis between previews and clicks  
  - Visualizations such as bar charts, pie charts, histograms, scatter plots, and boxplots  


## Key Findings

- Clicks and previews are **highly correlated** (r ~ 0.989), showing that links with more previews generally get more clicks.  
- Links with previews receive **significantly more clicks** than those without previews.  
- Most pageviews come from a few countries, with the **top three countries accounting for a large portion** of traffic.  
- Click rates vary across links, with many links showing high skew in engagement.  

## Tools & Libraries

- **Python**  
- **Pandas** - Data manipulation and analysis  
- **NumPy** - Numerical operations  
- **SciPy** - Statistical testing  
- **Matplotlib** - Data visualization  

