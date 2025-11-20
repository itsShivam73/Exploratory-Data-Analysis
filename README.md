# 🚢 Titanic Dataset – Exploratory Data Analysis (EDA)

This project performs a complete **Exploratory Data Analysis (EDA)** on the Titanic dataset.  
The goal is to clean the data, understand important patterns, handle missing values, and visualize meaningful trends such as survival rate, passenger demographics, and class distribution.

---

## 📌 Project Overview

In this notebook, I explored the following:

- Data loading and basic inspection  
- Handling missing values (`Age`, `Fare`, `Cabin`)  
- Changing data types to optimize memory  
- Removing duplicate records  
- Univariate, bivariate and multivariate analysis  
- Visualizing key trends using `Matplotlib` and `Seaborn`

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook / Google Colab**

---

## 📂 Dataset Information

The dataset contains the following columns:

- PassengerId  
- Survived  
- Pclass  
- Name  
- Sex  
- Age  
- SibSp  
- Parch  
- Ticket  
- Fare  
- Cabin  
- Embarked  

Total rows: **418**

---

## 🔧 Data Cleaning Steps

- Filled missing `Age` values with mean  
- Filled missing `Fare` values  
- Converted `Age` to `int64`  
- Checked and removed duplicate values  
- Created additional features such as **family size**

---

## 📊 Visualizations Included

- Pie chart: Survived vs Not Survived  
- Count plots:  
  - Passenger class distribution  
  - Gender distribution  
  - Embarkation port  
- KDE plot for Fare distribution  
- Crosstab-based bar charts:  
  - Class vs Survival  
  - Embarked vs Survival  
  - Sex vs Survival  

---

## 🧠 Key Insights

- Around **36.4% passengers survived**.  
- **Pclass 3** had the highest number of passengers.  
- More males (266) than females (152) were onboard.  
- Most people traveled alone (family size = 0).  
- Majority embarked from **Southampton**.  
- High survival among females compared to males.

---



