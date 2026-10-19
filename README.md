# 🚢 Titanic Survival Prediction | Data Analysis & Machine Learning

### Exploring Passenger Survival Patterns Through Python, Data Visualization, and Predictive Analysis

An exploratory data analysis and prediction project based on the famous Titanic dataset. This project uses Python and its data analysis libraries to investigate passenger information, uncover survival patterns, handle missing data, and explore the factors associated with survival during the Titanic disaster.

The project combines data exploration, visualization, preprocessing, and predictive analysis in Jupyter Notebook.

---

## 📌 Table of Contents

- [About the Project](#-about-the-project)
- [Project Objectives](#-project-objectives)
- [Key Features](#-key-features)
- [Exploratory Data Analysis](#-exploratory-data-analysis)
- [Data Cleaning and Preprocessing](#-data-cleaning-and-preprocessing)
- [Technologies Used](#️-technologies-used)
- [Repository Structure](#-repository-structure)
- [Getting Started](#-getting-started)
- [How to Explore the Project](#-how-to-explore-the-project)
- [Key Learning Outcomes](#-key-learning-outcomes)
- [Future Improvements](#-future-improvements)
- [License](#-license)

---

## 📖 About the Project

The sinking of the RMS Titanic in 1912 remains one of the most well-known maritime disasters in history. The passenger dataset provides an opportunity to explore how demographic and travel-related characteristics relate to survival outcomes.

This project analyzes the Titanic dataset using **Python, Pandas, NumPy, Matplotlib, and Seaborn**.

The analysis focuses on understanding passenger demographics, identifying missing values, examining survival patterns, and visualizing relationships between variables such as age, gender, passenger class, family members aboard, and ticket fare.

The repository includes two Jupyter notebooks:

- **Titanic_EDA.ipynb** — focuses on exploratory data analysis, data quality, statistical exploration, and visualizations.
- **Titanic_prediction.ipynb** — provides a separate notebook for exploring the prediction component of the project.

The overall goal is to demonstrate practical data analysis skills and develop a better understanding of how data can be transformed into meaningful insights.

## 🎯 Project Objectives

- Explore and understand the structure of the Titanic dataset.
- Identify missing values and assess data quality.
- Analyze passenger survival patterns across different demographic groups.
- Investigate relationships between passenger class, age, gender, and survival.
- Examine the distributions of age, fare, and family-related variables.
- Apply basic data cleaning and preprocessing techniques.
- Create meaningful visualizations to communicate findings.
- Explore passenger survival prediction using the provided prediction notebook.

## ✨ Key Features

🔍 **Exploratory Data Analysis (EDA)**  
Examine dataset structure, data types, summary statistics, and missing values.

📊 **Data Visualization**  
Use charts and statistical plots to understand passenger distributions and survival patterns.

🧹 **Data Cleaning**  
Handle missing age values using passenger-class-based estimates and remove the Cabin column due to extensive missing data.

👥 **Survival Analysis**  
Compare survival outcomes across gender and passenger classes.

📈 **Distribution Analysis**  
Investigate passenger ages, ticket fares, and the number of siblings or spouses aboard.

🤖 **Prediction Analysis**  
Explore the separate Titanic prediction notebook to understand the predictive component of the project.

📓 **Jupyter Notebook Workflow**  
Keep the analysis organized in interactive notebooks that are easy to explore and reproduce.

## 📊 Exploratory Data Analysis

The analysis investigates several important questions about the Titanic passengers.

| Analysis | Purpose |
|---|---|
| Survival Distribution | Examine the number of passengers who survived and did not survive. |
| Survival by Gender | Compare survival outcomes across genders. |
| Survival by Passenger Class | Investigate differences between first-, second-, and third-class passengers. |
| Age Distribution | Understand the age profile of passengers. |
| Fare Distribution | Examine ticket fare patterns and variations. |
| Family Relationships | Explore the `SibSp` variable representing siblings and spouses aboard. |
| Missing Values Heatmap | Visualize missing data and identify data quality issues. |
| Age vs. Passenger Class | Explore age differences across passenger classes using a box plot. |

These visualizations help identify patterns in the dataset and provide a foundation for further statistical analysis and predictive modeling.

## 🧹 Data Cleaning and Preprocessing

Data cleaning is an important part of the project because missing or incomplete information can affect analysis and interpretation.

### 1. Missing Values Analysis
The dataset is inspected to identify missing observations, particularly in the `Age` and `Cabin` columns.

### 2. Age Imputation
Missing age values are filled using passenger-class-based estimates:

- First Class: 37
- Second Class: 29
- Third Class: 24

These are the estimates documented in the exploratory analysis notebook.

### 3. Cabin Column Removal
The `Cabin` column is removed from the cleaned analysis because it contains a large proportion of missing values.

### 4. Validation After Cleaning
The dataset is checked again to review remaining missing values after preprocessing.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Interactive analysis and experimentation |
| Git & GitHub | Version control and project hosting |

## 📂 Repository Structure

```text
Titanic-Survival-Prediction/
│
├── Titanic_EDA.ipynb
│   └── Exploratory data analysis and visualizations
│
├── Titanic_prediction.ipynb
│   └── Titanic passenger prediction analysis
│
├── titanic_train.csv
│   └── Titanic passenger training dataset
│
├── README.md
│   └── Project documentation
│
└── LICENSE
    └── MIT License
```

## 🚀 Getting Started

Follow these steps to explore the project on your local machine.

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Jupyter Notebook or JupyterLab
- Git (optional, for cloning the repository)

### 1. Clone the Repository

```bash
git clone https://github.com/Umer00/Titanic-Survival-Prediction.git
```

### 2. Navigate to the Project Directory

```bash
cd Titanic-Survival-Prediction
```

### 3. Install the Required Libraries

```bash
python -m pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open a Notebook

Start with `Titanic_EDA.ipynb` to explore the dataset, data cleaning steps, and visualizations.

Then open `Titanic_prediction.ipynb` to examine the prediction-related analysis.

**Note:** Run the notebooks from the project directory so that the CSV dataset can be accessed using the appropriate relative file path.

## 🔎 How to Explore the Project

For the best learning experience, follow this workflow:

1. **Load the dataset** and inspect its dimensions, columns, and data types.
2. **Explore data quality** by identifying missing values and reviewing summary statistics.
3. **Clean the data** using the preprocessing steps demonstrated in the notebook.
4. **Visualize patterns** in passenger age, fare, gender, class, and survival.
5. **Interpret the findings** and consider which features may be useful for predicting survival.
6. **Explore the prediction notebook** to understand the project's predictive analysis.

## 💡 Key Learning Outcomes

This project provides practical experience in:

- Exploratory Data Analysis (EDA)
- Data cleaning and missing value handling
- Descriptive statistics
- Data visualization and interpretation
- Feature exploration
- Working with structured CSV datasets
- Using Pandas and NumPy for data analysis
- Creating visualizations with Matplotlib and Seaborn
- Working with Jupyter Notebook
- Understanding the foundations of predictive analytics

## 🔮 Future Improvements

Potential improvements that could extend the project include:

- Adding a detailed statistical summary of the dataset.
- Comparing survival rates using clearly labeled percentages.
- Exploring relationships between multiple passenger features.
- Applying feature engineering to create additional predictive variables.
- Evaluating classification models using appropriate performance metrics.
- Adding a model comparison chart and confusion matrix, if supported by the prediction workflow.
- Developing an interactive application for passenger survival predictions.

## 📜 License

This project is distributed under the **MIT License**. See the [LICENSE](LICENSE) file for the applicable terms.

## ⭐ Support

If you find this project useful for learning Python, data analysis, or data visualization, consider giving the repository a star!

---

**Made with Python, curiosity, and a passion for data analysis.**
