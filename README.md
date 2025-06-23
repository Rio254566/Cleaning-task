# Cleaning-task
Financial Economics Data Cleaning and Preprocessing

This project involves the data cleaning, preprocessing, and exploratory data analysis (EDA) of a financial and economic dataset to prepare it for machine learning models.

Dataset Description

The dataset includes daily stock market metrics and macroeconomic indicators such as:

- Open, Close, High, and Low stock prices
- Trading Volume
- GDP Growth (%)
- Inflation Rate (%)
- Unemployment Rate (%)
- Interest Rate (%)
- Consumer Confidence Index
- Forex USD/EUR, USD/JPY
- Crude Oil and Gold Prices
- Retail Sales and Real Estate Index
- M&A Deals
- VC Funding

  Row = 3000
  columns = 22

  #Task Performed
  Data cleaning
- Checked for missing values
- Imputed missing values using appropriate methods (mean/median)
- Dropped/handled unnecessary or constant columns
- Separated multiple stock indices into separate datasets

  **Encoding**
  Converted categorical features (e.g., `Stock Index`) using **Label Encoding

  **Exploratory Data Analysis (EDA)**
- Visualized distributions using  **boxplots**
- Detected and analyzed outliers

  **Outlier Detection**
- Performed **IQR-based outlier detection** on original data
- Verified using **boxplots**
- Confirmed that the dataset had **no significant outliers**
  

  **Feature Scaling**
- Applied **Standardization (Z-score normalization)** to numerical features
- Prepared the dataset for machine learning models that require scaled input

  Files in This Repository
| File |
|------|-------------|
| `cleaned_finance_data.csv` | Final cleaned and preprocessed dataset |
| `finance_economics_dataset(original).csv` | original dataset |
| `finance_cleaning_notebook.ipynb` | Full Jupyter Notebook with code, plots, and analysis |
| `README.md` | This file |
