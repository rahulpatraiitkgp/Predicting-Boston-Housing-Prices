# Predicting-Boston-Housing-Prices
Machine Learning Engineer Nanodegree Project Udacity

# Kaggle Competition Link:
https://www.kaggle.com/vikrishnan/boston-house-prices

# Disclaimer:

As a CS minor student of IIT Kharagpur and a long-time self-taught learner, I have completed many CS related MOOCs on Coursera, Udacity, Udemy, and Edx. I do understand the hard time you spend on understanding new concepts and debugging your program. Here I released these solutions, which are **only for your reference purpose**. It may help you to save some time. And I hope you don't copy any part of the code (the programming assignments are fairly easy if you read the instructions carefully), see the solutions before you start your own adventure. This Project is almost one of the simplest Machine Learning Project I have ever taken, but the simplicity is based on the fabulous course content and structure. It's a treasure given by Udacity team.

## Introduction

This repo contains all my work for Project 2 of Udacity's Machine Learning Basic Nanodegree Program. In this project, I applied basic machine learning concepts on data collected for housing prices in the Boston, Massachusetts area to predict the selling price of a new home. I first explored the data to obtain important features and descriptive statistics about the dataset. Next, I properly split the data into testing and training subsets, and determine a suitable performance metric for this problem. Then I analyzed performance graphs for a learning algorithm with varying parameters and training set sizes. This enabled me to pick the optimal model that best generalizes for unseen data. Finally, I tested this optimal model on a new sample and compare the predicted selling price to my statistics.

# Project Description
The Boston housing market is highly competitive, and you want to be the best real estate agent in the area. To compete with your peers, you decide to leverage a few basic machine learning concepts to assist you and a client with finding the best selling price for their home. Luckily, you’ve come across the Boston Housing dataset which contains aggregated data on various features for houses in Greater Boston communities, including the median value of homes for each of those areas. Your task is to build an optimal model based on a statistical analysis with the tools available. This model will then be used to estimate the best selling price for your clients' homes.

The dataset for this project originates from the UCI Machine Learning Repository. The Boston housing data was collected in 1978 and each of the 506 entries represent aggregated data about 14 features for homes from various suburbs in Boston, Massachusetts. For the purposes of this project, the following preprocessing steps have been made to the dataset:

- 16 data points have an 'MEDV' value of 50.0. These data points likely contain missing or censored values and have been removed.
- 1 data point has an 'RM' value of 8.78. This data point can be considered an outlier and has been removed.
- The features 'RM', 'LSTAT', 'PTRATIO', and 'MEDV' are essential. The remaining non-relevant features have been excluded.
- The feature 'MEDV' has been multiplicatively scaled to account for 35 years of market inflation.

