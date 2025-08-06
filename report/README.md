# 📝 Report Folder

This folder contains the Quarto documents used to document and explain each stage of the stroke prediction project.

## 📑 Files

### `EDA for final project.qmd`
This Quarto file performs and documents:

- Initial dataset loading and formatting
- Type conversion of numeric and categorical variables
- Missing data inspection and visualization
- Summary statistics for numeric variables
- Visual exploration of key predictors (e.g., BMI, glucose level)
- Class imbalance check of the target variable (`stroke`)
- Imputation of missing values using:
  - Median imputation for `bmi`
  - A new `"Missing"` level for `smoking_status`
- A final data dictionary summarizing cleaned variables

This file prepares a finalized, clean dataset ready for training a neural network model.

---

### `Modeling_and_PFI.ipynb`
This Jupyter notebook file performs and documents:

- Simple Exploratory Data Analysis using SQL
  - count the number of people who had a stroke and those who did not
  - explore min, max, and average age of participants
- Preprocess the data before modeling
  - One-hot Encoding
  - Scaling (MinMaxScaler)
- Create a function to select the best model among three algorithms based on recall.
  - mitigate class imbalance in the target variable using the SMOTE method
  - Build Artificial Neura Network model, KNN model and Random Forest model
  - Execute three models and create a performance metrics table to compare them
- Permutation Feature Importance (PFI)
  - Create a plot showing the top 3 features that contribute most to stroke prediction.

