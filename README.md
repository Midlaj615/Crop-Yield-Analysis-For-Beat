# Crop YieldAnalysis-For Beat

## Table of Contents
- [Project Overview](#project-overview)
- [Objective](#objective)
- [Dataset Description](#dataset-description)
- [Project Tasks](#project-tasks)
- [Tools & Technologies](#tools--technologies)
- [Key Insights](#key-insights)
- [Dashboard Features](#dashboard-features)
- [Repository Structure](#repository-structure)
- [How to Use](#how-to-use)
- [Contact](#contact)


## Project Overview
This project provides a comprehensive analysis of global crop production trends in the context of climate change during the period of 1961-2022. Using time-series data from the World Bank, the Power BI report visualizes trends, compares regional performance, and highlights the impact of climate variability on agricultural output.


![Beat Project](Screenshots/beat%20project.png)


## Objective
- **Calculate Crop Production Index:** Assess changes in agricultural output relative to the base period (2014-2016 = 100).
- **Evaluate Influencing Factors:** Analyze how climate variability and economic factors impact crop yields.

## Dataset Description
- **Source:** World Bank Open Data
- **Dataset Name:** Crop Production Index (2014-2016 = 100)
- **Time Period:** 1961 to 2022
- **Key Variables:**  
  - Country Name and ISO Code  
  - Annual Crop Production Index  
  - Indicator Name and Code


## Project Tasks
1. **Data Preparation:**
   - Load and inspect the dataset.
   - Remove irrelevant columns (e.g., Unnamed: 68, 1960, 2023).
   - Reshape data from wide to long format.
   - Handle missing values appropriately (filter or interpolate).

2. **Data Exploration & Analysis:**
   - Analyze global crop production trends.
   - Compare performance across countries and regions.
   - Perform year-over-year growth analysis.
   - Apply clustering techniques to group countries with similar trends.
   - Summarize trends by decade and correlate with global events.

3. **Dashboard Development:**
   - Build an interactive Power BI dashboard with maps, line charts, bar charts, heatmaps, and clustering visuals.

## Tools & Technologies
- **Data Preparation:** Excel
- **Data Analysis:** MySQL
- **Visualization & Reporting:** Power BI
- **Documentation:** Markdown, PDF


## Key Insights
- **Overall Trends:** Determine the global crop production index over time.
- **Regional Comparisons:** Highlight top-performing and low-performing countries.
- **Growth Analysis:** Calculate year-over-year growth rates.
- **Clustering:** Identify clusters of countries with similar production behaviors.
- **Impact Analysis:** Understand how climate variability and economic events influence crop production.


## Dashboard Features
- **Global Overview:** Interactive world map and line charts displaying overall trends.
- **Regional Insights:** Bar charts and matrices comparing crop production indices.
- **Trend Analysis:** Detailed line charts and heatmaps showing year-over-year and decade trends.
- **Clustering:** Visual grouping of countries with similar production patterns.

## Repository Structure
Climate-Change-Crop-Production-Report/
├── PowerBI_Report.pbix       
├── Data_Files/
│   └── crop_production_data.csv 
├── Documentation/
│   └── Climate_Change_Crop_Production_Report.pdf  
├── Screenshots/
│   ├── Dashboard_Overview.png  
│   └── Key_Insights.png         
└── README.md     


## How to Use
1.Clone the Repository
   
   git clone https://github.com/Midlaj615/Climate-Change-Crop-Production-Report.git

2.View the Power BI Report:
   Open PowerBI_Report.pbix in Power BI Desktop or Power BI Service.

3.Review Documentation:
   Open the PDF in the Documentation/ folder for complete project instructions.

4.Explore Data:
   Check the Data_Files/ folder for the dataset used in the analysis.

## 📬 **Contact**
Name: Midlaj

LinkedIn: www.linkedin.com/in/midlajac

Email: midlajac615@gmail.com
