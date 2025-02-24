# Customer_churn_analysis

BUSINESS UNDERSTANDING

OBJECTIVE
SyriaTel, a telecommunication's company, seeks to understand potential customer churn and develop strategies to enhance retention.This project analyzes customer behavior,satisfaction levels from service calls,account length, and incurred charges to identify predictive patterns of churn.These insights will help the company implement targeted incentives, improve service quality, and enhance customer satisfaction which will result in maximizing retention and profitability

KEY BUSINESS QUESTIONS
1.What is the average account length of churned compared to retained customers?

2.Do customers with multiple service complaints have a higher likelihood of churning?

3.How do charges and pricing plans affect customer churn?

### METRICS OF SUCCESS
Churn Rate​

Average Account Length​

Service Call Frequency​

DATA UNDERSTANDING

### OVERVIEW

This dataset contains customer's information such as the account length,service usage,charges and customer service calls and churn status.These features will be used in analysis to help the company implement targeted incentives, improve service quality, and enhance customer satisfaction which will result in maximizing retention and profitability


#### METRICS OF SUCCESS​

Churn Rate​

Average Account Length​

Service Call Frequency​
  ​

#### DISTRIBUTION OF CHURN VERSUS RETAINED CUSTOMERS​

There is a higher number of Retained customers compared to the churn customers. ​
![Image](https://github.com/user-attachments/assets/75d8ef5b-74f5-4889-8b45-3ef9cccd5439)

#### DISTRIBUTION OF CHURN VERSUS  CUSTOMER SERVICE CALLS ​
![Image](https://github.com/user-attachments/assets/bbc0b0ed-1467-44bb-aaa1-3a43221c67a1)
The number of customers who Churn tend to have more complaints .​
This could mean there is poor customer service​

#### DISTRIBUTION OF CHURN VERSUS  ACCOUNT LENGTH​
There is a slight difference between the Average Account Length of the churned and the Retained customers, Although the number of churned customers is still higher​
![Image](https://github.com/user-attachments/assets/90a43bbc-23f9-4371-b8f2-4769ef4ec242)
#### KEY FINDING

Random Forest Classifier​

It has an accuracy score of 93% which is better than the Decision Tree Classifier The ROC AUC score is at 90% which is very good. Recall is 73% which is a good improvement .It will be able to identify more churners Precision is at 76% which is a slight drop but good for handling the False Positives. the F1 score is at 75% which is an increase making the model more balanced at this point.

#### CONCLUSION​
The analysis of various models reveals that while Logistic Regression struggles with imbalanced data and low recall, tree-based models like Decision Tree and Random Forest perform significantly better. Hyperparameter tuning improved the Decision Tree's performance, but it still faced challenges with recall. The Random Forest Classifier emerged as the most balanced model, with high accuracy, ROC AUC, and recall, making it the best choice for identifying churners effectively​

#### RECOMMENDATION​

Adopt the Random Forest Model:​
It provides the best balance of accuracy (93%), ROC AUC (90%), and recall (73%), making it the most reliable model for churn prediction.​
