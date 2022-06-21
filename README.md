# Predict-Customer-clicks-on-FB-ads
Using Logistic regression to predict customer clicks on Facebook adverts
# Task
You have been hired as a consultant to a start-up that is running a targetted marketing ads on facebook. The company wants to anaylze customer behaviour by predicting which customer clicks on the advertisement. Customer data is as follows:
# Inputs:

•	Name

•	e-mail

•	Country

•	Time on Facebook

•	Estimated Salary (derived from other parameters)

# Outputs:

•	Click (1: customer clicked on Ad, 0: Customer did not click on the Ad)

# Methods

•	Get data from .csv

•	Visualization
   
   o	Visualization with seaborn ad matplotlib

•	Model training
   
   o	Logistic regression
# Result
Using Logistics Regression. The result is shown in the table below:

Clicked: did not click: 0, clicked: 1

|	          |precision|recall|f1-score|support|
|-----------|---------|------|--------|-------|
|0	        |0.83     |0.90  |0.86    |48    |
|1	        |0.90     |0.83  |0.86    |52     |
|accuracy   |-	      |-	   |0.86	  |100    |
|macro avg  |0.86     |0.86  |0.86	  |100   |
|weighted avg|0.86    |0.86  |0.86	  |100   |
