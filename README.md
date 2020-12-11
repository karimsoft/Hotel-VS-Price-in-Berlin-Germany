# How is Hotel's price in Berlin?

# Information and metrics for hotels in Berlin ,Germany.

## libraries used in the analysis.
- numpy as np
- pandas as pd
- matplotlib.pyplot 
- seaborn
- sklearn.linear_model import LinearRegression
- sklearn.model_selection import train_test_split
- sklearn.metrics import r2_score, mean_squared_error

## Questions
Question 1:- If more we go north, the lower price?

Question 2:- What is expected the price for most commonly used in the far south for every room type?

Question 3:- Increasing the number of days available per year causes price increases ?

Question 4:- when minimum nights is small then the price increases?

## Clean Data
-Delete fields that are not valid in price and number of occurrences.

-Room type update data Categorical.

-Convert Data Categorical to fields.

-Convert latitude from float64 to int.

## Summary

-When we go north, the lower price and Hotel Count.

-The expected price for most commonly used in the far south is 61.3 Euro from Entire home and 16.2 Euro from Shared room.

-Increasing the number of days available per year causes price increases .

-Not effect when the minimum nights is small the price not decreases.

## publish
https://karimsoft.medium.com/karimsoft-hotel-vs-price-in-berlin-germany-91f7630bf082
