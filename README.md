# Medical Insurance Cost Prediction

This repository contains a comprehensive analysis of medical insurance data to identify the primary factors driving healthcare costs and to predict individual insurance charges using machine learning.

## 📊 Key Findings
- **Smoker Status**: The most significant factor; smokers face substantially higher insurance charges compared to non-smokers (correlation ≈ 0.79).
- **Age & BMI**: Both show a steady positive correlation with costs, indicating that as patients age or their BMI increases, charges generally rise.
- **Regional Trends**: Geographic location showed negligible impact on the total insurance cost in this dataset.
- **Data Integrity**: The dataset was clean with no missing values, allowing for robust statistical modeling.

## 🛠️ Methodology
1. **Exploratory Data Analysis (EDA)**: Visualized data distributions and correlations using Seaborn and Matplotlib.
2. **Data Preprocessing**: Handled categorical variables (sex, smoker, region) using Label Encoding for model compatibility.
3. **Regression Analysis**: Implemented regression models to quantify the relationship between patient attributes and insurance charges.

## 📁 Project Structure
- `Insurance-eda-regression.ipynb`: The complete Jupyter Notebook containing data cleaning, visualizations, and modeling.
- `insurance.csv`: The dataset used for analysis (ensure this is in your input directory).

## 🚀 Getting Started
### Prerequisites
Ensure you have the following libraries installed:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
