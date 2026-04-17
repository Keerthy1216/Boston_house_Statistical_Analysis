# **Boston Housing Statistical Analysis**

### **Project Description:**

This project performs a comprehensive statistical analysis on the Boston Housing Dataset (U.S. Census data). The analysis includes exploratory data search, descriptive statistics, data visualization, and various hypothesis tests (T-tests, ANOVA, Pearson Correlation, and Linear Regression) to understand the factors influencing housing prices.

### **Dataset Overview**

The dataset contains information collected by the U.S. Census Service concerning housing in the area of Boston, MA. Key variables include:

* **CRIM:** Per capita crime rate by town.
* **CHAS:** Charles River dummy variable (1 if tract bounds river; 0 otherwise).
* **NOX:** Nitric oxide concentration (parts per 10 million).
* **RM:** Average number of rooms per dwelling.
* **AGE:** Proportion of owner-occupied units built prior to 1940.
* **DIS:** Weighted distances to five Boston employment centres.
* **MEDV:** Median value of owner-occupied homes in $1000s.

### **Requirements**

To run the notebook, you need the following Python libraries:

* pandas
* numpy
* matplotlib
* seaborn
* scipy
* statsmodels
* sklearn

### **Analysis Workflow**
**1. Descriptive Statistics & Visualization**

* **Boxplots:** Used to identify outliers and distributions of the Median Value (MEDV).
* **Bar Plots:** Visualized the distribution of houses bordering the Charles River.
* **Scatter Plots:** Explored the relationship between Nitric Oxide concentrations (NOX) and industrial acreage (INDUS).

**2. Hypothesis Testing**

The project addresses four key research questions:
| Question | Test Used | Key Finding |
|----------|----------|-------------|
| Is there a significant difference in home values based on Charles River proximity? | T-test | Significant. Houses near the river have different market values (p < 0.05). |
| Does the age of the house (AGE) impact the median value (MEDV)? | ANOVA | Significant. Older houses tend to be cheaper than newer ones. |
| Is there a relationship between NOX and INDUS? | Pearson Correlation | Strong positive correlation (r = 0.76). Higher industrial areas have higher NOX levels. |
| What is the impact of distance to employment centres (DIS) on home values? | Linear Regression | Significant positive impact. Every unit increase in distance increases value by about 1.09 (in $1000s), i.e., ~$1,091. |


### **Author :** Keerthana K
