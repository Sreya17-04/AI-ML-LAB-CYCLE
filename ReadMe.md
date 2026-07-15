# Data Preprocessing using Loan Prediction Dataset

## Experiment 1 – Data Preprocessing


---

## Objective

The objective of this experiment is to perform data preprocessing on the Loan Prediction dataset using Python in Google Colab. Data preprocessing improves the quality of raw data by handling missing values, removing duplicates, detecting and treating outliers, encoding categorical variables, scaling features, and preparing the dataset for machine learning applications.

---

## Dataset

**Dataset Name:** Loan Prediction Dataset

The dataset contains customer information used to predict loan approval status.

### Features

- Loan_ID
- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status

---

## Software Requirements

- Google Colab
- Python 3.x

### Python Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

---

# Preprocessing Tasks Performed

### 1. Dataset Loading
- Loaded the Loan Prediction dataset using the Pandas library.
- Displayed the first few records of the dataset.

### 2. Dataset Inspection
- Displayed the number of rows and columns.
- Checked data types.
- Identified missing values.

### 3. Exploratory Data Inspection
- Displayed:
  - First five records
  - Last five records
  - Randomly selected records

### 4. Missing Value Treatment
- Filled numerical missing values using the median.
- Filled categorical missing values using the mode.

### 5. Duplicate Record Removal
- Checked for duplicate records.
- Removed duplicate rows.

### 6. Outlier Detection
- Detected outliers using the Interquartile Range (IQR) method.
- Visualized outliers using box plots.

### 7. Outlier Handling
- Removed outliers using IQR boundaries.

### 8. Encoding
Implemented:
- Label Encoding
- One-Hot Encoding

### 9. Feature Scaling
Applied:
- Min-Max Normalization
- Standardization (Z-score Scaling)

### 10. Feature Selection
Performed correlation analysis to identify important features.

### 11. Correlation Analysis
Generated:
- Correlation Matrix
- Heatmap

### 12. Feature Engineering
Created a new feature:

**TotalIncome = ApplicantIncome + CoapplicantIncome**

### 13. Data Type Conversion
Converted required columns into appropriate data types.

### 14. Data Cleaning
Handled inconsistent and noisy data.

### 15. Train-Test Split
Split the dataset into:
- Training Dataset
- Testing Dataset

### 16. Data Balancing
Balanced the training dataset using **SMOTE**.

### 17. Data Visualization
Visualized numerical feature distributions before and after preprocessing.

### 18. Dataset Comparison
Compared the original dataset with the preprocessed dataset.

### 19. Save Clean Dataset
Saved the cleaned dataset as:

```
LoanPrediction_Cleaned.csv
```
---

# Results

The preprocessing pipeline successfully:

- Loaded the dataset
- Handled missing values
- Removed duplicate records
- Detected and removed outliers
- Encoded categorical variables
- Scaled numerical features
- Performed feature engineering
- Generated correlation analysis
- Balanced the dataset using SMOTE
- Split the data into training and testing sets
- Saved the cleaned dataset

The resulting dataset is cleaner, more consistent, and suitable for machine learning model development.

---

# Conclusion

The Loan Prediction dataset was successfully preprocessed using Python and Google Colab. Essential preprocessing techniques such as missing value treatment, duplicate removal, outlier handling, encoding, feature scaling, feature engineering, and data balancing were performed. The final cleaned dataset is well-prepared for further machine learning tasks.

---

