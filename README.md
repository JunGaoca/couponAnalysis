
# Coupon Acceptance Analysis Project

## Overview

Imagine driving through town and receiving a coupon on your phone for a nearby business. Would you take a detour to use it, save it for later, or ignore it altogether? What factors, such as location, timing, or personal preferences, influence your decision?

This project is to apply exploratory data analysis, statistical summarization, and visualization techniques to address questions about coupon acceptance. By analyzing and visualizing data, the project aims to uncover patterns and key factors influencing drivers’ decisions to accept or reject coupons. 


## GitHub Repository Structure

- https://github.com/JunGaoca/customerCouponAcceptance
- Jupyter Notebook: https://github.com/JunGaoca/customerCouponAcceptance/blob/main/coupon-analysis.ipynb
- Data: https://github.com/JunGaoca/customerCouponAcceptance/blob/main/data/coupons.csv


## Dataset

The dataset is from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. Participants were presented with hypothetical driving scenarios and asked whether they would accept a coupon. Key details include:

- **Coupons types**: Bar, coffee house, carry out & take away, less expensive restaurants (under $20), and more expensive restaurants ($20–$50).
- **Labels**: `Y = 1` (coupon accepted) and `Y = 0` (coupon not accepted).
- **Attributes**: Covers demographics and contextual factors such as  age, income, marital status, weather, time of day, education, occupation, passenger type, destination, and more.


## General Findings

Carryout & takeaway coupons and those for cheaper restaurants have the highest acceptance rates, indicating strong customer preference for these options. Bar coupons, on the other hand, have the lowest acceptance rates. Coffee house coupons show a nearly equal split in acceptance, with a rate of 49.57%.


## Findings about Bar Coupons
Drivers are twice as likely to accept a bar coupon if they:
1. Visit bar more than three times a month.
2. Visit bar more than once a month and are over 25 years old.
3. Visit bar more than once a month, are not employed in farming, fishing, or forestry ,and have no child passengers.

Overall, frequent bar-goers are significantly more inclined to take advantage of bar coupons compared to other groups.

In contrast, individuals with lower incomes or those who frequently dine at inexpensive restaurants tend to show little interest in bar coupons.


## Findings about Coffee House Coupons

1. Drivers are more inclined to accept coffee house coupons under specific conditions:
	- Age: Younger drivers under 21 are the most frequent coffee consumers, while individuals aged 50+ consume the least.
	- Marital Status: Singles and divorced individuals show higher coffee consumption compared to others.
	- Timing: Coffee consumption peaks around 10 AM and 2 PM.
	- Companionship: Drivers accompanied by friends or partners are more likely to accept coffee house coupons.
	- Purpose of Travel: Drivers without an urgent destination are more open to accepting coupons.
	

2. Neutral Factors:
	- Weather: Has minimal influence on coupon acceptance.
	- Gender: Has little to no effect on coupon acceptance rates.
	- Income: Acceptance rates remain consistent across income groups, typically around 50%, showing negligible influence on coffee coupon acceptance.


## Tools and Technologies

- **Programming Language**: Python
- **Libraries**: pandas, numpy, matplotlib, seaborn
- **Environment**: Jupyter Notebook


