# Bertelsmann Arvato: Customer Segmentation and Aquisition

This repositiory contains the code and the report for the "Capstone Project - Arvato Customer Segmentation".

## Project overview

In this project I will be analysing data about the general population of Germany along with data about existing customers in Bertelsmann Arvato in order to determine which members of the general population are the most likely to respond to mail-outs.  To do this I will use unsupervised learning techniques to find clusters of the customer data and compare these clusters with the general population.  Then I will create a machine learning model which will be used to determine whom are most likely to respond to the mail-out.

## Data Description 
This section contains a brief description of the data used in this project. Due to the terms and conditions this data will not be shared in this repository
* Udacity\_AZDIAS\_052018.csv: Provides the demographics for the general population. Contains 891211 entries x 366 features.
* Udacity\_CUSTOMERS\_052018.csv: Provides the demographics for customers of a mail-order company. Contains 891211 entries x 366 features.
* Udacity\_MAILOUT\_052018\_TRAIN.csv: Provides the demographics for individuals whom were targeted by a marketing campaign. Contains 42932 entries x 366 features.
* Udacity\_MAILOUT\_052018\_TEST.csv: Provides the demographics for individuals whom were targeted by a marketing campaign. Contains 42833 entries x 366 features.

## Technical overview
The following steps have been performed for this project

* Data exploration and cleaning
* PCA analysis
* Dimensionality reduction
* Clustering
* Univariate feature selection
* Supervised machine learning
* Model Evaluation
* Predictions on test set

## Requirements

In order to install the python packages used for this project run the following command within the terminal and have jupyter notebook installed:

`pip install numpy pandas matplotlib seaborn scikit-learn xgboost`

For the complementary blog post click <a href=https://medium.com/p/447d1d14741f/edit>here</a>
