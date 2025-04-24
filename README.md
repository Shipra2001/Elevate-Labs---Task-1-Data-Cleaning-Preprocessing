# Elevate-Labs---Task-1-Data-Cleaning-Preprocessing
A Jupyter Notebook demonstrating data cleaning, outlier handling, and feature engineering for the Titanic dataset. Includes visualization (Matplotlib/Seaborn) and correlation analysis. Ready for machine learning pipelines.

# Titanic Dataset: Data Cleaning & Preprocessing

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

## 📌 Task Overview
This repository contains my solution for **Task 1: Data Cleaning & Preprocessing** using the Titanic dataset. The goal was to prepare raw data for machine learning by handling missing values, encoding categorical features, and scaling numerical data.

## 🛠️ What's Included
- `titanic_cleaning.ipynb`: Jupyter Notebook with complete code
- `titanic.csv`: Raw dataset (automatically downloaded in notebook)
- `cleaned_titanic.csv`: Processed output file
- `screenshots/`: Visualization outputs (boxplots, heatmaps)

## 🔍 Key Steps Performed
1. **Data Exploration**: Identified missing values and data types
2. **Feature Engineering**:
   - Extracted titles from names (Mr/Mrs/Miss)
   - Created family size feature
3. **Data Cleaning**:
   - Handled outliers using IQR method
   - Scaled numerical features with `StandardScaler`
4. **Visualization**:
   - Boxplots for outlier detection
   - Correlation heatmap analysis

##Screenshot 
![image](https://github.com/user-attachments/assets/dce7aa76-96bc-4657-a0d1-7bc3898d0b7d)
![image](https://github.com/user-attachments/assets/60edf5cc-d5a1-4a45-a5b5-0e2a95a1382c)

## 🚀 How to Run
```bash
git clone https://github.com/your-username/titanic-data-cleaning.git
cd titanic-data-cleaning
jupyter notebook titanic_cleaning.ipynb
