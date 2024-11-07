# Customer Churn Analysis
I use information of the customers in a bank, such as balance, gender, and age, to analyze if a customer quits the bank or stays in the bank.

### Key finding and insights
1. I apply logistic regression, K-nearest neighbor (KNN), support vector machine (SVM), decision tree, random forest, gradient boosting,
   and XGBoosting models on the dataset to predict the customer churn. For the churn prediction task on this dataset,
   tree-based and ensemble models outperforme distance-based models.

2. This bank probably has low saving rate and is not keen on offering investment options. However, this bank probably offer good loan rate.

3. Age and the number of bank products a customer owns are the most relevant features to affect the churn. Customers who are older and own only one bank product tend to quit the bank.
   Customers with two bank producs tend to stay in the bank.

4. With my stacked model, stacked by XGBoosting, random forest, and decision tree, we could prevent 71% of the churn and reduce 50% of the loss.

### Data
Data can be downloaded from [here](https://www.kaggle.com/datasets/divu2001/customer-churn-rate/data]).

