# Market Basket Analysis in Python using Apriori Algorithm (Code Clause)
Market Basket Analysis has become familiar for analysis in the retail industry. It is also called Association Rules Analysis. This analysis is also used for advice. Personal recommendations in applications such as Spotify, Netflix, and Youtube can be given as examples. One of the biggest examples of Association Rules Analysis is the correlation between beer and diapers. When Walmart, a chain store in the United States, studied the shopping behavior of customers, the study showed that diapers and beers are bought together. Because, as it turns out, fathers are often tasked with shopping while mothers stay with the baby.

# Apriori Algorithm
The Apriori Algorithm, used for the first phase of the Association Rules, is the most popular and classical algorithm in the frequent old parts. These algorithm properties and data are evaluated with Boolean Association Rules. In this algorithm, there are product clusters that pass frequently, and then strong relationships between these products and other products are sought.

The importance of Association Rules can be determined by 3 parameters that are used to identify the strength of the algorithm.
Namely,
* Support
* Confidence
* Lift

Let X and Y represent the products in the market and N represent the total number of products.

Support: It is the probability of an event occurring.

Confidence: It is a measure of conditional probability

Lift: It is the probability of all items occurring together divided by the product of antecedent and consequent occurring as if they are independent of each other.

# Dataset
Dataset Link: https://www.kaggle.com/datasets/hemanthkumar05/market-basket-optimization

The dataset of a mall with 7500 transactions of different customers buying different items from the store is taken into consideration. The aim is to find correlations between the different items in the store. So that store can know if a customer is buying apple, banana and mango, what is the next item, the customer would be interested in buying from the store.
