# 📉 Customer Churn Analysis

An end-to-end customer churn analysis project that combines SQL and Python to explore customer data, identify churn patterns, and surface key drivers behind customer attrition.

## 📌 Overview

This project analyzes customer churn data to understand **why customers leave** and **what factors are most associated with churn**. The workflow moves raw data through a SQLite database and into a Jupyter notebook for exploratory data analysis (EDA) and insight generation.

## 📂 Project Structure

churn_analysis/

├── churn_analysis.ipynb # Main notebook: data loading, EDA, and analysis

├── customer_churn_data_raw.xlsx # Original raw dataset

├── test_database.sqlite # SQLite database used for querying the data

├── exported_churn_data.csv # Cleaned/queried data exported for analysis

└── README.md


## 🧠 Workflow

1. **Raw Data** – `customer_churn_data_raw.xlsx` contains the original, unprocessed customer churn dataset.
2. **Database Loading** – The raw data is loaded into `test_database.sqlite`, enabling SQL-based querying and filtering.
3. **Data Extraction** – Relevant/cleaned data is queried from the database and exported as `exported_churn_data.csv`.
4. **Analysis** – `churn_analysis.ipynb` uses the exported data to perform exploratory data analysis, uncover churn patterns, and visualize key trends.

## 🔍 What the Analysis Covers

- Overall churn rate across the customer base
- Customer segmentation by demographics, tenure, or usage behavior
- Key factors correlated with churn (e.g., contract type, charges, service usage)
- Visual breakdowns of churned vs. retained customers
- Data cleaning and transformation using SQL and pandas

## 🛠️ Tech Stack

- **Python** – pandas, numpy for data manipulation
- **SQLite** – storing and querying the customer dataset
- **Jupyter Notebook** – analysis and visualization
- **Matplotlib / Seaborn** *(if used)* – data visualization
- **Excel** – source data format

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/HimanshuSharmaa007/churn_analysis.git
cd churn_analysis
```

### 2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn jupyter openpyxl
```

### 3. Run the notebook
```bash
jupyter notebook churn_analysis.ipynb
```

The notebook connects to `test_database.sqlite` (and/or reads `exported_churn_data.csv`) to reproduce the full analysis.

## 📊 Key Insights
*(Add a short summary of your top 3–5 findings here once analysis is finalized — e.g. which customer segment churns the most, top churn drivers, retention recommendations.)*

## 🔮 Future Improvements

- Build a predictive churn model (Logistic Regression / Random Forest / XGBoost)
- Add a Power BI or Tableau dashboard for interactive churn visualization
- Automate the Excel → SQLite → CSV pipeline with a script
- Add a `requirements.txt` for easier environment setup

## 🤝 Contributing

Suggestions and improvements are welcome — feel free to open an issue or fork the repo.

## 👤 Author

**Himanshu Sharma**
GitHub: [@HimanshuSharmaa007](https://github.com/HimanshuSharmaa007)
