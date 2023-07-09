# Churn-Prediction-and-Customer-Segmentation
Churn prediction project, CentraleSupélec x BCG Gamma, Winter 2022

### Goal
Predict churn of customers based on their consumption data

### Language
```Python```

### Contents
1. Primary analysis
2. Pre-processing and features engineering
3. Models
4. Evaluation

### Libraries
* ```pandas```
* ```numpy```
* ```matplotlib```
* ```seaborn```
* ```scikit-learn```

### Conclusion
I first analyzed the business of the company and its activity to understand the number of customers, products, the diversity of distribution channels, ... I was able to observe that it is a very large company with a lot of product references and many customers. It possesses numerous data that are necessary to understand, target, and analyze the customers.

I decided to implement a churn prediction algorithm because it is an easily implementable use case with significant results and added value. By trying different classification algorithms, I selected the SVM algorithm, which allows maximizing the margin between the two classes. This algorithm seemed to be the most suitable in order not to miss too many customers who will churn, even if it means detecting too many. With this algorithm, we obtained the following performance metrics: Precision of 0.88, Recall of 0.79, and an F1-score of 0.80. These performances can undoubtedly be improved, but they seem sufficient at first to propose a Proof of Value to the company and show them the savings they can achieve.
