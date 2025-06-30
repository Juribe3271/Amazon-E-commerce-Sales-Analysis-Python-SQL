# Amazon E-commerce Sales Analysis: Python, SQL & Power BI

This project performs a comprehensive analysis of Amazon e-commerce sales data, utilizing Python for data cleaning and exploratory data analysis (EDA), SQL (SQLite) for efficient data storage and querying, and Power BI for creating an interactive sales dashboard to visualize key insights.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [How to Run/View the Project](#how-to-runview-the-project)
- [Key Insights & Findings](#key-insights--findings)
- [Future Enhancements](#future-enhancements)
- [Contact](#contact)

## Project Overview

This data analysis project focuses on understanding sales trends, product performance, and geographical insights from a dataset of Amazon e-commerce sales. The goal is to transform raw data into actionable insights, demonstrating proficiency in the end-to-end data analysis pipeline from data cleaning to interactive visualization.

## Features

* **Data Acquisition & Cleaning:** Demonstrated proficiency in Python (Pandas) for importing raw CSV data (`Amazon Sale Report.csv`), handling missing values, correcting data types, and preparing data for analysis.
* **Exploratory Data Analysis (EDA):** Performed in-depth analysis using Python (Matplotlib, Seaborn) to uncover sales trends, identify top-selling products/categories, analyze sales by demographics (gender, state), and understand order fulfillment patterns.
* **Database Management:** Utilized SQLite to efficiently store the cleaned and transformed data (`amazon_sales.db`), showcasing abilities in relational database creation and data insertion using Python's `sqlite3` module.
* **Interactive Data Visualization:** Developed an interactive Power BI dashboard to present key sales metrics and insights, enabling dynamic exploration of the data. (This will be added in a future commit).
* **Version Control:** Managed project versions and hosted the repository using Git and GitHub, including handling large files with Git LFS.

## Technologies Used

* **Python:** Pandas, NumPy, Matplotlib, Seaborn, SQLite3
* **SQL:** SQLite
* **Microsoft Power BI Desktop** (For interactive dashboard - to be added)
* **Jupyter Notebook**
* **Git & GitHub**
* **Git Large File Storage (LFS)**

## Project Structure

This repository is organized to clearly present the different components of the analysis:

* `Amazon_Sales_Analysis.ipynb`: The core Jupyter Notebook containing all Python code for data cleaning, EDA, and interactions with the SQLite database.
* `Amazon Sale Report.csv`: The original raw e-commerce sales dataset. This large file is tracked using Git LFS.
* `amazon_sales.db`: The SQLite database file, which stores the cleaned and processed sales data.
* `README.md`: This comprehensive project documentation.
* `.gitattributes`: Configuration file for Git Large File Storage (LFS) to properly track large files.
* `PowerBI_Sales_Dashboard/`: (This folder will contain the Power BI report (`.pbix` file) and any related assets once created and added.)

## How to Run/View the Project

To explore this project locally, follow these steps:

### Prerequisites

* **Python (3.8+):** [Download Python](https://www.python.org/downloads/)
* **Jupyter Notebook:** Install via `pip install notebook` or through Anaconda.
* **Python Libraries:** Install required libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
* **Microsoft Power BI Desktop:** [Download Power BI Desktop](https://powerbi.microsoft.com/desktop/)
* **Git:** [Download Git](https://git-scm.com/downloads) (ensure Git LFS is also installed: `git lfs install`)
* **SQLite ODBC Driver:** (Needed for Power BI to connect to SQLite) Download and install the appropriate `sqliteodbc_x64.exe` (for 64-bit Windows) or `sqliteodbc.exe` (for 32-bit Windows) from [http://www.ch-werner.de/sqliteodbc/](http://www.ch-werner.de/sqliteodbc/).

### Cloning the Repository


## Key Insights & Findings

Based on the comprehensive analysis of the Amazon E-commerce Sales data:

* **Sales Volatility:** The daily total sales amount shows significant fluctuations throughout the observed period (April-June 2022), indicating a dynamic sales environment.
* **Early May Sales Peak:** A distinct and sharp peak in daily sales was observed around **early May 2022**, representing the highest sales figures within the dataset. Further investigation could determine if this was driven by specific promotions or seasonal factors.
* **Late June Sales Decline:** Following the early May peak, there was a general downward trend in daily sales towards the end of June 2022, with daily volumes lower than those seen in April and the beginning of May.
* **Dominant Product Categories:** "Kurta" and "Set" emerged as consistently top-performing product categories by number of orders across major sales regions like Maharashtra, Karnataka, and Telangana.
* **Consumer-Driven Sales:** The vast majority of sales revenue (approximately 49.96 million INR) comes from **Non-B2B (Consumer) orders**, with Business-to-Business (B2B) sales being negligible (around 36,374 INR). This indicates that the platform is primarily used for direct consumer purchases.
* **Average Order Profile:** The average order value is **661.48 INR**, and customers typically purchase **1.07 items per order**, suggesting that most transactions involve a single item.
* **Top Performing States:** **Maharashtra** is the highest-contributing state by sales amount (over 8.7 million INR), followed by **Karnataka** and **Telangana**. These states represent the primary geographical markets for sales.
* **Sales by Day of Week:** Sales figures are relatively consistent across all days of the week, with **Sunday** showing the highest total sales amount. This implies consistent demand throughout the week with a slight weekend bump.

```bash
git clone [https://github.com/Juribe3271/Amazon-E-commerce-Sales-Analysis-Python-SQL.git](https://github.com/Juribe3271/Amazon-E-commerce-Sales-Analysis-Python-SQL.git)
cd Amazon-E-commerce-Sales-Analysis-Python-SQL


