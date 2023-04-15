# Default-Credit-Card-Classification

## Project Summary -
A bank wanted to minimize their financial losses due to credit card defaults and decided to embark on a project to develop a machine learning model that could predict which customers were most likely to default on their payments.

The bank's team gathered a large amount of data on their customers, including credit ratings, transaction history, and demographic information.
They used this data to train a predictive model that would analyze a new customer's data and determine their likelihood of defaulting in the future.

The project involved several stages, including data preprocessing, exploratory data analysis, feature engineering, and model development. However, the team was able to develop a reliable predictive model that helped the bank reduce its financial losses significantly.

The machine learning model helped the bank identify high-risk customers early on and take proactive measures to prevent defaults. They could also provide better service to customers by tailoring credit offerings to their individual needs.

Overall, the Credit Card Default Prediction project was a success story for the bank. By using machine learning to solve a real-world problem, they were able to minimize financial losses and improve customer satisfaction. The bank was now better positioned to make informed credit decisions and offer better service to their customers.

## Problem Statement
How can banks and financial institutions accurately predict which customers are most likely to default on their credit card payments and take proactive measures to prevent defaults? Traditional methods have limitations and often fall short in predicting future defaults. The Credit Card Default Prediction project aims to address this issue by developing a machine learning model that analyzes customer transaction history, credit rating, demographic information, and other relevant factors to determine their likelihood of defaulting. The project's goal is to help financial institutions minimize their financial losses and improve customer satisfaction by identifying high-risk customers early on and preventing defaults before they occur.

## Beautiful Feature Contribution
![image](https://user-images.githubusercontent.com/122529968/232202980-068107e3-e1f5-4516-a66a-bf92ac6bb37c.png)

## Conclusion
1. According to our Hypothesis Testing, the rate of default for males and females has no significant difference. Both the groups have same Statistical Probability for making Defaults.
2. The Age group with 27 and 29 shows maximum defaults, so Banks can be cautious while dealing with such age groups.\

3. For Contributing in the anti-fraudster financial environment, our decision tress classification model was well trained and showing the 77% accuracy on testing dataset. Indeed the model requires more improvement and hence we moved to the next model.
4. Random Forest Classifier shows a little improvement with 86% of testing accuracy, where as its training accuracy is 99%. It is still shows fractional overfitting.
5.Finally the extreme gradient boost classifier comes with maximum training and testing accuracy with a parallel relationship. Its training accuracy is 92% and testing accuracy is 87 %. 6. The cross validation for XGBClassifier was unable to provide help. Because its accuaracy for training is 99% and for testing it is 86%. 7.Hence for the final applications Banks can go with XGBClassifier without tuning.
