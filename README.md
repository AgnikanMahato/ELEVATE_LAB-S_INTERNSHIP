# ELEVATE_LAB-S_INTERNSHIP

## Titanic Data Science Workflow

This notebook demonstrates a complete data preprocessing pipeline for the Titanic dataset using advanced, yet easy-to-understand data science techniques. Below is a summary of each step:

## 1. Import & Explore Data
- Load the Titanic dataset using pandas.
- Display basic information: shape, columns, data types, and missing values.
- Preview the first few rows for initial understanding.

## 2. Handle Missing Values
- Impute missing values in numerical columns (`Age`, `Fare`) using the median for robustness.
- Fill missing categorical values (`Embarked`) with the mode (most frequent value).
- Drop the `Cabin` column due to excessive missing data.

## 3. Encode Categorical Features
- Convert categorical columns (`Sex`, `Embarked`) into numerical format using Label Encoding.
- Drop non-informative columns (`Name`, `Ticket`) to simplify the dataset.

## 4. Normalize Numerical Features
- Standardize numerical columns (`Age`, `Fare`, `SibSp`, `Parch`) using `StandardScaler` for better model performance and comparability.

## 5. Visualize & Remove Outliers
- Use boxplots to visualize outliers in numerical features.
- Apply the Interquartile Range (IQR) method to remove outliers, ensuring cleaner data for analysis.

---

**Result:**  
A clean, well-processed dataset ready for further analysis or machine
