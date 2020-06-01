# Telecom-Churn-Case-Study

## Problem Statement :

    You have a telecom firm which has collected data of all its customers. The main types of attributes are:
      - Demographics (age, gender etc.)
      - Services availed (internet packs purchased, special offers taken etc.)
      - Expenses (amount of recharge done per month etc.)
    Based on all this past information, you want to build a model which will predict whether a particular customer 
    will churn or not, i.e. whether they will switch to a different service provider or not. 
    So the variable of interest, i.e. the target variable here is ‘Churn’ which will tell us whether or not a 
    particular customer has churned. 
    It is a binary variable - 1 means that the customer has churned and 0 means the customer has not churned.
    
    
    So, here’s what the data frame churn_data looks like:
   
   ![alt text](https://github.com/manishkadam007/Telecom-Churn-Case-Study/blob/master/Data/Churn.png)
     
    Also, here’s the data frame customer_data:
   ![alt text](https://github.com/manishkadam007/Telecom-Churn-Case-Study/blob/master/Data/customer%2Bdata.png)
     
    Lastly, here’s the data frame internet_data:
   ![alt text](https://github.com/manishkadam007/Telecom-Churn-Case-Study/blob/master/Data/Internet%2BData.png)
     
    Now, as you can clearly see, the first 5 customer IDs are exactly the same for each of these data frames.
    Hence, using the column customer ID, you can collate or merge the data into a single data frame. 
    We'll start with that in the next segment.
