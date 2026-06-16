# 📊 Stock Price Analysis – Data Analytics Project

## 📌 Codveda Technology Internship – Level 1 (Task 1 & Task 2)

This project is part of the **Codveda Data Analytics Internship Program**.  
It covers **Level 1 Task 1 (Data Cleaning)** and **Task 2 (Exploratory Data Analysis)** using a large real-world stock market dataset.

---

# 🚀 Project Overview

The dataset contains historical stock price data for **505 companies** with approximately **497,000+ records**.

Each record includes:
- Stock symbol
- Date
- Open price
- High price
- Low price
- Close price
- Volume

The objective is to clean the dataset and perform exploratory analysis to extract meaningful financial insights.

---

# 📂 Dataset Information

- **Total Rows:** ~497,000  
- **Total Companies:** 505  
- **Time Period:** Multi-year historical stock data  
- **Features:** OHLC (Open, High, Low, Close), Volume  

---

# 🛠️ Tools & Technologies

- Python 🐍  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

# 🧹 TASK 1: DATA CLEANING & PREPROCESSING

## 📌 Objectives:
- Load and inspect dataset
- Handle missing values
- Remove duplicate records
- Convert data types
- Ensure data consistency

## 📊 Key Steps Performed:
- Loaded dataset using pandas
- Checked missing values (none found)
- Verified duplicate rows (none found)
- Converted `date` column to datetime format
- Standardized dataset structure

## ✅ Outcome:
- Clean dataset ready for analysis
- No missing or duplicate values
- Proper datetime formatting applied

---

# 📊 TASK 2: EXPLORATORY DATA ANALYSIS (EDA)

## 📌 Objectives:
- Understand data distribution
- Identify trends and patterns
- Analyze stock behavior
- Detect correlations
- Generate insights

---

## 📈 Analysis Performed:

### 1. Summary Statistics
- Mean, median, standard deviation of stock prices and volume

### 2. Market Overview
- Number of companies analyzed: **505**
- Date range covered: full dataset period

### 3. Top Stock Analysis
- Most traded stocks by volume
- Highest average stock prices

### 4. Feature Engineering
- Calculated daily returns
- Measured stock volatility

### 5. Single Stock Analysis (AAPL)
- Time series trend analysis
- Moving average (20-day) smoothing

### 6. Correlation Analysis
- Strong correlation between OHLC variables

---

# 📊 Key Visualizations

The project includes:
- Stock price distribution (histogram)
- Outlier detection (boxplot)
- Correlation heatmap
- Time series analysis (AAPL)
- Moving average trend visualization

---

# 📌 Key Insights

- Dataset includes **505 companies with ~497K records**
- No missing or duplicate values detected
- Strong correlation exists between OHLC stock features
- Trading volume varies significantly across companies
- Some stocks show high volatility (high risk profiles)
- AAPL demonstrates a stable long-term upward trend
- Moving average confirms consistent market direction

---

# 📁 Project Structure
    stock-price-analysis/
     │
     ├── data/
     │ └── raw/
     │   └── stock_prices.csv
     │ └── processed
     ├── notebooks/
     │ └── 02_eda.ipynb
     │ └──01_data_cleaning
     ├── README.md
     ├── requirements.txt
     └── .gitignore
 

---

# ⚙️ Installation & Setup

```bash
# Clone repository
git clone https://github.com/your-username/stock-price-analysis.git

# Navigate to project folder
cd stock-price-analysis

# Install dependencies
pip install -r requirements.txt
```

---
##📦 Requirements
pandas
matplotlib
seaborn
numpy
---

##📌 How to Run

- Open Jupyter Notebook
-Navigate to notebooks/02_eda.ipynb
-Run all cells sequentially

🎯 Learning Outcomes
- Data cleaning & preprocessing
- Exploratory data analysis (EDA)
- Feature engineering (returns & volatility)
- Financial data interpretation
- Data visualization techniques

---
##👨‍💻 Author

- Codveda Technology Internship Project
- Domain: Data Analytics
- Level: 1 (Task 1 & Task 2 Completed)

---
##📢 Acknowledgement

- This project was completed as part of the Codveda Technology Internship Program.
