# Credit-Card-Fraud
This repository contains Credit card fraud detection algorithm using machine learning techniques in python.

# Credit Card Fraud Detection : 
With a lot of people, banks and online retailer being a victim of credit card fraud, a model detecting whether the transaction is fraud or not can help in saving a huge amount of money.

 # Dataset:
 The dataset has been obtained from kaggle. This dataset contains 284807 rows and 30 numeric columns and one class that specifies whether the transaction is fraudulent or not. 
 
 # Algorithm:
 Isolation Forest Algorithm
 Local Outlier Factor(LOF) Algorithm
   
  # Isolation Forest Algorithm:
 One of the newest techniques to detect anomalies is called Isolation Forests. The algorithm is based on the fact that anomalies are data points that are few and different. As a result of these properties, anomalies are susceptible to a mechanism called isolation.This method is highly useful and is fundamentally different from all existing methods. It introduces the use of isolation as a more effective and efficient means to detect anomalies than the commonly used basic distance and density measures.
 
 How Isolation Forests Work The Isolation Forest algorithm isolates observations by randomly selecting a feature and then randomly selecting a split value between the maximum and minimum values of the selected feature. The logic argument goes: isolating anomaly observations is easier because only a few conditions are needed to separate those cases from the normal observations. On the other hand, isolating normal observations require more conditions. Therefore, an anomaly score can be calculated as the number of conditions required to separate a given observation.
 
 
 # Local Outlier Factor Algorithm
 The LOF algorithm is an unsupervised outlier detection method which computes the local density deviation of a given data point with respect to its neighbors. It considers as outlier samples that have a substantially lower density than their neighbors.

The number of neighbors considered, (parameter n_neighbors) is typically chosen 1) greater than the minimum number of objects a cluster has to contain, so that other objects can be local outliers relative to this cluster, and 2) smaller than the maximum number of close by objects that can potentially be local outliers. In practice, such informations are generally not available, and taking n_neighbors=20 appears to work well in general.
