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
-dep (Department in which they work for)
-salary (Relative level of salary)
```
## Confusion Matrix
When a classifier predicts an employee will leave, how often does that employee actually leave? This measurement is called “precision”. Random forest again outperforms the other two at about 96% precision (577 out of 601) with logistic regression at about 92% (594 out of 645), and support vector machine at about 93% (592 out of 636)

![RF](https://user-images.githubusercontent.com/16623583/57764556-faedb380-7703-11e9-9113-fc783d9f70c4.JPG)
![RF2](https://user-images.githubusercontent.com/16623583/57764558-fcb77700-7703-11e9-83c1-3d86719e5cc5.JPG)




## Feature Importance (Random Forest)
```
promotion_last_5years-0.16%
salary_high-0.29%
department_RandD-0.62%
department_management-0.79%
department_hr-1.03%
Work_accident-1.46%
salary_low-2.15%
last_evaluation-22.64%
satisfaction_level-34.87%
time_spend_company-35.97%
```
