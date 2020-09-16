# SMOTE-and-Hierarchy-Modeling

#### 1. We use SMOTE with unbalanced data to classify data in different classes. My data had 93:7 ratio of O:1.
#### 2. The data had call drop percent for hourly data for5000 location in 2019. My aim was to build a machine learning model to predict call drop percent for future. Only a sample was used out of 40 million rows in the dataset.

# Hierarchial Model

#### 3. Business was interested to see the call drop percent > 1 but as 93% of the data had 0 drop call percent.
#### 4. Using SMOTE, the we classify the data into drop call 0 or greater than 0. Post this random forest regressor was used for the data points which were predicted as 1 (drop call % greater than 1).
