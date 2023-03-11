# JAVA_FULL_STACK.
Java full stack assignment 1 - Ashmi.S

#Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers.

## Program:
```
/*
Program to implement the SVM For Spam Mail Detection..
Developed by: ASHMI.S
RegisterNumber:  212221040021
*/
import pandas as pd
data = pd.read_csv("/content/spam.csv",encoding = 'latin-1')
data.head()
data.info()
data.isnull().sum()
x = data["v1"].values
y = data["v2"].values
from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test = train_test_split(x,y,test_size = 0.2,random_state = 0)
from sklearn.feature_extraction.text import CountVectorizer
cv = CountVectorizer()    
x_train = cv.fit_transform(x_train)
x_test = cv.transform(x_test)
from sklearn.svm import SVC
svc = SVC()
svc.fit(x_train,y_train)
y_pred = svc.predict(x_test)
y_pred
from sklearn import metrics
accuracy = metrics.accuracy_score(y_test,y_pred)
accuracy
```

## Output:
## HEAD:
![GITHUB LOGO](s1.png)
## INFO:
![GITHUB LOGO](s2.png)
## ISNULL:
![GITHUB LOGO](s3.png)
## SVC PREDICT:
![GITHUB LOGO](s4.png)
## ACCURACY:
![GITHUB LOGO](s5.png)

## Result:
Thus the program to implement the SVM For Spam Mail Detection is written and verified using python programming.
