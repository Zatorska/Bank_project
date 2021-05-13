# Bank_project

The bank collects information about customers in order to better manage its risk and increase
profitability of products. There are three main areas of customer relationship management:
* acquisition,
* customers' portfolio management, 
* retention
 
_**Each area has its own analytical challenges:**_
* **customer retention** is about encouraging customers to stay with the bank if he intends to close his
account or card. Because of that, bank should be able to define the customers who potentially withdraw from the contract, on
on the basis of their behavior.
* in **customer acquisition** the most important thing is to know what is the risk of loan default for a given customer (this is a reason why analysts count the client's 'credit score').
* in **portfolio management**, the most important is customer segmentation. It helps to create groups of customers with similar preferences, therefore bank can offer profiled products.

### In this project I'm going to take a closer look at  _Customer Retention_. 

#### I will try to answer following questions:

* What is the profile of clients intending to terminate their cooperation with the bank?
* Are there patterns in the data that can be for me interesting or unexpected?

In this project I analyse received dataset, **clean data** and I use few machine learning classification models (such as **Logistic Regression**, **Decision Tree** or **Random Forest**) to find as many dependencies as it's possible. 

**Additionally:**
* I create my own function which finds best parameters for Decision Tree model and compare it with GridSearchCV,
* I check if there is a difference in the effectiveness of models using balanced and unbalanced data.

_Code written in **Python**._
