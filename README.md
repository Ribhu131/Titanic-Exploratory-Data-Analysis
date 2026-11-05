# 🚢 Titanic Exploratory Data Analysis (EDA)


<p align="center">
  Exploring passenger demographics, survival patterns, and insights from the Titanic dataset using Python.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas" alt="Pandas">
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-11557C" alt="Matplotlib">
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4C72B0" alt="Seaborn">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter" alt="Jupyter">
</p>

---

## 📌 Project Overview

This project explores the famous Titanic passenger dataset through exploratory data analysis (EDA).

The objective is to understand the dataset, identify missing values, analyze passenger demographics, and uncover patterns associated with survival.

## 🎯 Objectives

- Understand the structure and characteristics of the dataset.
- Perform data inspection and statistical analysis.
- Identify missing values and duplicate records.
- Explore passenger demographics and travel characteristics.
- Visualize distributions and relationships between variables.
- Investigate factors associated with passenger survival.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Interactive analysis |

## 📂 Project Structure

```text
Titanic-Exploratory-Data-Analysis/
│
├── assets/
│   └── titanic-banner.png
│
├── Titanic dataset.csv
├── EDA.ipynb
└── README.md
```

## 📊 Dataset Description

The dataset contains passenger information from the Titanic, including demographic details, ticket information, and survival status.

| Feature | Description |
|---|---|
| `PassengerId` | Unique passenger identifier |
| `Survived` | Survival status (0 = No, 1 = Yes) |
| `Pclass` | Passenger class (1st, 2nd, or 3rd) |
| `Name` | Passenger name |
| `Sex` | Passenger sex |
| `Age` | Passenger age |
| `SibSp` | Number of siblings or spouses aboard |
| `Parch` | Number of parents or children aboard |
| `Ticket` | Ticket number |
| `Fare` | Passenger fare |
| `Cabin` | Cabin number |
| `Embarked` | Port of embarkation |

## 🔍 Analysis Workflow

1. **Data Loading** — Import the dataset using Pandas.
2. **Data Inspection** — Examine rows, columns, data types, and dataset dimensions.
3. **Statistical Analysis** — Generate descriptive statistics.
4. **Data Quality Checks** — Identify missing values and duplicates.
5. **Univariate Analysis** — Explore individual feature distributions.
6. **Data Visualization** — Visualize relationships and patterns.
7. **Survival Analysis** — Investigate survival across passenger groups.

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or later
- Jupyter Notebook
- Git

### Installation

Clone the repository:

```bash
git clone https://github.com/Ribhu131/Titanic-Exploratory-Data-Analysis.git
```

Navigate to the project directory:

```bash
cd Titanic-Exploratory-Data-Analysis
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Launch the notebook:

```bash
jupyter notebook EDA.ipynb
```

Run the notebook cells sequentially to reproduce the analysis.

## 💡 Key Questions Explored

- What percentage of passengers survived?
- How did survival vary by gender and passenger class?
- What was the age distribution of passengers?
- How did ticket fares differ across passenger classes?
- Which passenger characteristics were associated with survival?

## 🔮 Future Improvements

- Handle missing values using appropriate imputation techniques.
- Perform deeper survival analysis.
- Engineer features such as family size and passenger titles.
- Detect and investigate outliers.
- Build and evaluate machine learning models to predict survival.

## 👨‍💻 Author

**Ribhu Bose**

- GitHub: [@Ribhu131](https://github.com/Ribhu131)
- Repository: [Titanic Exploratory Data Analysis](https://github.com/Ribhu131/Titanic-Exploratory-Data-Analysis)

---

<p align="center">
  ⭐ If you find this project interesting, consider giving it a star!
</p>
