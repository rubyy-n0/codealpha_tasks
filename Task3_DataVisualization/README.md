# CodeAlpha Data Analytics Internship

## Task 3: Data Visualization
### Project: Bike Sharing Dataset Analysis

**Domain:** Data Analytics  
**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

### 1. Project Overview

This project focuses on visualizing bike-sharing rental patterns using Python.

The objective is to transform raw data into meaningful visual representations, identify important trends and relationships, and communicate insights about customer behavior and rental demand.

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

### 4. Visualizations

The project includes:

1. Seasonal Rental Analysis
2. Hourly Rental Analysis
3. User Type Comparison
4. Weather Impact Analysis
5. Working Day Comparison
6. Rental Distribution Histogram
7. Seasonal Box Plot
8. Temperature Scatter Plot
9. Correlation Heatmap
10. Combined Bike Sharing Analytics Dashboard

### 5. Key Findings

- Peak average rental demand occurs at 5 PM (17:00).
- Lowest average rental demand occurs at 4 AM (04:00).
- Fall has the highest average seasonal rental demand.
- Spring has the lowest average seasonal rental demand.
- Registered users contribute approximately 81.17% of total rentals.
- Clear weather has the highest average rental demand.
- Heavy Rain / Snow has the lowest average rental demand.

### 6. Business Recommendations

- Maintain sufficient bike availability during peak rental hours.
- Plan operational resources according to seasonal demand.
- Improve registered customer retention through membership benefits.
- Consider weather conditions when planning bike distribution.
- Use rental trends to improve operational efficiency and customer satisfaction.

### 7. Project Structure

```text
Task3_DataVisualization/
|
|-- data_visualization.ipynb
|-- README.md
|
|-- outputs/
    |
    |-- charts/
        |-- seasonal_rentals.png
        |-- hourly_rentals.png
        |-- user_type_comparison.png
        |-- weather_rentals.png
        |-- workingday_comparison.png
        |-- rental_distribution.png
        |-- seasonal_boxplot.png
        |-- temperature_scatterplot.png
        |-- correlation_heatmap.png
        |-- bike_sharing_dashboard.png
```

### 8. How to Run

1. Install Python.
2. Install the required libraries:

   `pip install pandas numpy matplotlib seaborn`

3. Open `data_visualization.ipynb` in VS Code.
4. Ensure the original `hour.csv` dataset is available in the `Task2_EDA` folder.
5. Run the notebook cells sequentially.

### 9. Conclusion

This project demonstrates how data visualization can transform raw bike-sharing data into meaningful insights.

Using different visualization techniques, the project explores rental trends, seasonal patterns, customer behavior and relationships between environmental conditions and bike rental demand.

The combined analytics dashboard presents the major findings in an organized and understandable format, supporting data-driven decision-making.

---

**Internship:** CodeAlpha Data Analytics  
**Project Status:** Completed
