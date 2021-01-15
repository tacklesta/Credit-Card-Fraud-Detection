# Credit-Card-Fraud-Detection

The dataset contains transactions made by credit cards in September 2013. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions

Traditionally, we could begin with any number of ways to explore and then decide on a particular technique to classify the fraud transactions and use a performance metric to justify the results. I have tried implementing Undersampling and Oversampling both the techniques to deal with imbalance nature of the data and then tried applying varius ML models to classify the fraudulent transactions. Then, using confusion matrix, I estimate the f1-score.
 
 In this particular use case, I decide on f1-score performance metric because of our primary focus on False Positive and False Negative rates.
 
 We got a fair result and able to detect more than 80% fraud transactions and at the same time not classifying a lot of non-fraud transactions as fraud.
