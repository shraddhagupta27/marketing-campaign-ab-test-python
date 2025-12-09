# marketing-campaign-ab-test-python

# Marketing Campaign Analytics
A data-driven A/B testing project comparing Facebook Ads vs Google AdWords performance using Python, hypothesis testing, and Bayesian modeling to drive ROI-focused budget recommendations.

## Overview
This project analyzes one year of digital advertising data to rigorously compare the performance of Facebook Ads and Google AdWords.  
It uses statistical A/B testing, Bayesian modeling, and simple predictive modeling to answer a core business question: Which ad platform delivers better conversion efficiency and should receive more budget?

## Problem Statement
Marketing teams often distribute budget across multiple ad platforms without statistically validating which channel performs better.  
Raw metrics like clicks and impressions don’t tell the full story and can be misleading without proper analysis.

Goal: 
Use data and statistical methods to determine whether Facebook or Google AdWords is more effective in terms of:
- Conversion Rate (CVR)  
- Click-Through Rate (CTR)  
- Cost Per Click (CPC)  
- Cost Per Conversion / ROI  
And translate this into clear, actionable budget recommendations.

## Dataset
- Source: Kaggle 
- Columns:
  - `Date`
  - `Facebook Ad Views`, `Facebook Ad Clicks`, `Facebook Ad Conversions`
  - `AdWords Ad Views`, `AdWords Ad Clicks`, `AdWords Ad Conversions`
  - `Cost per Facebook Ad`, `Cost per AdWords Ad`
  - Metrics like CTR, CVR, CPC (as strings/percentages)

## Tools & Technologies
- Language: Python  
- Libraries:
  - Data: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Statistics: `scipy`, `statsmodels`
  - Modeling: `scikit-learn`

## Methods
1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. A/B Testing (Frequentist)
4. Bayesian A/B Testing
5. Predictive Modeling - Linear Regression

## Key Insights
- Facebook had a substantially higher conversion rate than Google AdWords.  
- Daily/weekly analysis indicated certain months and weekdays with:
  - Lower cost per conversion
  - More efficient performance
- A regression model showed:
  - Strong relationship between clicks and conversions, especially for Facebook.


