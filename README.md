# HR-Analytics-Case-Study

## Introduction

This project aims to analyze the factors that influence employee attrition and retention in a large company. The data set contains information about 4410 employees, such as their department, salary, promotion status, work accident, time spent in the company, number of projects, and whether they left or stayed.

## Data Sources

The data set consists of the following files:

- `employees.csv`: The main data file that contains the employee attributes and the target variable `left`.
- `data_dictionary.xlsx`: A file that explains the meaning and possible values of each column in the main data file.
- `employee_survey_data.csv`: A file that contains the results of a survey conducted among the employees, measuring their job satisfaction, environment satisfaction, and work-life balance.
- `manager_survey_data.csv`: A file that contains the results of a survey conducted among the managers, measuring their job involvement and performance rating.
- `in_time.csv` and `out_time.csv`: Two files that contain the daily in-time and out-time records of each employee for the year 2015.

## Data Analysis

The data analysis was performed using Python 3.8.5 and the following libraries:

- pandas 1.1.3
- numpy 1.19.2
- matplotlib 3.3.2
- seaborn 0.11.0

The code for the data analysis can be found in the file `hr_analytics.ipynb`. The code performs the following steps:

- Importing the data files and merging them into a single data frame
- Exploring the data and checking for missing values, duplicates, outliers, and data types
- Performing descriptive statistics and correlation analysis on the numerical variables
- Visualizing the distribution and relationship of the variables using histograms, boxplots, scatterplots, and heatmaps
- Performing chi-square tests and ANOVA tests on the categorical variables to check for association with the target variable
- Creating new features based on the existing variables, such as average working hours per day, average satisfaction score, and average performance score
- Selecting the relevant features for building a predictive model using feature importance and correlation methods
- Splitting the data into training and testing sets
- Building and evaluating different classification models, such as logistic regression, decision tree, random forest, and gradient boosting
- Comparing the performance of the models using accuracy, precision, recall, f1-score, and ROC curve metrics
- Choosing the best model based on the evaluation results and interpreting its coefficients or feature importances
- Making predictions on the test set using the best model and analyzing the results

## Results

The main findings from the data analysis are as follows:

- The employee attrition rate in the company is 23.81%, which is quite high compared to the industry average of 15%¹.
- The most important factors that influence employee attrition are salary, promotion status, number of projects, time spent in the company, work accident, department, and average satisfaction score.
- The employees who are most likely to leave are those who have low or high salary, have not been promoted in the last five years, have too few or too many projects, have spent more than three or six years in the company, have not had a work accident, work in sales or technical department, and have low satisfaction score.
- The best model for predicting employee attrition is gradient boosting with an accuracy of 97.28%, a precision of 95.83%, a recall of 93.75%, an f1-score of 94.78%, and an AUC of 0.99 on the test set.

## Conclusion

Based on the results of the data analysis, some recommendations for reducing employee attrition are:

- Increase the salary of the employees who are underpaid or overqualified for their roles
- Provide more opportunities for career advancement and recognition for the high-performing employees
- Balance the workload and expectations of the employees who have too few or too many projects
- Offer more flexibility and autonomy for the employees who have spent a long time in the company
- Improve the safety and well-being of the employees who have experienced a work accident
- Enhance the work environment and culture of the sales and technical departments
- Conduct regular surveys and feedback sessions to monitor and improve employee satisfaction
