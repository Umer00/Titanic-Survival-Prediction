<div align="center">

# 🚢 Titanic EDA

### Exploring the Titanic Dataset Through Data Analysis & Visualization 📊

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge\&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge\&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge\&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</div>

---

## 📌 About the Project

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset using Python.

The main goal is to explore the dataset, identify missing values, analyze passenger survival patterns, and visualize the relationship between survival and different features such as **Gender, Passenger Class, Age, Siblings/Spouses, and Fare**.

The project also includes basic **data cleaning**, where missing Age values are handled based on passenger class and the Cabin column is removed due to a large number of missing values.

---

## 📊 Analysis Performed

### 🔍 Data Exploration

* Loaded and explored the Titanic dataset
* Checked the dataset for missing values
* Visualized missing data using a heatmap

### 👥 Survival Analysis

* Analyzed the number of passengers who survived and did not survive
* Compared survival based on **Gender**
* Compared survival based on **Passenger Class**

### 📈 Data Visualization

* Age distribution analysis
* Passenger age histogram
* Distribution of siblings/spouses (`SibSp`)
* Fare distribution analysis

### 🧹 Data Cleaning

* Examined the relationship between **Passenger Class and Age**
* Filled missing Age values using class-based age estimates
* Dropped the `Cabin` column
* Checked missing values again after cleaning

---

## 📉 Visualizations Included

📌 Missing Values Heatmap
📌 Survival Count Plot
📌 Survival by Gender
📌 Survival by Passenger Class
📌 Age Distribution
📌 Age Histogram
📌 Siblings/Spouses Count Plot
📌 Fare Distribution
📌 Passenger Class vs Age Box Plot

---

## 🛠️ Technologies Used

| Technology          | Purpose                        |
| ------------------- | ------------------------------ |
| 🐍 Python           | Programming Language           |
| 🐼 Pandas           | Data Manipulation & Analysis   |
| 🔢 NumPy            | Numerical Operations           |
| 📊 Matplotlib       | Data Visualization             |
| 🌊 Seaborn          | Statistical Data Visualization |
| 📓 Jupyter Notebook | Project Development            |

---

## 🧹 Data Cleaning Approach

The dataset contained missing values, mainly in the **Age** and **Cabin** columns.

### Age

Missing Age values were filled according to the passenger's class:

* 🥇 **1st Class → 37**
* 🥈 **2nd Class → 29**
* 🥉 **3rd Class → 24**

### Cabin

The `Cabin` column was removed because it contained a large number of missing values.

After cleaning, the dataset was checked again to identify the remaining missing values.

---

## 📂 Project Structure

```text
Titanic_EDA/
│
├── Titanic_EDA.ipynb
├── titanic_train.csv
└── README.md
```

---

## 🎯 Project Objective

The purpose of this project is to practice and strengthen skills in:

* Exploratory Data Analysis
* Data Cleaning
* Handling Missing Values
* Data Visualization
* Understanding Data Distributions
* Analyzing Relationships Between Variables
* Using Pandas and Seaborn

---

## 🚀 Key Areas Explored

```text
Titanic Dataset
      │
      ├── 🔍 Missing Values Analysis
      │
      ├── 👥 Survival Analysis
      │     ├── By Gender
      │     └── By Passenger Class
      │
      ├── 📊 Distribution Analysis
      │     ├── Age
      │     ├── SibSp
      │     └── Fare
      │
      └── 🧹 Data Cleaning
            ├── Age Imputation
            └── Cabin Removal
```

---

## 📚 What I Practiced

> **Explore → Visualize → Clean → Understand**

This project helped me practice using Python libraries to inspect a dataset, identify data quality issues, create meaningful visualizations, and perform basic data cleaning.

---

<div align="center">

### ⭐ If you found this project interesting, consider giving it a Star!

**Made with ❤️ by Umer Farooq**

</div>
