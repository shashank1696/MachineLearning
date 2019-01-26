# MachineLearning
To predict the salary of Employees across different levels, skill set from StackOverFlow dataset using Decision Tree, Random Forest and Gradient Boosting Algorithm techniques.

## Goal for this Notebook:
Show a simple example of an analysis of the StackOverflow datset in Python using a full complement of PyData utilities. Here we Predict the Amount Spent for range of Customers considering the salaries of customers with different roles.

## Attributes
1)  RespondentID(Integer)
2)  Salary(Float)
3)  YearsCodedJob(Integer)
4)  OpenSource(Binary)
5)  Hobby(Binary)
6)  CareerSatisfaction(Integer)
7)  Datascientist(Binary)
8)  Database administrator(Binary)
9)  Desktop applications developer(Binary)
10) Developer with stats/math background(Binary)
11) CompanySizeNumber(Categorical:(Float) 'new')
12) DevOps(Binary)
13) Embedded developer(Binary)
14) Graphic designer(Binary)
15) Graphics programming(Binary)
16) Machine learning specialist(Binary)
17) Mobile developer(Binary)
18) Quality assurance engineer(Binary)
19) Systems administrator(Binary)
20) Web developer(Binary)
21) Remote(Categorical: 'Remote' or 'Non-Remote')

## Data Handling
1) Importing Data with Pandas
2) Cleaning Data
3) Exploring Data through Visualizations with graphs
4) Data Prediction

## Packages required in Python
1)  pandas
2)  numpy
3)  sklearn.tree
4)  sklearn.model_selection
5)  pydotplus
6)  os
7)  from IPython.display importing Image
8)  sklearn.metrics
9)  sklearn.ensemble
10) sklearn.ensemble.partial_dependence

## Graphs
- Feature Importance using Gradient Boosting Algorithm
![machinelearning2](https://user-images.githubusercontent.com/44108439/50859627-e302cd80-13b9-11e9-9e6c-748e78c93428.png)
 
- RespondentID VS Partial dependence
![machinelearning1](https://user-images.githubusercontent.com/44108439/50859634-e8601800-13b9-11e9-986a-d2544253070c.png)

## Error Calculations
1) Mean Absolute Error: 413.53466720353447
2) Mean Squared Error: 421771.9310288262
3) Root Mean Squared Error: 649.439705460658

## Conclusion
- Predicting the Amount Spent for range of Customers considering the salaries of customers
  with different roles using different Algorithms:
* Using Decision Tree Regression Algorithm with 62.9% accuracy and
* Using Gradient Boosting Algorithm with 66.3% accuracy and
* Using Random Forest Regressor Algorithm with 64.6% accuracy(Mean Absolute Error: 17180.42 degrees)
