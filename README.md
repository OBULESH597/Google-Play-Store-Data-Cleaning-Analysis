# 📱 Google Play Store Data Cleaning & Analysis

## 📌 Project Overview

This project focuses on cleaning, preprocessing and analyzing Google Play Store application data using Python.

The project demonstrates a complete data analytics workflow starting from raw data cleaning and progressing toward exploratory data analysis, visualization and dashboard development.

---

## 🎯 Objectives

- Clean raw Google Play Store data
- Handle missing values
- Remove duplicate application records
- Convert columns into appropriate data types
- Standardize numerical values
- Perform feature engineering
- Conduct exploratory data analysis
- Visualize application trends
- Build an interactive analytics dashboard

---

## 📂 Dataset

The dataset contains information about Google Play Store applications.

### Main Columns

- App
- Category
- Rating
- Reviews
- Size
- Installs
- Type
- Price
- Content Rating
- Genres
- Last Updated
- Current Ver
- Android Ver

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Streamlit
- Jupyter Notebook / Google Colab

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

1. Checked dataset structure
2. Identified missing values
3. Identified duplicate records
4. Removed duplicate application records
5. Handled missing ratings
6. Handled missing categorical values
7. Converted Reviews to numeric
8. Converted Installs to numeric
9. Converted Price to numeric
10. Converted application Size into MB
11. Converted Last Updated into datetime
12. Checked invalid values
13. Standardized text fields
14. Created additional analytical features

---

## 🔧 Feature Engineering

### Size_MB

Application sizes were converted into MB for consistent numerical analysis.

### Updated_Year

The year was extracted from the Last Updated column.

### Updated_Month

The month was extracted from the Last Updated column.

---

## 📊 Exploratory Data Analysis

The project includes analysis of:

- App categories
- Rating distribution
- Free vs paid applications
- Application installations
- Reviews
- Application size
- Rating vs reviews
- Correlation between numerical variables

---

## 📈 Visualizations

The project includes:

- Bar charts
- Histograms
- Pie charts
- Scatter plots
- Correlation heatmaps
- Distribution plots

---

## 📱 Interactive Dashboard

A Streamlit dashboard was developed to provide interactive analysis.

### Dashboard Features

- KPI cards
- Category filtering
- Rating analysis
- Installation analysis
- Reviews analysis
- Free vs paid comparison
- Application size analysis
- Interactive data table

---

## 📁 Project Structure

```text
Google-Play-Store-Analysis/
│
├── app.py
├── googleplaystore_cleaned.csv
├── googleplaystore_analysis.ipynb
├── README.md
├── requirements.txt
│
└── screenshots/
    ├── dashboard.png
    ├── category_analysis.png
    └── rating_analysis.png


🚀 How to Run
1. Clone the repository
git clone YOUR_GITHUB_REPOSITORY_URL

2. Install dependencies
pip install pandas numpy matplotlib seaborn plotly streamlit

3. Run the dashboard
streamlit run app.py

💡 Key Learning Outcomes
Through this project, I practiced:
- Data cleaning
- Data preprocessing
- Missing-value treatment
- Duplicate handling
- Data type conversion
- Feature engineering
- Exploratory Data Analysis
- Data visualization
- Dashboard development
- Python-based data analytics
👨‍💻 Author
Obulesu Polisetti
B.Tech Computer Science & Engineering — 2026 Graduate
Skills
Python | Pandas | NumPy | SQL | Excel | Power BI | Data Analysis | Data Visualization
⭐ Project Purpose
This project was created as part of my journey toward becoming a Data Analyst and demonstrates practical experience with Python-based data cleaning, analysis and visualization.

### Suggested GitHub repository name

```text
google-play-store-data-analysis
