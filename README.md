# NBA Team Oklahoma City Thunder Analysis

## Project Overview

This project aims to analyze the Oklahoma City Thunder team using various data analysis techniques. The analysis consists of two main operations:
1. **Prediction of Rookie Salaries**: Using historical NBA draft data and performance statistics, we predict the salaries of rookies for the Oklahoma City Thunder.
2. **Best Fit Player Analysis**: Analyzing the advanced statistics of current players to determine which players would best fit the team.

## Key Operations

### 1. Rookie Salary Prediction
The project includes a thorough data acquisition and cleaning process:
- **Data Sources**: NBA team statistics, historical draft data, and salary information (CSV files).
- **Data Cleaning**: Column standardization, removal of currency symbols, and conversion of salary data for analysis.
- **Modeling**: A linear regression model was used to predict salaries based on several performance indicators, such as:
    - Games Played (G)
    - Minutes Played (MP)
    - Points (PTS)
    - Total Rebounds (TRB)
    - Assists (AST)
    - Field Goal Percentage (FG%)
    - Win Shares (WS), and more.

#### Results
- Predicted salaries for 2024 rookies:
    - **Isaiah Joe**: $9,566,838
    - **Aaron Wiggins**: $10,406,023
  
### 2. Best Fit Player Analysis
Using advanced metrics, we performed player analysis to identify individuals who would best suit the team’s needs. Key metrics used include:
- Player Efficiency Rating (PER)
- True Shooting Percentage (TS%)
- Usage Percentage (USG%)
- Win Shares (WS), among others.

#### Machine Learning Models Applied:
- **Naive Bayes Classifier**
- **Support Vector Machine (SVM)**
- **K-Means Clustering**

#### Outcome:
Best-fit players for the Oklahoma City Thunder:
- Mike Conley
- Malik Monk
- Kyle Anderson
- Tyrese Maxey, and more.

## Technologies and Tools Used
- **Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib
- **Models**: Linear Regression, Naive Bayes, SVM, K-Means Clustering
- **Data Source**: CSV files with player statistics, salary information, and draft data.

## Future Enhancements
- Consider more sophisticated models like Random Forest or Neural Networks for better accuracy in salary prediction.
- Incorporate additional variables such as player efficiency and injury history to improve the prediction model.

---
