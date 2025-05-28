# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import required Python libraries for data manipulation and machine learning.

### Step2
Load the dataset (e.g., from a CSV file).

### Step3
Define the features (X) and target (y).

### Step4
Create and train the regression model.

### Step5
Check the coefficients and intercept of the trained model.

### Step6
Use the model to make a prediction with new input data.

## Program:
```
``
#Implementation of Multivariate Linear Regression
#Developed by : VUTUKURI SAI KUMAR REDDY
#Registration no : 212224230307
``
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("car (1).csv")
x=df[["Volume","Weight"]]
y=df[["CO2"]]
regression=linear_model.LinearRegression()
regression.fit(x,y)
print(regression.coef_)
print(regression.intercept_)
print(regression.predict([[3300,1300]]))

```
## Output:

### Insert your output
![image](https://github.com/user-attachments/assets/2661155f-4052-41c9-8c33-9326183ef858)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
