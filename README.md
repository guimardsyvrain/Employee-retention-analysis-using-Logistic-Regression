# Employee Retention Analysis at Salifort Motors Using Logistic Regression

## Overview
The Human Resources department at Salifort Motors aims to identify the key factors influencing employee retention and turnover. To support this initiative, the company conducted an employee survey to gather insights on employee engagement, work environment, job satisfaction, and workplace experience.

In this project, a predictive analytics approach was developed using a logistic regression model to estimate the likelihood of employee attrition. The analysis explores how variables such as department, workload, number of projects, average monthly working hours, performance evaluation, and other employee-related factors contribute to retention outcomes.

The objective of this project is to provide data-driven insights that can help Salifort Motors improve employee retention strategies, enhance workplace satisfaction, and support informed HR decision-making.

## Data understanding
To better understand employee attrition, the HR team at Salifort Motors conducted an anonymous employee satisfaction survey completed by more than 14,500 employees. The survey data was combined with internal HR records, cleaned, and prepared for predictive modeling using logistic regression, with employee departure as the target variable.

The dataset contains 14999 records including the following Key features employee satisfaction level, performance evaluation score, workload (projects and monthly hours), years at the company, workplace accidents, promotion history, and salary level.

## Model results
A logistic regression model was developed and evaluated on more than 14,000 employee records using 5-fold cross-validation to ensure model robustness and generalization performance. The analysis identified the most influential factors associated with employee attrition, with satisfaction level, tenure, workload, workplace incidents, and compensation emerging as the strongest predictors of employee turnover.

The feature importance analysis below highlights the relative contribution of each variable to the likelihood of an employee leaving the company, providing actionable insights to support HR retention strategies and workforce planning.
<img width="757" height="562" alt="image" src="https://github.com/user-attachments/assets/39673458-ec13-43ef-b944-9fc7d44d9c3b" />

## Insights and recommendations
* Cap the number of projects that employees can work on.
* Consider promoting employees who have been with the company for at least four years, or conduct further investigation about why four-year tenured employees are so dissatisfied.
* Either reward employees for working longer hours, or don't require them to do so.
* If employees aren't familiar with the company's overtime pay policies, inform them about this. If the expectations around workload and time off aren't explicit, make them clear.
* Hold company-wide and within-team discussions to understand and address the company work culture, across the board and in specific contexts.
* High evaluation scores should not be reserved for employees who work 200+ hours per month. Consider a proportionate scale for rewarding employees who contribute more/put in more effort.
