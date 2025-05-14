# Correlation Analysis of Movie Dataset
This Python project analyzes the correlation between various features of movies from `movies.csv` such as *budget*, *gross earnings*, *ratings*, *votes* and other metadata like *genre*, *director* and *company*. The goal is to determine which factors most significantly correlate with a film's financial success.

##### Tools & Libraries Used

- [Python 3](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

##### Data Cleaning Steps

+ Checked for missing values and removed rows where *budget* or *gross* was missing.
+ Converted *budget* and *gross* to integers.
+ Extracted the correct year from the *released* column.
+ Converted categorical columns to numerical codes for correlation analysis.

##### Visualizations

+ **Scatter plot**: Budget vs Gross earnings.
+ **Regression plot**: Seaborn regression to visualize correlation.
+ **Heatmaps**: Pearson correlation of numeric features and numerized categorical features.<br><br>

**P.S.** This project was built with the help of [Alex The Analyst](https://www.youtube.com/@AlexTheAnalyst).
