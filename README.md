# NYPD Arrest Data Analysis Project
## Project Overview
This project leverages NYPD arrest data to build an interactive Power BI dashboard and conduct a comprehensive data cleaning process using Python in Jupyter Notebook. The dashboard serves to provide meaningful insights into arrest patterns, highlighting trends over time, geographical distribution, and key demographic information related to the arrests.

The analysis supports law enforcement agencies, policymakers, and researchers in understanding the dynamics of arrests in New York City, such as identifying areas with high arrest rates, analyzing offenses by severity, and uncovering trends across different demographic groups.

## NYPD Arrest Dashboard: The Power BI dashboard offers a wide range of visualizations, including:

### 1. **Arrests Over Time**
A time-series analysis showing trends in arrests on a monthly, quarterly, or yearly basis, allowing users to explore spikes and dips in arrests.
### 2. **Geospatial Mapping**
A heatmap highlighting arrest locations across the boroughs of New York City, providing a clear visual of hotspots for criminal activity.
### 3. **Demographics Breakdown**
Insights into arrests by age group, gender, and race, enabling deeper understanding of how different population groups are affected.
### 4. **Offense Types**
A breakdown of arrest types based on offense severity, categorizing arrests into major offenses like felonies, misdemeanors, and violations.
### 5. **Time of Arrest**
A visualization of when arrests typically occur during the day, segmented into morning, afternoon, evening, and night hours.

This dashboard demonstrates the use of Power BI for data visualization, advanced filtering, and drill-down capabilities, making the data easily accessible for detailed exploration.
## **Data Cleaning Process Using Python (Jupyter Notebook)**: 
A crucial part of this project was cleaning the raw arrest data to ensure accuracy, consistency, and readiness for analysis. The Python Jupyter notebook provides a thorough, step-by-step documentation of the data transformation process. Key tasks include:

### **Exploratory Data Analysis (EDA)**:
Initial data exploration to identify patterns, anomalies, and data issues. This includes reviewing descriptive statistics, value distributions, and identifying outliers.

### **Handling Missing Data:**
Identification: Missing values were found in various columns (e.g., date, offense description), which could skew analysis.
Treatment: Depending on the nature of the missing data, appropriate strategies such as imputation, forward filling, or row removal were applied.

### **Data Type Corrections:**
Dates, times, and categorical fields were standardized, ensuring that the data types were appropriate for accurate filtering and aggregation in the dashboard. For instance, arrest dates were converted into proper datetime objects, while categorical variables (like gender and race) were encoded correctly.

### **Duplicate Removal:**
Multiple identical records were identified and removed to maintain the integrity of the data. This helped avoid inflated arrest counts during analysis.

### **Standardizing and Normalizing Data:**
Inconsistent entries, such as misspelled location names or variations in offense descriptions, were standardized. This ensured uniformity across key columns like location, offense type, and demographic fields, enabling more accurate grouping and comparison in visualizations.

### **Feature Engineering:**
#### New features were created to enrich the analysis, including:

**Time of Day Buckets:** Arrests were categorized by time of day (e.g., morning, afternoon, night), allowing analysis of peak arrest hours.

**Offense Severity:** A classification system was added to group offenses into categories like "Felony," "Misdemeanor," and "Violation," which were then used in the dashboard.
Validation and Testing:

After cleaning, the data was rigorously validated by checking summary statistics and ensuring the cleaned dataset aligned with expectations. Cross-validation against known benchmarks helped ensure the integrity of the dataset.

## Tools Used:

### **Python Libraries:**

**Pandas:** For handling dataframes, data wrangling, and cleaning processes.

**NumPy:** For numerical operations, particularly in data transformations.

**Matplotlib/Seaborn:** To visualize patterns during EDA, ensuring a thorough understanding of the dataset before cleaning.

**Jupyter Notebook:** Used to create an interactive and well-documented data cleaning process that tracks each step of the transformation.

**Power BI:** For creating intuitive and insightful visualizations, making it easy for users to engage with the arrest data.
