# README - Data Visualization and Statistical Analysis Lab

## Purpose

This lab was conducted as part of the MSCS 634 course to apply data visualization, preprocessing, and statistical analysis techniques on a real-world dataset using Jupyter Notebook. I selected the **Walmart Sales dataset** to explore sales trends, clean the data, detect outliers, scale numeric features, and perform key statistical evaluations.

---

## Key Insights

- **Visualizations:**
  - The scatter plots revealed relationships between store numbers and weekly sales, highlighting which stores consistently perform better.
  - Bar charts and histograms showed the distribution of sales across categories and time, revealing sales peaks and low periods.
  - The correlation heatmap identified moderate relationships between economic indicators (like CPI and unemployment) and weekly sales.

- **Statistical Measures:**
  - Calculated min, max, mean, median, mode, variance, and standard deviation for key numeric columns like `Weekly_Sales`, `Temperature`, and `Fuel_Price`.
  - Identified and removed outliers using the IQR method, improving the data’s reliability for future modeling.
  - Applied Min-Max scaling to normalize numeric data, preparing it for potential machine learning applications.

---

## Challenges and Decisions

- **Missing Data Handling:**  
  Some columns contained missing values; I decided to fill numeric columns with the mean and categorical columns with the mode to preserve as much data as possible.

- **Outlier Removal:**  
  Outliers were identified in `Weekly_Sales` using the IQR method. I carefully removed only extreme outliers to avoid distorting the dataset.

- **Scaling Decisions:**  
  Not all columns were scaled — only numeric columns relevant to analysis (dates were excluded or converted appropriately).

- **Correlation Analysis:**  
  To avoid errors, I ensured only numeric columns were used for correlation, which required careful selection and sometimes dropping non-numeric or incomplete data.

---

This lab provided valuable practice in preparing raw data for deeper analysis, interpreting statistical outputs, and improving the dataset’s quality for future tasks.
