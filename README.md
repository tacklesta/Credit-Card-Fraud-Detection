# Credit-Card-Fraud-Detection

The dataset contains transactions made by credit cards in September 2013. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions

Traditionally, we could begin with any number of ways to explore and then decide on a particular technique to classify the fraud transactions and use a performance metric to justify the results. I have implemented Undersampling with Neural Nets to classify the fraudulent transactions. Then, using recall metric, I estimate the recall-score.

 In this particular use case, I decide on recall-score performance metric because of our primary focus on how many data points from the positive class did we classify correctly.
 
 We got a fair trade-off with 96% for both accuracy and recall.
