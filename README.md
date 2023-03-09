# HR_Analytics
## Abstract
In any business organization, there are many
positions in the organization for their employees. These positions
are sometimes based on hierarchy where employees
who are in top level positions are more experienced and
have higher skill level than the employees who work under
them. Employees who are in the lower levels, however,
can get promoted to a higher position by the organization
if their work efforts are recognized by the organization.
The role of analyzing, screening, recruiting and promoting
workers in a company is done by the company’s Human
Resources (HR) manager. This project is developed to
assist a HR manager in the tasks mentioned above by
creating a model using different machine learning algorithms
such as Support Vector Machines (SVM), Artificial
Neural Networks (ANN), Random Forest Regressor and
Decision Trees.

## Conclusion
The purpose of this project is to develop a system
where the user, who is the HR manager of a company can
determine whether an employee can get promoted by the
company. By using machine learning algorithms, we find
that in our dataset of over 58,000 employees, approximately
4,600 employees are eligible for a promotion. Our
model uses 5 different ML algorithms and compares the
accuracy to find the most accurate algorithm for the given
dataset and uses this algorithm to predict the output.
In our model, we have found that XGBoostClassifier
gave us the best results not only in terms of accuracy
but also time. By implementing this model to our test
data, we can predict the employees who are eligible for
promotion.

## Contents
The hr_analytics.ipynb file is the notebook that performs data cleaning, visualization, analysis and prediction using machine learning algorithms. 
The train.csv file is the dataset used for this project.
