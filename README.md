![image](https://github.com/user-attachments/assets/791e432a-d52e-4553-ba25-edc4ddeccdb5)# Telecom Churn-case-study

## Objective

In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.
For many incumbent operators, retaining high profitable customers is the number one business goal.
To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.
In this project, we have analysed customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.


## Steps Followed

### Reading and cleaning data
- Handle missing values in rows and columns
- Removed unwanted columns
- Imputed missing values
- Deleted unwanted records
- Tagged the churned customers (churn=1, else 0) based on the fourth month as follows: Those who have not made any calls (either incoming or outgoing) AND have not used mobile internet even once in the  churn phase.
- Deleted all the attributes corresponding to the churn phase
- Treated outliers
- Derived new columns.

### EDA
- Churn rate on the basis whether the customer decreased her/his MOU in action month
- Churn rate on the basis whether the customer decreased her/his number of recharge in action month
- Churn rate on the basis whether the customer decreased her/his amount of recharge in action month
- Churn rate on the basis whether the customer decreased her/his amount of recharge in action month
- Analysis of the average revenue per customer (churn and not churn) in the action phase
- Analysis of the average revenue per customer (churn and not churn) in the action phase
- Analysis of the average revenue per customer (churn and not churn) in the action phase
- Analysis of the average revenue per customer (churn and not churn) in the action phase
- Analysis of recharge amount and number of recharge in action month

### Building a logistic regression model with PCA
- Splitting the dataset in train and test set
- Dealing with data imbalance
- Feature scaling
- Logistic regression with PCA
- Support vector machine with PCA
- Decision tree with PCA
- Random Forest with PCA
- Logistic regression without PCA
- ROC curve

### Prediction on test set
- Logistic regression with PCA - Prediction on test set
- Support vector machine with PCA - Prediction on test set
- Decision tree with PCA - Prediction on test set
- Random Forest with PCA - Prediction on test set
- Logistic regression without PCA - Prediction on test set
  
## Files uploaded:
- Telecom Churn case study - Presentation pdf
- telecom-churn-case-study.ipynb - Python commented file
- README.md file

### Case study group: Shagun Choudhary, Pooja Mathur, Alistair Dsilva
