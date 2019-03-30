# PROJECT : Dive Into Internet Advertisements Data Set. 


### Table Contents:

| Description | README |
| ------ | ------ |
| Getting Started|[GOTO](https://github.com/vinayakn/Bulding-Adblocker-Model#getting-started)|
| Installation | [GOTO](https://github.com/vinayakn/Bulding-Adblocker-Model#installation)|
| Motivation for the project | [GOTO](https://github.com/vinayakn/Bulding-Adblocker-Model#Motivation-for-the-project) |
| Files in the repository  | [GOTO](https://github.com/vinayakn/Bulding-Adblocker-Model#Files-in-the-repository) |
| Summary of the results  | [GOTO](https://github.com/vinayakn/Bulding-Adblocker-Model#Summary-of-the-results-) |
| Article On Medium | [GOTO](https://github.com/vinayakn/Bulding-Adblocker-Model#article-on-medium)|
| Acknowledgements | [GOTO](https://github.com/vinayakn/Bulding-Adblocker-Model#licensing-authors-acknowledgements)|


## Getting Started:

In This Project with Advertising data we will build Supervised ML predictive models to see how accurately they can detect whether an image is an advertisement ("ad") or not ("nonad"). The dataset for this project originates from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/internet+advertisements).
Internet Advertisements Data Set consists total 3279 Records(2821 nonads, 458 ads). Datasets were investigated before we do any preprocessing.
Prepare Data: This Includes data cleaning, filling NAN value, one-hot encoding preprocessing. Please refer to Preprocessing for detail.


## Installation:

Anaconda distribution of Python Version 3


## motivation for the project:

**motivation behind this project was to answer the below question by understanding and exploring data:**

1. How to build vary basic simple Prediction model, which will identify Images on website, is AD or (Not AD)
2. We will also explore the challenges associated with building Model
3. How we can tackle those challenges?

## Files in the repository:

* Ad.csv
* Ad_OR_Not_Ad_Prediction_Model.ipynb
* README.Md

## Summary of the results :<br/>

**FOLLOWING ARE THE TRAINING & TESTING SCORES:** <br/>

**Data Modeling:** In this Entire Project we have used Logistic Regression Classification Algorithm. Used GridSearch with 5 folds validation to find best parameter for Classifier. 
How to handle unbalanced data discussed Please refer to Training & Testing for detail. 

Feel free to try differnet cv's ,Optimizaters, Algorithms & Models etc as you would like!<br/>

|SNO|Model - Logistic Regression	|Accuracy	|Precision	|Recall	|F1 Score	|AUC  |
|---|----------------------------|-----------|-----------|-------|-----------|-----|
|0	|Unbalanced Training Data with CV	|0.969841	|0.981667	|0.983587	|0.982624	|0.978826|
|1	|Unbalanced Testing Data with CV	|0.804988	|0.957660	|0.789441	|0.865258	|0.924146|
|2	|Balanced Down Sampled Training Data	|0.920117	|0.901411	|0.937570	|0.918870	|0.974084|
|3	|Balanced Down Sampled Testing Data	|0.868421	|0.849945	|0.919192	|0.876766	|0.914395|
|4	|Balanced Up-Sampled Training Data	|0.982353	|0.991589	|0.973014	|0.982190	|0.996710|
|5	|Balanced Up-Sampled Testing Data	|0.934418	|0.915866	|0.962735	|0.937470	|0.974488|

## Article On Medium

The main findings of the code can be found at the post available [here](https://medium.com/@vinayak_navale/are-you-fed-up-with-too-many-ads-on-websites-mobile-80df2f1d3175). if you like this article feel free to share and clap!! :)<br/>

## Licensing, Authors, Acknowledgements:

The dataset for this project originates from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/internet+advertisements). 
Title of Database is Internet advertisements and The datset Creator & donor is Nicholas Kushmerick.,Otherwise, feel free to use the code here as you would like!
