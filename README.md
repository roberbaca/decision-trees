# Optimizing Deposit Subscription Predictions with Decision Trees and Economic Metrics

This repository contains a subscription predictions and economic metrics of a bank institution with decision trees, implemented in R.

## Project Overview

We will use the bank dataset from the liver package, which must be installed from CRAN if not already available.

The data is related to direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact with the same client was required to determine whether the product would be subscribed. The classification goal is to predict whether a client with a given profile will subscribe to a term deposit.

Decision trees will be used to predict the target variable “deposit” in the bank dataset from the liver package. The approaches are:

Decision trees without balancing

- Upsampling

- Downsampling

- ROSE balancing

- Hybrid balancing

- No balancing but with hyperparameter tuning

The main metrics of each model will be compared, along with economic evaluation, to choose the model that fits best and maximizes profit.

## Technologies and libraries used

- R
- liver
- rpart
- rpart.plot
- tidyverse
- ROSE
- Caret
- ggplot2  

## Project Report

You can view the full analysis here: [Optimizing Deposit Subscription Predictions with Decision Trees and Economic Metrics](https://roberbaca.github.io/decision-trees)

## How to Run

1. Clone the repo  
2. Open the RMarkdown or R script file  
3. Run the Decision Trees code to reproduce the results (Rmd file)

## Links

- [Kaggle Notebook](https://www.kaggle.com/code/robertonicolsbaca/decision-trees-in-r-banking-institution)

---

© 2025 Roberto Baca
