# Task 01 — Clean & Prepare a Dataset

## 📌 Project Overview

This project focuses on cleaning and preparing the Titanic passenger dataset for data analysis and machine learning.

The dataset contains passenger information such as survival status, passenger class, age, sex, fare, and embarkation port. The project uses Python, Pandas, NumPy, and Jupyter Notebook to inspect data quality, handle missing values, remove duplicates, validate values, and export the cleaned dataset.

## 📂 Dataset

**Source:** [Seaborn Data — Titanic Dataset](https://github.com/mwaskom/seaborn-data/blob/master/titanic.csv)

The dataset contains passenger characteristics, including:

- Survival status
- Passenger class
- Age and sex
- Fare
- Embarkation port
- Other passenger-related information

## 🎯 Project Objectives

- Load and inspect a real-world dataset.
- Identify and handle missing values.
- Record baseline data quality metrics.
- Remove duplicate records.
- Standardize whitespace and selected text categories.
- Identify invalid ages and negative fares.
- Fill missing numerical values using median values.
- Fill missing embarkation values using the mode.
- Drop the `deck` column due to substantial missingness.
- Convert columns to appropriate data types.
- Generate a before-and-after data quality report.
- Export the cleaned dataset for further analysis and machine learning.

## 🛠️ Technologies Used

- Python 3.14.7
- Jupyter Notebook
- Pandas
- NumPy

## 📋 Requirements

Install the required libraries using:

```bash
python -m pip install pandas numpy
```

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open the project folder in VS Code or Jupyter Notebook.
3. Ensure Python and the required libraries are installed.
4. Open `clean-titanic-dataset.ipynb`.
5. Select the appropriate Python kernel.
6. Run all notebook cells in sequential order.

**Note:** Internet access is required to download the original dataset from its public GitHub URL when running the notebook from the beginning.

## 🧹 Data Cleaning Workflow

1. Load and inspect the dataset.
2. Record initial data quality metrics.
3. Remove exact duplicate records.
4. Standardize selected text values.
5. Handle invalid age and fare values.
6. Fill missing age and fare values with their medians.
7. Fill missing embarkation values with the mode.
8. Remove the `deck` column because of substantial missing data.
9. Handle any remaining missing values.
10. Validate and convert data types.
11. Export the cleaned dataset.
12. Generate a before-and-after quality report.

## 📁 Project Files

| File | Description |
|---|---|
| `clean-titanic-dataset.ipynb` | Jupyter Notebook containing the complete data cleaning workflow |
| `titanic_cleaned.csv` | Cleaned dataset ready for further analysis |
| `data_quality_report.csv` | Before-and-after data quality metrics |
| `README.md` | Project documentation and instructions |

## 📊 Data Quality Report

The project generates `data_quality_report.csv` containing actual before-and-after metrics, including:

- Total rows
- Total columns
- Duplicate rows
- Missing cells
- Integer columns
- Float columns
- Object columns

The report values are calculated by running the notebook. No fixed counts are assumed in advance.

## 📈 Results

The final output is a cleaned Titanic dataset with missing values handled, duplicate records removed, selected invalid values addressed, and data types reviewed.

The before-and-after report helps evaluate changes in data quality during preprocessing.

## 🎓 Learning Outcomes

Through this project, I practiced:

- Data loading and inspection using Pandas.
- Missing-value handling techniques.
- Duplicate detection and removal.
- Data validation and type conversion.
- Exporting processed datasets to CSV.
- Documenting a reproducible data cleaning workflow.

## 👩‍💻 Author

**Wajiha Fareed**

Aspiring AI Engineer | Python | Data Science | Machine Learning

---

*This project was completed as a practical data cleaning and preparation task.*