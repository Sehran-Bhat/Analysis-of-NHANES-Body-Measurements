# Analysis-of-NHANES-Body-Measurements



## 🔹 Project Overview

This project analyzes **NHANES (National Health and Nutrition Examination Survey)** body measurement data for adult males and females. The goal is to explore patterns in physical health metrics such as **height, weight, and BMI**, and highlight differences between genders using data analysis and visualization techniques.

---

## 🔹 Datasets

1. **`nhanes_adult_male_bmx_2020.csv`** – Contains body measurement data for adult males.
2. **`nhanes_adult_female_bmx_2020.csv`** – Contains body measurement data for adult females.

**Key Columns:**

* `Height` (in cm)
* `Weight` (in kg)
* `BMI` (calculated)
* `Age` (years)
* Other health-related attributes

---

## 🔹 Objectives

* Perform **data cleaning and preprocessing** for both datasets.
* Compare **male vs female body metrics** such as height, weight, and BMI.
* Conduct **statistical analysis** to identify significant differences.
* Use **visualizations** to highlight distributions and trends.

---

## 🔹 Steps & Methodology

1. **Data Preprocessing**

   * Handle missing values
   * Standardize units where necessary
   * Merge datasets for comparative analysis

2. **Exploratory Data Analysis (EDA)**

   * Descriptive statistics (mean, median, variance)
   * Gender-based comparisons (male vs female)
   * Correlation analysis between height, weight, and BMI

3. **Visualization**

   * Histograms and boxplots for height, weight, BMI
   * Bar charts for age-group comparisons
   * Scatterplots showing relationships between body metrics

---

## 🔹 Tools & Technologies

* **Languages:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

---

## 🔹 Results & Insights

* **Height & Weight Distributions:** Males generally had higher average height and weight than females.
* **BMI Trends:** BMI varied across genders, with distinct distribution patterns.
* **Age Impact:** Differences in body metrics became more pronounced across age groups.

---

## 🔹 Future Scope

* Extend analysis to include **ethnicity, lifestyle, and diet-related factors**.
* Perform **hypothesis testing** to validate statistical significance.
* Apply **predictive modeling** to estimate BMI or health risk based on demographic attributes.

---

## 🔹 How to Run

1. Clone the repository:

   ```bash
   git clone <repo_url>
   cd nhanes-body-measurement-analysis
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the Jupyter Notebook:

   ```bash
   jupyter notebook Analysis_of_NHANES_body_measurement.ipynb
   ```

---
