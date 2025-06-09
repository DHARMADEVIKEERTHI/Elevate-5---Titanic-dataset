# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This repository contains the Exploratory Data Analysis (EDA) for the Titanic dataset as part of **Task 5** of the **Data Analyst Internship**.

---

## 📌 Task Objective

To extract meaningful insights and identify patterns from the Titanic dataset using visual and statistical exploration.

---

## 🛠 Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Key Steps Performed

1. **Data Loading and Overview**
   - Used `pandas` to load `train.csv`
   - Displayed basic info, summary stats, and null value counts
     
2. **Data Cleaning**
   - Drop missing values in Age and Embarked
   - Dropped Cabin due to excessive nulls

3. **Univariate Analysis**
   - Plotted distributions of Age, Fare, Pclass, and Sex
   - Observed skewness and class imbalance

4. **Bivariate Analysis**
   - Compared survival by Gender and Pclass
   - Used bar plots and count plots

5. **Multivariate Analysis**
   - Created correlation heatmap and pairplot
   - Focused on Age, Pclass, Fare, and Survived

6. **Summary of Findings**
   - Included insights from each plot and a final summary

---

## 📈 Summary of Findings

- Women and passengers in 1st class had higher survival rates.
- Higher fare correlated with increased survival chances.
- Younger passengers were more likely to survive.
- Family-related variables (SibSp, Parch) showed positive correlation with Fare.

---

## 📁 Files Included

- `Titanic_EDA.ipynb` - Jupyter Notebook with full code and analysis
- `Titanic_EDA_Report.pdf` - PDF version of the notebook with visual insights
- `train.csv` - Dataset used
- `README.md` - Task summary and instructions
