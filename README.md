# Titanic Dataset Preparation and Exploratory Data Analysis

## Activity 1: Dataset Preparation

**Subject:** Foundations & Data Preparation  
**Unit:** Unit I  
**Activity:** 1 – Dataset Preparation  
**Dataset:** Titanic Passenger Dataset  
**Programming Language:** Python  
**Platform:** Google Colab  

---

## 1. Introduction

This project focuses on inspecting, cleaning and preparing the Titanic Passenger Dataset for future machine learning applications.

The dataset contains passenger information such as age, gender, passenger class, ticket fare and survival status.

The main objective is to identify data-quality issues, handle missing values, perform exploratory data analysis (EDA), visualize the data and prepare a cleaned dataset.

No prediction model is developed in this activity.

## 2. Objectives

- Load and inspect a tabular dataset.
- Identify numerical and categorical features.
- Detect and handle missing values.
- Check duplicate records and data consistency.
- Perform exploratory data analysis.
- Create meaningful data visualizations.
- Apply one-hot encoding to categorical features.
- Apply standardization to numerical features.
- Export the prepared dataset into CSV format.

## 3. Dataset Information

**Dataset Name:** Titanic Passenger Dataset

**Dataset Source:** Seaborn Open-source Dataset Repository

**Dataset Link:**  
https://raw.githubusercontent.com/mwaskom/seaborn-data/master/titanic.csv

**File Format:** CSV

**Original Dataset Size:** 891 Rows × 15 Columns

### Important Features

| Feature | Description |
|---|---|
| survived | Passenger survival status |
| pclass | Passenger class |
| sex | Passenger gender |
| age | Passenger age |
| sibsp | Siblings/spouses aboard |
| parch | Parents/children aboard |
| fare | Ticket fare |
| embarked | Port of embarkation |

## 4. Tools and Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 5. Methodology

The following steps were performed:

1. Dataset selection and loading.
2. Dataset inspection and structural analysis.
3. Identification of numerical and categorical features.
4. Missing-value detection.
5. Missing-value treatment using median and mode.
6. Duplicate checking and data consistency.
7. Exploratory Data Analysis and visualization.
8. One-hot encoding of categorical features.
9. Standardization of numerical features.
10. Saving the final prepared dataset as a CSV file.

## 6. Data Visualization

The following visualizations are generated:

- Distribution of Passenger Ages (Histogram).
- Survival Count of Titanic Passengers (Count Plot).
- Gender-wise Survival Count (Count Plot).
- Fare Distribution by Passenger Class (Box Plot).

## 7. Data Preprocessing

Missing values in the Age column are handled using median imputation, while missing values in Embarked are handled using mode imputation.

The Deck column is removed because it contains a high proportion of missing values.

Categorical features are converted into numerical representations using One-Hot Encoding.

Numerical features are standardized using StandardScaler.

## 8. Final Output

The final cleaned and transformed dataset is exported as:

`Titanic_Prepared_Dataset.csv`

The prepared dataset can be used for future machine learning applications.

## 9. Conclusion

The Titanic dataset was successfully inspected, cleaned and prepared using Python. Missing values, duplicate records and data-quality issues were examined. Exploratory Data Analysis was performed using statistical methods and visualizations.

Categorical encoding and numerical standardization were applied to prepare the data for future machine learning workflows.

This activity provided practical understanding of data preparation and exploratory data analysis.

---

**Note:** This project is completed as part of Activity 1 – Dataset Preparation. No machine learning prediction model is trained.
