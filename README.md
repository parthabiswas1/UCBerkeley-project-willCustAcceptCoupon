# UC Berkeley ML/AI project: Will Customer Accept the Coupon ?
(Data analysis and visualization with python, pandas, dataframe, matplotlib, seaborn) \
Project location: https://github.com/parthabiswas1/UCBerkeley-project-willCustAcceptCoupon 

## Problem Statement

A survey was done with drivers of differnt ages, gender, income, status, weather, time and other parameters to find out if they will accept coupons to bars, resturants, takeaways, coffee houses etc. the project aims to identify drivers who are nore likely to accept coupons than others.

## Source of data

The data is from the UCI Machine Learning Repository and was collected via a survey on Amazon Mechanical Turk. Data attributes consists of Gender, Age, Marital status, Children, Education,Occupation, Income and scenaro details like frequncy of visits to bars, coffee houses, takeaways, resturants, driving direction and purpose, weather and time of day.

## Approach

- Observe the data and formulate a data cleaning strategy
- Execute the data cleaning strategy
- Do data analysis and visualization to identify drivers who are more likely to accept coupons than others
- two coupon groups were selected for analysis - **Bar coupons** and **Coffee House** coupons

Below are a summary of observations and findings.

## Obsevations - **Bar coupons**

- Drivers who go to Bars more frequently accept more bar coupons (76%)
- Drivers above 25 who go to Bars, accept more bar coupons (68.98%)
- Drivers who have no kids and is not in farming or forestry accept more bar coupons (70.94%)
- Drivers who are not economically well off, goes to affordbale resturants and earns below 50K accept more coupons (61.15%)
- Only **41%** of Bar coupons overall were accepted which is low. This could mean  that the coupon appeal is to a targeted group - younger, no kids, lower income, jobs in more urban settings and frequent Bar goers. 

## Recommendations

- Create a marketing campaign targeting young adult drivers who frequently go to bars, are not economically well off, do not have kid and are employed in more urban settings.
- Make the bar coupon more attractive to low income earners by increasing the discount rate or by combining it with resturant discount offers.

## Obsevations - **Coffee House coupons**

- Frequent coffee house visitors (1 or more per month) accepted more coupons(64.73% - 68.24%)
- Morning coffee house visitors (10AM) have a higher coupon acceptance rate (63.43%).
- Irrespective of marital status, a high rate of acceptance(44.4% - 65.6%) among drivers who go to coffee houses in the morning (10AM).
- Highest rate of acceptance (76.9%) is by divorced drivers who go to coffee houses late in the evening (10PM)
- Drivers who have no urgent place to go in the morning (10AM) or late evening (10PM) have higher coupon acceptance rates (63.4% - 68.7%)
- Young single females divers with some college earning less than $12.5k who went to coffee houses in the afternoon accepted coffee coupons at the highest rate
- Overall **49.5%** of coffee house coupons were accepted. This shows that close to majority of the  drivers were interested in Coffee House coupons</li>

## Recommendations
- Run a targeted marketing campaign focused on young female drivers, drivers who frequented coffee houses often and drives to nowhere particular and divorcees who go to coffee houses late in the evening.

