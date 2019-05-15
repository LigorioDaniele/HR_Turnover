# HR_Turnover

## Data Set

```
-satisfaction_level (0–1)
-last_evaluation (Time since last evaluation in years)
-number_projects (Number of projects completed while at work)
-average_monthly_hours (Average monthly hours at workplace)
-time_spend_company (Time spent at the company in years)
-Work_accident (Whether the employee had a workplace accident)
-left (Whether the employee left the workplace or not (1 or 0))
-promotion_last_5years (Whether the employee was promoted in the last five years)
-sales (Department in which they work for)
-salary (Relative level of salary)
```
## Confusion Matrix
When a classifier predicts an employee will leave, how often does that employee actually leave? This measurement is called “precision”. Random forest again outperforms the other two at about 95% precision (991 out of 1045) with logistic regression at about 51% (273 out of 540), and support vector machine at about 77% (890 out of 1150)

![RF](https://user-images.githubusercontent.com/16623583/57759723-d93bfe80-76fa-11e9-8e79-3af60548cede.JPG)

![RF2](https://user-images.githubusercontent.com/16623583/57760485-ef968a00-76fb-11e9-8b4f-d9e5ca7a73d2.JPG)

## Feature Importance (Random Forest)
```
promotion_last_5years-0.20%
department_management-0.22%
department_hr-0.29%
department_RandD-0.34%
salary_high-0.55%
salary_low-1.35%
Work_accident-1.46%
last_evaluation-19.19%
time_spend_company-25.73%
satisfaction_level-50.65%
```
