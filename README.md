# Titanic Data Preprocessing Project

## Overview
This project demonstrates a complete data preprocessing workflow using the Titanic dataset. It covers data exploration, missing value handling, outlier detection and treatment, feature scaling, encoding, and building a preprocessing pipeline suitable for machine learning.

## Dataset
- **Dataset:** Titanic Dataset
- **Source:** https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv

The dataset contains passenger information such as age, sex, passenger class, fare, embarked port, and survival status.

---

## Objectives

- Perform Exploratory Data Analysis (EDA)
- Handle missing values
- Detect and treat outliers
- Encode categorical features
- Normalize and standardize numerical features
- Build a preprocessing pipeline
- Prepare clean data for machine learning models

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow

### 1. Import Libraries
Required Python libraries are imported for data analysis, visualization, and preprocessing.

### 2. Load Dataset
The Titanic dataset is loaded directly from an online CSV source.

### 3. Exploratory Data Analysis (EDA)
- Display first few rows
- Dataset dimensions
- Data types
- Statistical summary
- Missing value analysis

### 4. Missing Value Imputation
Missing values are handled using appropriate techniques:
- Numerical columns → Mean or Median imputation
- Categorical columns → Most frequent (Mode) imputation

### 5. Outlier Detection
Outliers are identified using:
- Boxplots
- Interquartile Range (IQR) Method

### 6. Outlier Treatment
Detected outliers are treated to reduce their impact on model performance.

### 7. Encoding Categorical Variables
Categorical features are converted into numerical form using suitable encoding methods.

### 8. Feature Scaling

Two scaling techniques are demonstrated:

- **Normalization (Min-Max Scaling)**
- **Standardization (StandardScaler)**

### 9. Preprocessing Pipeline
A Scikit-learn preprocessing pipeline is created to automate:
- Missing value handling
- Encoding
- Feature scaling

---

## Project Structure

```
Titanic_Preprocessing/
│
├── titanic.ipynb        # Jupyter Notebook
├── README.md            # Project Documentation
```

---

## Learning Outcomes

After completing this project, you will understand how to:

- Explore a real-world dataset
- Handle missing values effectively
- Detect and manage outliers
- Encode categorical variables
- Scale numerical features
- Build reusable preprocessing pipelines
- Prepare datasets for machine learning

---

## Future Improvements

- Feature engineering
- Model training
- Model evaluation
- Hyperparameter tuning
- Cross-validation

---

## Author

**Name:** Nija Lathiya

**Course:** Data Science

**Project:** Titanic Data Preprocessing

---

## License

This project is created for educational and academic purposes.
