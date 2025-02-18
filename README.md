## Project Overview
This project focuses on data cleaning, exploratory data analysis (EDA), and feature engineering for a real estate dataset. The dataset has been processed to handle missing values, outliers, and inconsistencies, followed by feature extraction and transformation for predictive modeling.

## Repository Structure
- **README.md** – Project documentation  
- **5243_raw_data.csv** – Raw data before cleaning  
- **5243_cleaned_data.csv** – Cleaned data  
- **5243_knn2_data.csv** – Cleaned data using KNN2 (used in feature engineering and part of EDA)  
- **Project1_Code_file.ipynb** – Jupyter Notebook containing all three steps (cleaning, EDA, feature engineering)  
- **Project1_report.pdf** – Final project report (PDF format)  
- **Project1_report.qmd** – Final project report (Quarto format)  

## How to Run

1. Clone the Repository
```{python} 
git clone https://github.com/mingyan-xu/STAT5243-Project1.git  
cd STAT5243-Project1
```

2. Run Python file
```{python} 
jupyter notebook notebooks/5243_CodeFile.ipynb
```


## Key Features
- Data Cleaning: Standardizes area and price units, handles missing values, and removes duplicates.  
- EDA: Analyzes property pricing trends, categorical distributions, and correlations.  
- Feature Engineering: Creates derived features and applies TF-IDF for text analysis.  
- Outlier Handling: Uses Z-score and IQR filtering to remove extreme values.

## Group Distribution
**Yi Lu**: Data Cleaning and Handling Inconsistencies
**Shenghong Wu**: Exploratory Data Analysis
**Jiaheng Zhang**: Data Preprocessing and Feature Engineering
**Mingyan Xu**: Report Wrting


