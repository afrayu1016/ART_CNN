# Clustering_practice

## Context
Use different datasets corresponding to different models : k-means, mean-shift, k-prototypes, k-modes to predict the target values.

## Dataset
1. age_education.csv
2. ageinc.csv
3. customer_offers.csv

## Ageinc - k-means
* Standarize the age and income.
* Use Elbow to find the best k value to minimize the SSE(sum of squared errors).
* Use the best k value and k-means to cluster data, set random_state 10.

## Ageinc - mean-shift
* Standarize the age and income.
* Use estimate_bandwidth to find the best bandwidth value.
* Use mean-shift to cluster data.

## age_education - k-prototypes
* Standarize the age.
* Use k-prototypes to cluster data, set random_state 10 and the number of clustring is 3.

## customer_offers - k-modes
* Use k-modes to cluster data, set random_state 10 and the number of clustring is 4.
