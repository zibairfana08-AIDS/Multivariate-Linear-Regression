# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Start
2. Import required libraries
3. Load the dataset
4. Split data into X (inputs) and Y (output)
5. Divide into training and testing sets
6. Create Linear Regression model
7. Train the model using training data
8. Predict output using test data
9. Evaluate the model performance
10. Stop

## Program:
#Developed By: Irfana M
#RegisterNumber : 212225230105
```
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("car (1).csv")
x=df[["Volume","Weight"]]
y=df["CO2"]
regression=linear_model.LinearRegression()
regression.fit(x,y)
print(regression.coef_)
print(regression.intercept_)
print(regression.predict([[3300,1300]]))
```
## Output:
<img width="1411" height="298" alt="Screenshot 2026-03-26 111906" src="https://github.com/user-attachments/assets/1f2979ea-2c3e-4331-8945-c8c64bed2741" />

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
