# Time Series Phase 4 Project

**Authors**: Matthew Gayanelo

## Business Problem

Identify the top 5 best Real Estate investments by Region

## Data


Source: Zillow
Analytical Prupose: Time Series Analysis
Target Variable: Growth in 1 year
Target Variable Use: Determine whether or not a RegionID is a good investment


***

## Methods

1. Initial Analysis of Data (Time Series Decomposition etc.)
2. Generalizable SARIMAX Model
4. Identify top 10 Growers
5. Establish SARIMAX Accuracy per top 10 Region
6. Select top 5 most accurate RegionIDs with greatest growth potential
6. Optimize Accuracy with Neural Network

## Results

Following Region IDs were identified as top growers:

[99877, 73177, 66015, 60706, 91259, 60642, 92306, 399593, 66828, 70395]

Following Region IDs were identified as most accurate with Sarimax:

[73177, 91529, 66015, 60706, 399593]

Use of RNN LSTM Networks for individual forecasting proved to be even more accurate, reuslting in ~50% less Mean Absolute Error.

### Proposition

Invest in [73177, 91529, 66015, 60706, 399593] and track changes to potential growth via updated Neural Net Forecasts
