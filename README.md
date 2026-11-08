# Vendor Recommendation System



\## Overview



This project builds a machine learning–based recommendation system to predict and rank vendors (restaurants) for customers.



\---



\## Problem Statement



Instead of directly predicting vendor IDs, the problem is reframed as a \*\*binary classification task\*\*:



\* Given (customer, vendor) → predict probability of selection



\---



\## Approach



\### 1. Data Preparation



\* Split dataset into:



&#x20; \* Customer features

&#x20; \* Vendor features



\### 2. Dataset Creation



\* Created customer–vendor pairs:



&#x20; \* Label = 1 (chosen vendor)

&#x20; \* Label = 0 (non-chosen vendors)



\### 3. Model



\* Random Forest Classifier



\### 4. Evaluation



\* Accuracy: \~81%

\* Metrics:



&#x20; \* Precision

&#x20; \* Recall

&#x20; \* F1 Score

&#x20; \* ROC-AUC



\---



\## Recommendation System



For a given customer:



1\. Combine with all vendors

2\. Predict probability

3\. Rank vendors

4\. Recommend top results



\---



\## Tech Stack



\* Python

\* Pandas

\* NumPy

\* Scikit-learn

