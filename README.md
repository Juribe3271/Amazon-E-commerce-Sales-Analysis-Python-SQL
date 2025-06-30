# Amazon E-commerce Sales Analysis: Python, SQL & Power BI

This project performs a comprehensive analysis of Amazon e-commerce sales data, utilizing Python for data cleaning and exploratory data analysis (EDA), SQL (SQLite) for efficient data storage and querying, and Power BI for creating an interactive sales dashboard to visualize key insights.

## Table of Contents

* [Project Overview](#project-overview)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Project Structure](#project-structure)
* [How to Run/View the Project](#how-to-runview-the-project)
* [Key Insights & Findings](#key-insights--findings)
* [Future Enhancements](#future-enhancements)
* [Contact](#contact)

## Project Overview

This data analysis project focuses on understanding sales trends, product performance, and geographical insights from a dataset of Amazon e-commerce sales. The goal is to transform raw data into actionable insights, demonstrating proficiency in the end-to-end data analysis pipeline from data cleaning to interactive visualization.

## Features

* **Data Acquisition & Cleaning:** Demonstrated proficiency in Python (Pandas) for importing raw CSV data (`Amazon Sale Report.csv`), handling missing values, correcting data types, and preparing data for analysis.
* **Exploratory Data Analysis (EDA):** Performed in-depth analysis using Python (Matplotlib, Seaborn) to uncover trends, identify top-performing categories and states, and understand sales distribution. Visualizations include daily sales trends, sales by category, sales by state, and B2B vs. non-B2B sales breakdown.
* **Database Integration (SQL):** Stored cleaned and transformed data in an SQLite database (`amazon_sales.db`) for efficient querying and data management.
* **Interactive Dashboard (Power BI):** Developed an interactive dashboard in Power BI Desktop to present key findings visually, allowing users to filter and explore data dynamically (e.g., by date, category, and ship-state).
* **Version Control:** Project managed using Git and hosted on GitHub for version control and collaboration.

## Technologies Used

* Python: Pandas, NumPy, Matplotlib, Seaborn, SQLite3
* SQL: SQLite
* **Microsoft Power BI Desktop (Interactive dashboard now available)**
* Jupyter Notebook
* Git & GitHub
* Git Large File Storage (LFS)

## Project Structure

This repository is organized to clearly present the different components of the analysis:

* `Amazon_Sales_Analysis.ipynb`: The core Jupyter Notebook containing all Python code for data cleaning, EDA, and interactions with the SQLite database.
* `Amazon Sale Report.csv`: The original raw e-commerce sales dataset. This large file is tracked using Git LFS.
* `amazon_sales.db`: The SQLite database file, which stores the cleaned and processed sales data.
* `README.md`: This comprehensive project documentation.
* `.gitattributes`: Configuration file for Git Large File Storage (LFS) to properly track large files.
* **`PowerBI_Sales_Dashboard/`**: **This folder now contains the interactive Power BI report (`.pbix` file).**

## How to Run/View the Project

To explore this project locally, follow these steps:

### Prerequisites

* Python (3.8+): [Download Python](https://www.python.org/downloads/)
* Jupyter Notebook: Install via `pip install notebook` or through Anaconda.
* Python Libraries: Install required libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn sqlite3
    ```
* **Microsoft Power BI Desktop:** [Download Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Required to view and interact with the `.pbix` dashboard file).

### Steps

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Juribe3271/Amazon-E-commerce-Sales-Analysis-Python-SQL.git](https://github.com/Juribe3271/Amazon-E-commerce-Sales-Analysis-Python-SQL.git)
    cd Amazon-E-commerce-Sales-Analysis-Python-SQL
    ```
2.  **Ensure Git LFS files are downloaded:**
    If you haven't already, install Git LFS and then pull the files:
    ```bash
    git lfs install
    git lfs pull
    ```
3.  **Run the Python Analysis:**
    * Open `Amazon_Sales_Analysis.ipynb` in Jupyter Notebook.
    * Run all cells to perform data cleaning, EDA, and generate the `amazon_sales.db` SQLite database.
4.  **View the Power BI Dashboard:**
    * Navigate to the `PowerBI_Sales_Dashboard/` folder.
    * Open `Amazon_Sales_Dashboard.pbix` using Power BI Desktop to explore the interactive dashboard.

## Key Insights & Findings

* **Sales Trends:** Sales show volatility, with a significant peak in early May, followed by a decline.
* **Customer Focus:** The vast majority (over 99%) of sales revenue is driven by Non-B2B (Consumer) orders.
* **Top Products:** "Kurta" and "Set" are the dominant product categories by order quantity.
* **Geographical Performance:** Maharashtra is the leading state in sales, followed by Karnataka and Telangana.
* **Order Profile:** The average order value is approximately 661 INR, with customers typically purchasing 1 item per order.

## Future Enhancements

* **More Granular Date Analysis:** Explore weekly or monthly sales patterns.
* **Customer Segmentation:** Analyze customer behavior based on purchase frequency, value, and recency.
* **Product Performance Deep Dive:** Identify best-selling individual products, not just categories.
* **Forecasting:** Implement time series forecasting models to predict future sales.

## Contact

Feel free to connect with me for any questions or collaborations:

* **GitHub:** [Your GitHub Profile Link]
* **LinkedIn:** [Your LinkedIn Profile Link]
