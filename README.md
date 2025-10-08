# Dsiability_Analysis
Project Overview
This project focuses on analyzing and visualizing disability health records from the 
[U.S. Centers for Disease Control and Prevention (CDC)](https://www.cdc.gov/) to identify 
key patterns and high-risk demographics.  
The analysis leverages Databricks (Apache Spark) for distributed processing of 
large-scale datasets (1.2M+ records) and Python visualization libraries for insights.

Tech Stack
- **Platform:** Databricks  
- **Big Data Engine:** Apache Spark (PySpark)  
- **Language:** Python  
- **Visualization:** Matplotlib, Seaborn  
- **Version Control:** Git & GitHub  
- **Dataset:** CDC Disability & Health Data System (DHDS)

Data Processing Workflow
1. **Data Ingestion:** Loaded raw CDC dataset directly into Databricks Spark environment.  
2. **Data Cleaning:**  
   - Handled missing values and footnote symbols.  
   - Standardized fields for analysis consistency.  
3. **Transformation:**  
   - Segmented disability indicators (Hearing, Vision, Cognitive, etc.).  
   - Filtered by year, region, and demographic variables.  
4. **Exploratory Data Analysis (EDA):**  
   - Generated descriptive stats (mean, confidence intervals, weighted numbers).  
   - Identified high-risk categories.  
5. **Visualization:**  
   - Created plots to show disability trends over time.  
   - Mapped state-wise prevalence with geolocation data.  
6. **Optimization:**  
   - Improved PySpark query performance by 70% using partitioning and selective projections.
