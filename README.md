# Employee_Turnover_Prediction
Classification, predictive analytics

## Project Overview
* Identified the key factors behind employee turnover through EDA and Feature importance and made suggestion based on the findings.
* Executed diverse models such as Logistic Regression, KNN Classifier and Random Forest to identify key predictors.
* Visualized KNN using feature selection and PCA. several models using respective techniques

## Resources Used
* dataset : https://www.kaggle.com/datasets/marikastewart/employee-turnover

## EDA & Visualization
I looked at the distributions of numerical and categorical variables based on the churn result(0 or 1). Below are a few highlights.
![alt text](https://github.com/Hayoung-Zoe-Kim/Employee_Turnover_Prediction/blob/main/1.png)
![alt text](https://github.com/Hayoung-Zoe-Kim/Employee_Turnover_Prediction/blob/main/2.png)
![alt text](https://github.com/Hayoung-Zoe-Kim/Employee_Turnover_Prediction/blob/main/3.png)
![alt text](https://github.com/Hayoung-Zoe-Kim/Employee_Turnover_Prediction/blob/main/4.png)
![alt text](https://github.com/Hayoung-Zoe-Kim/Employee_Turnover_Prediction/blob/main/5.png)
![alt text](https://github.com/Hayoung-Zoe-Kim/Employee_Turnover_Prediction/blob/main/6.png)
![alt text](https://github.com/Hayoung-Zoe-Kim/Employee_Turnover_Prediction/blob/main/7.png)
![alt text](https://github.com/Hayoung-Zoe-Kim/Employee_Turnover_Prediction/blob/main/8.png)

## Model performance
The Random Forest model far outperformed the other approaches on the test and validation sets. 

![alt text](https://github.com/Hayoung-Zoe-Kim/Employee_Turnover_Prediction/blob/main/9.png)


## Conclusion & Suggestion
* Satisfaction score, Review(employee performance evaluation) score, tenure and average monthly working hours were the top 4 important variables.

Based on our comprehensive analysis, we propose the following suggestions for the top 4 variables we have identified.
- Satisfaction: The highest churn rate was observed not only in employees with low satisfaction scores (30-50 out of 100) but also in the group with high satisfaction scores (70-90 out of 100).
Assuming high satisfaction scores indicate loyalty would be naive, as some employees may not have provided honest responses in the survey. A more comprehensive understanding may require exploring various aspects beyond direct survey inquiries, including everyday observations.
- Review: The unexpected positive correlation between turnover and review scores, along with the high churn rate among outstanding employees with high ratings (90 or above), calls for a focus on providing appropriate promotions and bonuses to retain top talent.
For underperforming employees, organizational-level education and management are crucial, while high-performing employees may benefit from exclusive rewards and enhanced opportunities for motivation.
- Average Working Hours of Month: The unexpected high turnover in the group with the least monthly average working hours suggests considering industry standards, as it may indicate potential overworking compared to norms.
Alternatively, the second-highest turnover in the group with the most working hours suggests that working hours indeed have a significant impact on employee retention.
Therefore, exploring company-wide measures to promote a culture of efficiency and time management, preventing burnout, and improving overall well-being might be essential to address this issue.
- Tenure: There were significant turnover rates observed in the 2-3 years and 7-8 years tenure groups, which could be related to promotions and active job-seeking periods. Since tenure is closely tied to individual career building, it may seem somewhat out of the company's control. Nevertheless, discerning some patterns, developing retention strategies for long-tenured employees, such as offering growth opportunities, mentorships, and fostering a positive work environment, would be essential.




