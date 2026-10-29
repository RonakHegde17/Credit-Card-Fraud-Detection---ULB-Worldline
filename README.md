# Credit-Card-Fraud-Detection---ULB-Worldline 2013
 
# Overview

In this project, we will train and deploy a model to identify fraudulent credit card transactions. We will place an emphasis on honest evaluation to minimize false positives.

Our process will be the following-

- Load dataset and sanity check (shape, # of values, no null values)
- Run a Kolmogorov-Smirnov (KS) test to confirm and rank difference in fraud and legitimate distributions across features.
- 


# Dataset
The dataset is too large for this repo, but can be downloaded
[here](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

Characteristics-
- 284,807 European card transactions over two days in September 2013
- 
- 492 confirmed frauds (0.173% of total)
- `Time`, `Amount`, and 28 anonymized PCA components (`V1`-`V28`). `Class:0` - Legitimate, `Class:1` - Fraud
- Data has been cleaned
