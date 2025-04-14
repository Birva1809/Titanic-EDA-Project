# 🚢 Titanic Dataset – Exploratory Data Analysis
# Project By: [Birva Dave](https://www.linkedin.com/in/birva-dave/)

A clean and structured walkthrough of the Titanic dataset. This mini-project focuses on essential steps like data cleaning, filtering, and visualizations using Python — built with clarity and purpose.

---


## 📂 Dataset

- **Source URL:** [Titanic Dataset (GitHub - Data Science Dojo)](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)
- **Optional Local Use:** (df = pd.read_csv('titanic.csv'))

## 🔍 What’s Covered

### ✅ Data Loading
Imported the dataset using `pandas` directly from the provided URL.

### 🧹 Data Cleaning
- Filled missing values in:
  - `Age` with **median**
  - `Embarked` with **mode**
- Removed duplicate rows.

### 🎯 Filtering
- Extracted and displayed passengers from **First Class** (`Pclass == 1`).

### 📊 Visualizations  
- **Bar Chart** – Survival rate by passenger class  
- **Histogram** – Age distribution with KDE  
- **Scatter Plot** – Age vs Fare *(active by default)*

---

## 🛠️ Libraries Used

- `pandas`
- `matplotlib.pyplot`
- `seaborn`

Install them using:

```bash
pip install pandas matplotlib seaborn
```

## 💡 Final Note

This project provides a concise yet complete exploratory analysis of the Titanic dataset. From data cleaning to visual insights, it demonstrates essential EDA practices using Python. The structure is modular and easy to extend, making it a solid foundation for further statistical analysis or machine learning applications.

