# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project explores and analyzes the Titanic dataset using Python. The main goal is to perform data cleaning, detect and remove outliers, and visualize meaningful patterns to understand survival factors.

---

## 📁 Dataset Used
- **Source**: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)
- **File Used**: `train.csv`

---

## 📊 Tasks Completed

### ✅ 1. Data Loading
- Loaded the dataset using `pandas`
- Displayed head, info, and statistical summary

### ✅ 2. Initial Exploration
- Printed column names and data types
- Identified numeric and categorical columns

### ✅ 3. Data Visualization
- Created **boxplots** for `Age`, `Fare`, `SibSp`, and `Parch` to visualize outliers
- Plotted **histograms** and **barplots** to understand distributions

### ✅ 4. Outlier Detection and Removal
- Used **IQR method** to find and remove outliers in:
  - `Fare`
  - `Age`
  - `SibSp`
  - `Parch`
- Boxplots confirmed cleaner data after removal

### ✅ 5. Correlation Analysis
- Created a **correlation heatmap**
- Found:
  - `Fare` positively correlated with survival
  - `Pclass` and `Sex` important predictors (after encoding)

### ✅ 6. Column Understanding
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- Added explanation in analysis

---

## 🔧 Tools & Libraries
- Python
- pandas
- numpy
- seaborn
- matplotlib
- scipy

---

## 📈 Visual Insights
- Many outliers in `Fare`, mostly above 100–200
- Very few outliers in `Age` (older passengers)
- Most people had no family (`SibSp = 0`, `Parch = 0`)
- Females and 1st class passengers had higher survival rates

---

---

## 📬 Contact

I'm always open to feedback, contributions, and collaborations!

- 📧 Email: [mayank.bansal.2805@gmail.com](mayank.bansal.2805@gmail.com)
- 💼 LinkedIn: [Mayank Bansal](https://www.linkedin.com/in/mayankofficialit/)

> Made with ❤️ by [Mayank Bansal](https://github.com/MayankBansal07)
