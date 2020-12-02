## Goal :
To perform Attribution Modelling  for Criteo Attribution Bidding Dataset and to optimize the Budget Allocation for various Marketing campaigns.

## Attribution Modeling :
Attribution modeling is a framework for analyzing which touchpoints, or marketing channels, receive credit for a conversion.Each attribution model distributes the value of a conversion across each touchpoint differently. 
A model comparison tool allows you to analyze how each model distributes the value of a conversion. 

## Dataset Preparation :
Data Sampling • Balancing Dataset • Deriving additional columns from existing datasets 

## Types of Marketing Models we will be implementing :

Single-touch attribution models assign 100% of conversion credit to one marketing touchpoint. Even if a customer saw 20 ads before converting, single-touch attribution will determine that only 1 of the 20 ads deserves conversion credit.
Single-touch attribution models are easy to implement because of their low level of complexity. They're also the most popular attribution models because of their historical tie to Google Ads
The models are
1).First Touch Attribution (FTA)
2).Last Touch Attribution (LTA)

Multi-touch attribution is best described in contrast to its counterpart, single-touch attribution.
In order to divide the revenue credit for a sale properly, multi-touch attribution uses weighted modeling in order to allocate credit to the plethora of influential channels, campaigns, keywords, and touchpoints.
Weighted touchpoint modeling assigns a percentage of the revenue credit for a customer to an array of touchpoints, as defined by the respective multi-touch attribution model chosen by the organization.
The models are:
1).Logistic Regression Model
2).Time-decay Attribution Model
3).Linear Attribution Model
4).U-Shaped Attribution Model

We have implemented 6 models to compare and see which works best for us and validate our claim using Simulation algorithm to optimize the Budget Allocation using the history data to calculate Return on Investment.

## Dashbaord :
We also create a Dashbaord using Voila to summarize our insights and model outcomes.

## CLAAT Document :
https://codelabs-preview.appspot.com/?file_id=16_qjTsxV4dfyPo2Ni60gBfFIXtjn0Sk-IKDV99dqyTg#17
