# credit_card_user_behavior

Business Goal: To understand and analyse credit card user behavior to target different business objectives
Methods used:
1. Data cleaning
2. EDA
3. Data preprocessing and normalization
4. K means clustering technique
5. Best fit 'K' value selection by Elbow method and silhouette score
6. Building clustering model with best fit k value
7. Cluster interpretation with distribution plots
8. PCA dimension reduction and plot visulization  in 2 dimensions
9. Conclusion:Market strategy study to map cluster characteristics to business objectives

Cluster Characteristics and potential business objectives:

Different ways credit card companies/Banks gain profit are:
1.Interest on due payments/cash advances
2.By charging merchants on number of credit card transactions 

Four cluster model which can be used to drive different business objectives on different clusters
1. cluster 0:Money Savers: Is the cluster with least amount and frequency of purchases
2. cluster 1:Spenders: Is the cluster with highest amount of purchases of bothe type: onetime as well as installment based
3. cluster 2:People with installment purchases:Is the cluster with highest frequency of purchases made in installments
4. cluster 3:Cash in advance payments:Is the cluster with highest number of cash in advance type transactions with highest monthly minimum payment amount requirement and highest credit limit

Potential business objectives for each cluster :
1. cluster 0: This seems to be a group of money saver people prefering least transactions, this group can be encouraged to make more purchases by availing several offers for thei credit cards
2. cluster 1: As this cluster seems to be group of spenders, credit card purchases in wide product domains can be encouraged for the group
3. cluster 2: As this cluster seems to be group of people with installment purchases,can be targeted to make EMI based product purchases
4. cluster 4:  As this cluster seems to be group of people douing cash in advance payments, interest rate optimization can be done for this group, for interest profit margin optimization
