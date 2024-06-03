# Predicting Employee Turnover to Enhance Retention at Salifort Motors [WIP]
This project was completed as part of the Google Advance Data Analytics Professional Certificate. This repository is a work-in-progress, as I am cleaning up notebooks and images.

## Overview
This project aimed to improve employee retention by identifying factors that contribute to employee attrition. By analyzing the data collected from employees, the project aimed to build a predictive model to forecast the likelihood of employees leaving the company. Utilizing machine learning techniques, specifically a random forest model, the analysis revealed that key factors influencing employee turnover included 'last evaluation', 'tenure', 'number of projects', 'overwork', 'low salary', and 'work accidents'. The project focused on developing a high-performing random forest model, which achieved an AUC of 96.5%, precision of 87%, recall of 90.4%, and accuracy of 96.2%. The analysis revealed that last evaluation score, number of projects, tenure, and overworked status were the primary factors influencing employee turnover. These insights guided actionable recommendations aimed at improving employee satisfaction and retention.

## Data Understanding
The dataset provided by Salifort Motors included 14,999 records with 10 variables: satisfaction level, last evaluation score, number of projects, average monthly hours, tenure, work accidents, whether the employee left, promotions in the last five years, department, and salary level. Initial exploratory data analysis revealed no missing values but identified significant duplicates and outliers, particularly in the tenure and average monthly hours columns. The data was cleaned, and essential transformations were applied, such as encoding categorical variables and engineering new features like 'overworked' to improve model performance.

Below is a box plot showcasing the monthly hours worked by the number of projects, highlighting that employees who left had higher average monthly hours worked.

[box plot of monthly hours worked by number of projects]

## Modeling and Evaluation
The primary focus was on developing a random forest model to predict employee turnover. The random forest model was selected for its robustness and ability to handle complex interactions between variables. After extensive feature engineering, which included creating an 'overworked' indicator and removing potentially leaked features like satisfaction levels, the random forest model demonstrated outstanding performance. The model achieved an AUC of 96.5%, precision of 87%, recall of 90.4%, and accuracy of 96.2%. The model identified key factors that influence employee attrition, which can be seen in the feature importance plot below. The most important factors include last evaluation score, number of projects, tenure, and overworked status. This high-performance model provided reliable predictions and valuable insights into the primary drivers of employee turnover at Salifort Motors.

[feature importance plot]

## Conclusion
The analysis confirmed that employees at Salifort Motors were leaving primarily due to being overworked and undervalued. Recommendations to improve retention included capping the number of projects, investigating dissatisfaction among long-tenured employees, clarifying workload expectations, and improving communication about company policies. Implementing these changes is expected to enhance employee satisfaction and reduce turnover rates, which can benefit the company by maintaining a more stable and experienced workforce.
