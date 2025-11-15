# Titanic Data Cleaning & Preprocessing Tool
Automates cleaning of raw datasets by handling missing values, removing duplicates, and detecting outliers using Z-score. Prepares clean, reliable data ready for analysis or machine learning. Built with Pandas and NumPy.


## Project Overview

In real-world datasets, inconsistencies such as missing values, duplicates, and outliers are common and can reduce the accuracy of analysis and machine learning models. This project provides a **Data Cleaning & Preprocessing Tool** that automates key preprocessing steps, ensuring datasets are clean, reliable, and ready for further analysis.

---

## Features

* **Missing Values Handling:** Automatically imputes numeric columns using mean and categorical columns using mode.
* **Duplicate Removal:** Detects and removes duplicate rows.
* **Outlier Detection (Z-Score):** Flags extreme numeric values and removes them to improve model performance.
* **Automated CSV Export:** Saves the cleaned dataset to a CSV file.

---

## 🛠 Libraries Used

* **Pandas** – for data manipulation
* **NumPy** – for numerical operations
* **SciPy** – for Z-score calculation

---



## Google Colab Notebook
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sharmacharvi/Titanic-Data-Cleaning-Preprocessing-Tool/blob/main/Data_Cleaning_%26_Preprocessing_Too.ipynb)

---

## How to Run

1. Upload `titanic_raw.csv` and `data_cleaning.py` to Google Colab or your local environment.
2. Run the preprocessing script or notebook cells.
3. The cleaned dataset will be automatically saved to `output/titanic_cleaned.csv`.

---
## Author

### Charvi Sharma



