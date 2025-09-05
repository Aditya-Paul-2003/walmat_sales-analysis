# Walmart Data Analysis: SQL + Python End-to-End Project

## 📌 Project Overview

This project demonstrates a complete **data analysis workflow** on Walmart sales data using **SQL** and **Python**.  
The aim is to extract **business insights** through:

- **Python** → Data cleaning, preprocessing, feature engineering  
- **SQL** → Advanced queries to solve business questions  
- **Pipeline** → Transforming raw data into insights  

The project is ideal for practicing **SQL querying, data manipulation, and analytics storytelling**.



## 🔑 Project Workflow

### 1. Environment Setup
- **Tools Used**: VS Code, Python, MySQL  
- **Objective**: Create a structured workspace for smooth development.

### 2. Data Acquisition
- **Source**: [Walmart Sales Dataset (Kaggle)](https://www.kaggle.com/najir0123/walmart-10k-sales-datasets)  
- **Method**: Download using Kaggle API and store under `data/` folder.

### 3. Install Libraries
```bash
pip install pandas numpy sqlalchemy mysql-connector-python
```



## 4. Data Exploration
- Used `.head()`, `.info()`, `.describe()` to understand structure.  
- Checked column data types, ranges, and potential anomalies.  



## 5. Data Cleaning
- Removed duplicate records.  
- Handled missing values.  
- Converted column types (e.g., dates → datetime, prices → float).  
- Standardized currency fields and categories.  



## 6. Feature Engineering
- Added new column: **Total Amount = unit_price × quantity**.  
- Prepared dataset for advanced SQL queries.  



## 7. Database Integration
- Established **MySQL** connection via **SQLAlchemy**.  
- Created tables and inserted cleaned data.  
- Verified successful load with initial SQL queries.  



## 8. SQL Analysis
Solved business questions such as:  
- Revenue trends by branch and category  
- Best-selling products  
- Customer payment preferences  
- Peak sales times (daily/weekly/monthly)  
- Profit margin distribution  



## 9. Documentation & Publishing
- Documented queries and insights clearly.  
- Hosted project on GitHub with scripts, queries, and documentation.  



## ⚙️ Requirements
- **Python**: 3.8+  
- **Database**: MySQL  
- **Libraries**:  
  - `pandas`, `numpy`, `sqlalchemy`, `mysql-connector-python`  
- **Kaggle API Key** (for dataset download)  


## 📂 Project Structure
```plaintext
Walmart-Analysis/
│-- data/                # Raw & cleaned datasets
│-- sql_queries/         # SQL scripts for analysis
│-- notebooks/           # Python notebooks for cleaning & EDA
│-- main.py              # End-to-end pipeline script
│-- requirements.txt     # Python dependencies
│-- README.md            # Project documentation
```

##  📊 Results & Insights

- **Sales:** Electronics & Food categories dominate revenue.
- **Branch Performance:** Certain locations consistently outperform others.
- **Customer Behavior:** Evening hours see peak shopping; digital payments are most common.
- **Profitability:** Some product categories yield higher margins, critical for promotions.

## 🚀 Future Enhancements
- Build interactive dashboards with Power BI or Tableau.
- Automate real-time data ingestion pipeline.
- Enrich dataset with external factors.

## 🙌 Acknowledgments
- Dataset Source: Kaggle Walmart Sales Dataset
- Inspired by real-world retail analytics and Walmart case studies.
