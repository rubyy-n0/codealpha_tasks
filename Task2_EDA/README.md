# CodeAlpha Data Analytics Internship

## Task 2: Exploratory Data Analysis (EDA)
### Project: Bike Sharing Dataset Analysis

**Domain:** Data Analytics  
**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

### 1. Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Bike Sharing Dataset using Python.

The objective is to explore, clean and analyze the dataset to understand bike rental patterns and identify relationships between rental demand, time, seasons, weather conditions and user categories.

### 2. Dataset

**Dataset:** Bike Sharing Dataset (`hour.csv`)

**Number of records:** 17,379

**Number of columns:** 17

The dataset contains hourly bike rental records, including date, season, hour, weather conditions, temperature, humidity, wind speed and customer rental counts.

### 3. Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### 4. Analysis Performed

The project includes:

1. Dataset Exploration and Inspection
2. Data Cleaning and Preparation
3. Missing Value Analysis
4. Duplicate Record Detection
5. Descriptive Statistical Analysis
6. Hourly Bike Rental Analysis
7. Seasonal Rental Analysis
8. User Type Comparison
9. Weather Impact Analysis
10. Working Day Comparison
11. Correlation Analysis
12. Data Visualization

### 5. Key Findings

- The dataset contains 17,379 records and 17 columns.
- No missing values were identified during the initial data inspection.
- No duplicate records were identified.
- Bike rental demand varies across different hours and seasons.
- Registered users contribute the majority of bike rentals.
- Weather conditions are associated with changes in rental demand.

### 6. Business Recommendations

- Analyze peak rental periods to improve bike availability.
- Consider seasonal demand when planning operational resources.
- Focus on customer retention and registered user engagement.
- Monitor weather conditions when planning bike distribution.
- Use data-driven insights to improve operational efficiency.

### 7. Project Structure

```text
Task2_EDA/
|
|-- eda_analysis.ipynb
|-- hour.csv
|-- README.md
|
|-- outputs/
    |
    |-- bike_sharing_cleaned.csv
    |-- descriptive_statistics.csv
    |-- hourly_rental_summary.csv
    |-- seasonal_rental_summary.csv
    |-- user_type_summary.csv
    |-- weather_rental_summary.csv
    |
    |-- charts/
```

### 8. How to Run

1. Install Python.
2. Install the required libraries:

   `pip install pandas numpy matplotlib seaborn`

3. Open `eda_analysis.ipynb` in VS Code.
4. Ensure `hour.csv` is available in the Task2_EDA folder.
5. Run the notebook cells sequentially.

### 9. Conclusion

This project demonstrates the importance of Exploratory Data Analysis in understanding and preparing real-world datasets.

Through data inspection, cleaning, statistical analysis and visualization, the project identifies meaningful patterns in bike-sharing usage.

The findings provide a foundation for understanding customer behavior and supporting data-driven operational decisions.

---

**Internship:** CodeAlpha Data Analytics  
**Project Status:** Completed
