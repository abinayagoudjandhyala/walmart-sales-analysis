
# Walmart Sales Analysis

## Table of Contents
- [Overview](#overview)
- [Project Workflow](#project-workflow)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Insights and Observations](#insights-and-observations)
  - [Dashboard 1](#dashboard-1)
  - [Dashboard 2](#dashboard-2)
- [Getting Started](#getting-started)
- [Kaggle Dataset](#kaggle-dataset)
- [Future Improvements](#future-improvements)

---

## Overview

This project is a comprehensive analysis of Walmart's sales data, showcasing insights into sales performance, seasonal trends, and forecasting. It integrates Python for data cleaning and preparation, MySQL for in-depth analysis, and Power BI for visualization. The goal is to extract actionable insights and present them in an interactive and visually appealing manner.

---

## Project Workflow

1. **Data Extraction and Cleaning (Python)**  
   - The dataset was loaded and cleaned using Python libraries like `pandas`.
   - Cleaned data was exported as `walmart_clean_data.xls` for further analysis.

2. **Data Analysis (MySQL)**  
   - The cleaned data was imported into MySQL.
   - SQL queries were used to perform operations such as aggregations, filtering, and data segmentation. The queries are documented in `Queries.sql`.

3. **Data Visualization (Power BI)**  
   - Cleaned data was used to build interactive dashboards in Power BI.
   - Two dashboards were created, each focusing on different aspects of sales data.
   - The complete Power BI file (`Walmart.pbix`) is included in the project for further exploration and customization.

---

## Technologies Used

- **Python**: Data cleaning and transformation (`pandas`).
- **MySQL**: Analytical queries and data exploration.
- **Power BI**: Interactive dashboards for visualizing insights.
- **Kaggle API**: Dataset retrieval.

---

## File Structure

```
├── my_env1/                  # Virtual environment (optional)
├── output_folder/            # Outputs (if applicable)
├── Dashboard1.png            # First dashboard visualization
├── Dashboard2.png            # Second dashboard visualization
├── Walmart.pbix              # Power BI file containing interactive dashboards
├── icon1.jpeg                # Supporting visual assets
├── icon2.jpeg
├── icon3.jpg
├── icon4.jpeg
├── project.ipynb             # Jupyter notebook for data preparation
├── Queries.sql               # SQL queries for analysis
├── requirements.txt          # Python dependencies
├── Walmart.xls               # Raw dataset
├── walmart_clean_data.xls    # Cleaned dataset
└── walmart-10k-sales-datasets.zip # Original dataset zip file
```

---

## Insights and Observations

### Dashboard 1
**Key Metrics and Features**:
- **Total Units Sold**: Shown as a line graph alongside total revenue.
- **Total Revenue**: Visualized in bar charts and as part of top products analysis.
- **Profit Margin**: Highlighted in the "Sales by Region" section, showing variances across regions.
- **Filters**: Interactive filters by store city, product category, and year.

**Key Insights**:
1. **Seasonality**: Sales peak in December, suggesting a strong holiday shopping influence, while the lowest sales occur in June.
2. **Top Products**: "Fashion accessories" and "Home and Lifestyle" categories dominate revenue generation.
3. **Geographic Trends**: North America and Europe are key regions, with varying profit margins.

### Dashboard 2
**Key Metrics and Features**:
- **Seasonal Trends**: Line chart showing monthly revenue fluctuations.
- **Forecasting**: Line chart projecting revenue trends with confidence intervals.
- **Product Distribution**: Pie chart displaying the contribution of each category to total revenue.
- **Average Rating**: Gauge chart presenting customer satisfaction (average: 5.83/10).

**Key Insights**:
1. **Time Series Analysis**: Revenue dips in January after the holiday season and reaches the lowest in mid-year.
2. **Forecasting**: Revenue shows a projected upward trend from 2023 onwards.
3. **Product Popularity**: Similar to Dashboard 1, "Fashion accessories" and "Home and Lifestyle" categories lead in revenue contribution.

---

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repository-url
   ```
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run Jupyter Notebook**:
   - Open `project.ipynb` and run all cells to prepare and clean the data.
4. **Set Up MySQL**:
   - Import the cleaned data (`walmart_clean_data.xls`) into your MySQL database.
   - Execute the SQL queries in `Queries.sql` for analysis.
5. **View Dashboards**:
   - Open `Walmart.pbix` in Power BI to explore interactive dashboards.
   - Alternatively, view `Dashboard1.png` and `Dashboard2.png` for static insights.

---

## Kaggle Dataset

The dataset used for this project is available on Kaggle:  
[Walmart Sales Dataset](https://www.kaggle.com/datasets/najir0123/walmart-10k-sales-datasets)

To download the dataset, use the Kaggle API or manually download and place it in the project directory.

---

## Future Improvements

1. **Enhanced Visualizations**: Add more drill-down capabilities in dashboards for granular analysis.
2. **Advanced Forecasting**: Implement machine learning models for more accurate revenue predictions.
3. **Automated Workflow**: Use scripts or workflows to automate the entire analysis pipeline.

---

## Acknowledgments

- Dataset: [Kaggle](https://www.kaggle.com/datasets/najir0123/walmart-10k-sales-datasets)
- Tools: Python, MySQL, Power BI
```

