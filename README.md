# ML-Project_7-info.-Employee-Attrition-Prediction
### Data Details 

  Kaggle - https://www.kaggle.com/datasets/patelprashant/employee-attrition?select=WA_Fn-UseC_-HR-Employee-Attrition.csv  
  Colab Notebook - https://colab.research.google.com/drive/1IxU95OCoYi0c2Ds2SKJd86QYQ9YLkob_?usp=sharing
  
#### Please use the Ipynb file in the repository for a detailed explanation of this project. This is because the project has been completed and the steps have been written in the notebook referenced in the repository.
Link - https://github.com/SudeepSinha09/ML-Project_7-info.-Employee-Attrition-Prediction/blob/main/%5B%40co%5D%20-%20Employee%20Attrition%20Prediction.ipynb

## Description

#### Context  
The key to success in any organization is attracting and retaining top talent. I’m an HR analyst at my company, and one of my tasks is to determine which factors keep employees at my company and which prompt others to leave. I need to know what factors I can change to prevent the loss of good people. Watson Analytics is going to help.

#### Content  
I have data about past and current employees in a spreadsheet on my desk top. It has various data points on our employees, but I’m most interested in whether they’re still with my company or whether they’ve gone to work somewhere else. And I want to understand how this relates to workforce attrition.

#### Acknowledgements  
https://www.ibm.com/communities/analytics/watson-analytics-blog/watson-analytics-use-case-for-hr-retaining-valuable-employees/

#### Inspiration  
Which factors led to employee attrition?

## An Overview of EDA

![image](https://user-images.githubusercontent.com/93086122/210525368-048eb516-a41b-48cb-9fb0-3aab9951165a.png)
![image](https://user-images.githubusercontent.com/93086122/210525380-e68891b9-ac74-4ec9-990a-8e7dc6bdb6f4.png)
![image](https://user-images.githubusercontent.com/93086122/210525390-b6223b1e-9182-484e-a6ba-5e358cc6d51f.png)

![image](https://user-images.githubusercontent.com/93086122/210525437-9defcd9d-f59c-494f-999f-b915b973795d.png)

## Attribute Information

Education  
1 'Below College' 2 'College' 3 'Bachelor' 4 'Master' 5 'Doctor'

EnvironmentSatisfaction  
1 'Low' 2 'Medium' 3 'High' 4 'Very High'

JobInvolvement  
1 'Low' 2 'Medium' 3 'High' 4 'Very High'

JobSatisfaction  
1 'Low' 2 'Medium' 3 'High' 4 'Very High'

PerformanceRating  
1 'Low' 2 'Good' 3 'Excellent' 4 'Outstanding'

RelationshipSatisfaction  
1 'Low' 2 'Medium' 3 'High' 4 'Very High'

WorkLifeBalance  
1 'Bad' 2 'Good' 3 'Better' 4 'Best'


## Project Brief

In this project, we aimed to build a machine learning model to predict employee attrition in a company. Attrition, also known as employee turnover, refers to the loss of employees over time due to various reasons such as resignations, retirements, or dismissals. Predicting attrition is important for companies as it can help them identify potential risk areas and take proactive measures to retain their employees.

To build the prediction model, we collected data on various characteristics of the employees, such as their job role, salary, performance, and demographics. We then cleaned and pre-processed the data to prepare it for modeling.

We evaluated several different machine learning models for the task, including logistic regression, random forest, and support vector machine. We trained each model using the training data and evaluated their performance on the test data using various evaluation metrics.

The results showed that the logistic regression model outperformed the other models and was the most accurate in predicting employee attrition. Based on this, we selected the logistic regression model as the final prediction model for employee attrition.

Overall, this project helped us gain a better understanding of the factors that contribute to employee attrition and develop a model that can accurately predict it, enabling us to take proactive measures to retain our valuable employees.

##### The model selected - Logistic regression
