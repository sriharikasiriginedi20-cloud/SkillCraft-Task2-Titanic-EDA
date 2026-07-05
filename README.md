# SkillCraft-Task2-Titanic-EDA
Performed Exploratory Data Analysis (EDA) on the Titanic Passenger Dataset using Google Sheets. Analyzed survival patterns, passenger class distribution, gender distribution, and age trends through statistical summaries, charts, and visualizations. Generated key insights to identify factors influencing passenger survival.

# SkillCraft Technology - Task 02

## Titanic Dataset - Data Cleaning and Exploratory Data Analysis (EDA)

### Project Overview
This project demonstrates the process of performing Data Cleaning and Exploratory Data Analysis (EDA) on the Titanic dataset. The objective is to clean the dataset, handle missing values, explore relationships between variables, and identify patterns and trends that influence passenger survival.

---

## Objective
- Perform data cleaning on the Titanic dataset.
- Handle missing values and remove unnecessary columns.
- Explore the dataset using descriptive statistics.
- Visualize important relationships between variables.
- Identify key factors affecting passenger survival.

---

## Dataset
- **Dataset:** Titanic Dataset
- **Source:** Kaggle Titanic Competition
- **File Used:** `train.csv`

---

## Tools & Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Steps Performed
1. Imported the required libraries.
2. Loaded the Titanic dataset.
3. Explored the dataset using `head()`, `info()`, and `describe()`.
4. Checked for missing values.
5. Filled missing values in the **Age** column using the median.
6. Filled missing values in the **Embarked** column using the mode.
7. Removed the **Cabin** column due to a large number of missing values.
8. Checked for duplicate records.
9. Performed Exploratory Data Analysis (EDA) using visualizations.

---

## Visualizations
- Survival Count
- Survival by Gender
- Survival by Passenger Class
- Age Distribution
- Correlation Heatmap

---

## Key Insights
- Female passengers had a higher survival rate than male passengers.
- First-class passengers were more likely to survive.
- Most passengers were between 20 and 40 years of age.
- Age and Embarked contained missing values that were successfully handled.
- The Cabin column was removed because it contained a large number of missing values.
- The dataset was successfully cleaned and prepared for analysis.

---

## Project Structure

```
SkillCraft-Task2-Titanic-EDA
│
├── Titanic_EDA.ipynb
├── train.csv
├── Titanic_Cleaned.csv
├── README.md
└── screenshots
    ├── 01_Dataset_Preview.png
    ├── 02_Dataset_Info.png
    ├── 03_Missing_Values.png
    ├── 04_Survival_Count.png
    ├── 05_Survival_by_Gender.png
    ├── 06_Survival_by_Passenger_Class.png
    ├── 07_Age_Distribution.png
    └── 08_Correlation_Heatmap.png
```

---

## Outcome
Successfully performed Data Cleaning and Exploratory Data Analysis (EDA) on the Titanic dataset by handling missing values, analyzing data patterns, and creating meaningful visualizations to understand the factors affecting passenger survival.

---

**SkillCraft Technology Internship - Task 02**
