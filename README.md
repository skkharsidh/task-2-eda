# task-2-eda
# Task 2: Exploratory Data Analysis (EDA)

## Objective
Understand the Titanic dataset using statistics and visualizations.

## Tools Used
Python, Pandas, Matplotlib, Seaborn, Plotly (Google Colab)

## Steps Performed
1. **Summary statistics:** used `describe()` for numeric and text columns.
2. **Histograms:** checked the shape of Age and Fare.
3. **Boxplots:** checked outliers in Age, Fare, SibSp and Parch.
4. **Correlation heatmap:** checked how columns relate to each other.
5. **Pairplot:** compared Survived, Pclass, Age and Fare.
6. **Bar charts and Plotly:** checked survival by Sex, Pclass and Age.

## Key Findings
- About 38% of passengers survived.
- About 74% of women survived, but only about 19% of men.
- 1st class passengers survived more than 3rd class passengers.
- Young children (about 0 to 4 years) mostly survived.
- Fare is skewed: the mean (32.2) is much higher than the median (14.45), because a few people paid a very high price.
- Pclass and Fare have a strong negative correlation (-0.55), which is an example of multicollinearity.
- Age has 177 missing values and Cabin has 687 missing values.
- Outliers in Fare, SibSp and Parch are real cases (rich passengers, large families), so they are not errors.

## Files
- `Titanic-Dataset.csv`: dataset
- `task2_eda.ipynb`: full code
- `histograms.png`, `boxplots.png`, `correlation_heatmap.png`, `pairplot.png`, `survival_patterns.png`: charts
