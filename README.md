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

```bash
git clone [https://github.com/Juribe3271/Amazon-E-commerce-Sales-Analysis-Python-SQL.git](https://github.com/Juribe3271/Amazon-E-commerce-Sales-Analysis-Python-SQL.git)
cd Amazon-E-commerce-Sales-Analysis-Python-SQL
