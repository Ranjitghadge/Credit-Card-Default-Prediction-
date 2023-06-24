# Credit Card Default Prediction

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

![App Screenshot](https://img.money.com/2022/10/News-2022-Credit-Card-Debt-Increase.jpg?crop=0px%2C49px%2C1728px%2C972px&quality=85)


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📖 Problem Statement:

Predicting whether a customer will default on his/her credit card
This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
## 📖 Data Summary
This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. This study reviewed the literature and used the following 23 variables as explanatory variables:

X1: Amount of the given credit 
(NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.

X2: Gender (1 = male; 2 = female).

X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).

X4: Marital status (1 = married; 2 = single; 3 = others).

X5: Age (year).

X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005) 
as follows: X6 = the repayment status in September, 2005; 

X7 = the repayment status in August, 2005; . . .; X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 

8 = payment delay for eight months; 

9 = payment delay for nine months and above.

X12-X17: Amount of bill statement (NT dollar). 

X12 = amount of bill statement in September, 2005; 

X13 = amount of bill statement in August, 2005; . . .;

X17 = amount of bill statement in April, 2005.

X18-X23: Amount of previous payment (NT dollar). 

X18 = amount paid in September, 2005; 

X19 = amount paid in August, 2005; . . .;

X23 = amount paid in April, 2005.
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
## 📖 Algorithm used:
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Support Vector Machine
5. Gradient Boosting
6. XG Boosting

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 💾 Project Files Description
This Project includes 1 colab notebook and 1 Pdf of presentation.
Executable Files:
Credit-Card-Default-Prediction - Includes Exploratory Data Analysis and all algorithms which are used in this project.
credit card default prediction.pdf - Includes pdf of the presentation of the project.
Output:
Google Colab - All the outputs are visible in the provided colab notebook.
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📖 Conclusion:
From all baseline model, Random forest classifier shows highest test accuracy and F1 score and AUC.
Baseline model of Random forest and decision tree shows huge difference in train and test accuracy which shows overfitting.
After cross validation and hyperparameter tunning, XG Boost shows highest test accuracy score of 87.10% and AUC is 0.874.
Cross validation and hyperparameter tunning certainly reduces chances of overfitting and also increases performance of model.
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📜 Credits

Ranjit Ghadge | Data Analyst | Data Scientist | Machine Learning Engineer 
   
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/Ranjitghadge)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ranjit-ghadge/)

