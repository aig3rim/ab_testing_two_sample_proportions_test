# A/B testing with binary data: Two sample proportions z-test

## Introduction
This repository is for a Medium blog post "A/B testing with binary data: Two sample proportions test for a marketing campaign". The notebook shows how to apply hyphothesis testing to understand whether a campaign was statitically significant or not for a situation, when the input is binary data.

## Motivation
As a data scientist, I find that hyphothesis testing is an important tool for data-driven decision making. So I decided to deepen my knowledge in the field and run some experiments using publically available data... (rewrite)

## Getting started
To run the notebook you need the following packages:
* pandas
* numpy
* math
* statsmodels
* scipy
* matplotlib

## Dataset 
I am using a dataset of a marketing campaign from [Kaggle](https://www.kaggle.com/faviovaz/marketing-ab-testing).
The idea of the dataset is to analyze the groups, find if the ads were successful, how much the company can make from the ads, and if the difference between the groups is statistically significant.

## Summary
* The two-sample proportions test allows you to compare proportions of two user groups, which is used in marketing to evaluate a difference in conversion rates/other binary metrics for two user groups
* The result shows that there is a statistically significant difference between the control and treatment groups, which means that the ad was successful
* Along with the test, we learned how to calculate a sample size for the two-sample proportions test and got to know about the difference between the hypothesis and A/B tests.
