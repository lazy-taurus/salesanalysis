# Diwali Sales Data Analysis: A Comprehensive Study of Consumer Behavior

## 1. Introduction

This project details a data-driven exploration of Diwali sales data, with the primary objective of uncovering patterns in consumer purchasing behavior. The analysis focuses on correlating sales performance with demographic variables, including gender, age group, marital status, occupation, and geographic location.

## 2. Methodology

### 2.1 Data Preparation

The initial phase involved meticulous data preprocessing to ensure data quality and integrity. This included:

* **Data Loading**: Importing the `Diwali Sales Data.csv` dataset into a pandas DataFrame.
* **Cleaning**: Dropping irrelevant columns (`Status`, `unnamed columns`) and handling missing values to prevent analytical bias.
* **Feature Engineering**: Converting the `Amount` column to an appropriate data type and renaming columns like `Marital_Status` to `Shaadi` for enhanced readability.

### 2.2 Exploratory Data Analysis (EDA)

A systematic EDA was performed to derive insights, utilizing various data visualization techniques. Key areas of focus included:

* **Demographic Segmentation**: Analyzing sales and order distributions across different age groups, genders, and states.
* **Purchasing Power Analysis**: Investigating the correlation between marital status, occupation, and total sales.
* **Product Performance**: Identifying the most popular product categories and individual items based on order frequency and sales volume.

## 3. Key Findings & Conclusion

The analysis reveals a dominant customer segment: **married women aged 26-35, primarily from Uttar Pradesh, Maharashtra, and Karnataka, working in the IT, Healthcare, and Aviation sectors.** This group shows the highest purchasing power, with a strong preference for products in the Food, Clothing, and Electronics categories. These findings provide a clear target audience for future marketing and sales initiatives.

---

## 4. Future Scope

* **Time-Series Forecasting**: Developing a predictive model to forecast future sales trends.
* **Advanced Segmentation**: Employing clustering algorithms to create more granular customer segments.

---

## 5. Repository Structure

* `Diwali Sales Data.csv`: The raw dataset.
* `diwali_sales_analysis.ipynb`: The Jupyter Notebook containing all the code and analysis.

---

## 6. How to Run the Analysis

1.  **Clone the repository**:
    `git clone https://github.com/lazy-taurus/salesanalysis.git`
2.  **Install dependencies**:
    `pip install pandas numpy matplotlib seaborn`
3.  **Open the notebook**:
    Launch Jupyter Notebook and open the `diwali_sales_analysis.ipynb` file.
4.  **Run the cells**:
    Execute the cells sequentially to reproduce the analysis and visualizations.

---

