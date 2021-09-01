# Housing_Market_analysis
Downloaded median rents, home values information from zillow research data www.zillow.com/research/data/

•	Plotted home values, price to rent ratios across years for 1/2/3 bedroom's separately.\
•	Noticed that the price/rent ratio for 3 bedroom houses has always been historically lower relative to 1 bedroom.\
•	Studied the relationship between growth in home values & preceding period price to rent ratios extensively.\
•	Interestingly, price/rent ratio doesn't necessarily correlate with size of the city.\
•	There are very large such as Chicago where home prices appear cheap relative to their rents.\
•	Observed that there are nearly 2000 zip codes where median rents have decreased between 2010 and 2017 (in absolute terms).

Predicted percentage growth (yearly) in home values with Zillow variables & following external data:-\
•	County unemployment rate www.kaggle.com/jayrav13/unemployment-by-county-us \
•	State GDP data www.bea.gov   \
•	30Y mortgage rates fred.stlouisfed.org/series/MORTGAGE30US    

Modeling results:-\
•	Linear Regression R2 of 38% and an RMSE of 6.5%\
•	Random Forest R2 of 75% and an RMSE of 4.2%\
•	Logistic Regression accuracy of 72% (Predicted >5% growth Y/N)
