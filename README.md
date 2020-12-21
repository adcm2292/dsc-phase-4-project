
# Phase 4 Project: Time Series Modeling

## Top 5 Best Connecticut Zipcodes to Invest In 



### I. Overview

I have been hired by a real-estate investment firm to help them understand:

* How real estate prices have changed overtime and,
* How to use this information to invest in areas with the most potential value increase.
* To get me started I have been provided with a dataset from Zillow Research

 #### Home values
Zillow Home Value Index (ZHVI): A smoothed, seasonally adjusted measure of the typical home value and market changes across a given region and housing type. It reflects the typical value for homes in the 35th to 65th percentile range.

 #### Housing Bubble
On December 30, 2008, the Case–Shiller home price index reported its largest price drop in its history.
The credit crisis resulting from the bursting of the housing bubble is an important cause of the Great Recession in the United States.

### II. Business Problem

What are the top 5 best zip codes for us to invest in?
Let's begin by defining best:
* We used 3 year (2015-2018) Return On Investment ratio to measure 'best'.
* After some preliminary analysis of the data, we have decided to make Connecticut our test state to optimize computational runtime.

### III. Cleaning and Obtaining Data

* Total Zipcodes in DataFrame: 14723
* Number of CT zipcodes: 124

### IV. EDA

* ROI: Based on the historic ROI (3 year and 5 year), we selected the zipcodes in top 10th percentile for highest ROI ratios.
* By doing this we narrowed down from 124 to 13 zipcodes.

![Top13Zipcodes](./Images/13zipcodes.png)

### V. Modeling

SARIMAX 

### VI. Recommendation

Invest in:

![Recommendation](./Images/recommendation.png)
