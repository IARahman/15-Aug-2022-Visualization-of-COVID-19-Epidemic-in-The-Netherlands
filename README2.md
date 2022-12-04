[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=8898978&assignment_repo_type=AssignmentRepo)
# CATALIS - Customer Clustering and Time Series Analysis

## Background

Understanding customer behaviour is paramount to a company's operations. Armed with the correct information, a company can maximize service to customers and increase profits. Some of the methods in analysing customer behaviour is customer segmentation and sales prediction.

## Objectives

We want to have machine learning models that can do customer segmentation based on their Recency; Frequency; Monetary and Length analysis (RFM), sales prediction based on past sales data, and also the data derived from those models.

## Methods

- In customer segmentation, we give RFM scores to each user and tried classifying them based on those scores using various clustering algorithm. 

- As for sales prediction, we create a time-series data of sales every month and using ARIMA algorithm to forecast future sales.

## Results

- Out of 5 clustering algorithms, we settled for KMeans algorithm that divides the customer base into 4: `Hybernating`, `New`, `Potential Loyalist` and `Loyalist`.

- Our sales prediction model forecasted that for the next 6 months item types `apparatus`, `contraption` and `widget` will have an increase in sales while `tools`, `mechanism` and `dongle` will have a decrease instead.

