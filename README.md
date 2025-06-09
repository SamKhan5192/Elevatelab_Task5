# Elevatelab_Task5
EDA on Titanic Dataset
# Titanic Dataset - Exploratory Data Analysis (EDA)

## Objective
This notebook performs exploratory data analysis on the Titanic dataset to understand the factors that influenced passenger survival.

## Dataset
- Source: Titanic dataset (commonly used for classification tasks)
- Contains 891 rows and 12 columns
- Key columns: `Survived`, `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`

##  Key Steps Performed
1. **Loading Data** – Used `pandas` to read CSV and preview dataset
2. **Missing Value Handling**:
   - Filled missing `Age` values with the mean
   - Filled missing `Embarked` values with the mode
   - `Cabin` column largely missing; was noted but not used in analysis
3. **Univariate Analysis** – Distribution plots for `Age`, `Fare`, and count plots for categorical data
4. **Bivariate Analysis** – Analyzed how survival correlated with:
   - `Sex`: Females survived more
   - `Pclass`: First-class passengers had higher survival rates
5. **Descriptive Statistics** – Summary statistics to understand central tendency and spread

##  Tools Used
- Python 3
- pandas
- matplotlib
- seaborn

##  Insights
- Women and first-class passengers had a significantly higher chance of survival.
- Age and class were important indicators.
- Certain columns had high missing data (`Cabin`) and were not reliable for model building.

