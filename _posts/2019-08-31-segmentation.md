---
title: "Credit Card Users' Behavioral Segmentation"
date: 2019-08-31
tags: [Clustering]
excerpt: "Data Science, K Means"
---

The aim of the following case was to do customer segmentation in order to develop a marketing strategy.
The dataset contained credit card usage of around 9000 active users for the last 6 months. 
Data pre-processing involved appropriate handling of missing values and outliers as well as dropping any variable that was irrelevant to the task of segmentation e.g. Customer ID. A ***correlation matrix*** was constructed to see any obvious dependencies between different variables that should be taken into account before applying the clustering algorithm.

The original ***18 of behavioral variables were used to derive intelligent Key Performance Indicators (KPIs)*** in order to build an enriched customer profile. The KPIs were then explored to gain some insight on the customer behavioral patterns. ***Factor analysis was used for dimension reduction to arrive at 8 underlying factors***. The number of factors were decided using the ***Kaiser test*** and ***scree plots***. The reduced factors were used to cluster similar credit card users into segments using K-means. 

Here is a scree plot that let us decide the number of factors to be used.
          
<img src="{{ site.url }}{{ site.baseurl }}/images/segmentation/scree.jpg" alt="Scree Plot">

The R code and the final report with results can be found [here](https://github.com/SameeraSuhail1/Customer-Segmentation).  
Directly download the final report with complete analysis and results [here](https://github.com/SameeraSuhail1/Customer-Segmentation/raw/master/final-output.xlsx).