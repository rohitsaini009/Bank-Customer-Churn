
# <center> BANK CUSTOMER CHURN PREDICTION </center>

<center><img src="https://creazilla-store.fra1.digitaloceanspaces.com/cliparts/9108/bank-clipart-md.png" width=700></center>

**PROBLEM STATEMENT: BANK CUSTOMER CHURN PREDICTION**

<font size="3">The dataset on bank customer churn is widely employed to forecast customer attrition within the banking sector. It encompasses details about customers who have either departed from the bank or are currently active customers.</font>

**Features**
1. Customer ID: A unique identifier for each customer
2. Surname: The customer's surname or last name
3. Credit Score: A numerical value representing the customer's credit score
4. Geography: The country where the customer resides (France, Spain or Germany)
5. Gender: The customer's gender (Male or Female)
6. Age: The customer's age.
7. Tenure: The number of years the customer has been with the bank
8. Balance: The customer's account balance
9. NumOfProducts: The number of bank products the customer uses (e.g., savings account, credit card)
10. HasCrCard: Whether the customer has a credit card (1 = yes, 0 = no)
11. IsActiveMember: Whether the customer is an active member (1 = yes, 0 = no)
12. EstimatedSalary: The estimated salary of the customer
13. Exited: Whether the customer has churned (1 = yes, 0 = no)

**Metric of Evalutaion:** ROC-AUC

# Results

### Modeling

* A Rendom Forest Regressor and XGboost This model has 10 features, making the most use of the NumOfProducts,Age,IsActiveMember,Gender,Balance,CreditScore.
* The leaderboard ROC-AUC Score obtained by this model is 88.75








