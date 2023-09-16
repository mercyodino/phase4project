# phase4project

# TIME SERIES MODELLING FOR REAL ESTATE USING ZILLOW DATA 

## INTRODUCTION
Real estate is real property that includes land and anything permanently attached to it or built on it, whether natural or man-made.In real estate there are five main categories which include residential, commercial, industrial, raw land, and special use.
Investing in real estate includes purchasing a home, rental property, or land. Indirect investment in real estate can be made via REITs or through pooled real estate investment.

Real estate encompasses the land, plus any permanent man-made additions, such as houses and other buildings. Any additions or changes to the land that affects the property's value are called an improvement. In most times improvements are for the better and also increases its market value. The total capital and labor used to build the improvement represent a sizable fixed investment. Though a building can be razed, improvements like drainage, electricity, water and sewer systems tend to be permanent. Hence you get the rights inherent to its ownership and usage.

## PROBLEM STATEMENT

You are a consultant for a Zillow real-estate investment firm. As a consultant, your work is to help clients who are buyers or renters to get which property is best to invest in and in which zipcodes or region codes.

### Defining a metric of success
A model will be considered successful when it's able to predict the best zip codes to invest in as per their profit/return on investment (ROI)

## OBJECTIVES 

### MAIN OBJECTIVE
* To develop a time series model that would predict the top five best zipcodes to invest in

### SPECIFIC OBJECTIVES
* To look at the profits it brings over a period of time

* To look at the RMSE of the model to see how well your model is performing 

* To look at which zip codes/ region codes are good to invest in.

## DATA UNDERSTANDING
This analysis will be using data from Zillow dataset that is from the Zillow. The dataset has 14723 rows and 272 columns. The dataset includes:- RegionID,	RegionName,	City, State, Metro,	CountyName, and SizeRank.

* RegionID: Represents a unique ID for each region.
* RegionName: Represents the name of the region/ also the zipcode	
* City: The city where the region is located.
* State:	State where the region is located.
* Metro:	It is the metropolitan area where the region is located 
* CountyName: The name of the county where the region is located.
* SizeRank: Size of the region compared to other regions in the dataset.	
* 1996 up to 2018: Represents the median home price for the region in months and years.

## MODELLING
From the Zillow dataset i have used ARIMA/SARIMA models and also calculated the RMSE and MSE in order to see how well the model is performing. 

## CONCLUSION
From the Zillow Real Estate database, I have concluded that :-

1. Real estate is being appreciated 

2. There is high return  on investment in real estate

3. There are zipcodes to invest in that are at the top 5 Regioncodes 

4. The model created is has a 0.95 confidence interval.


## RECOMMENDATIONS

1. Real estate is being appreciated - From the data we have seen that , more and more people are appreciating real estate in that people are looking to mostly buy homes and other than being tenants.

2. There is high return on investment in real estate - From the dataset we have seen that the return on investment has risen over  the years and it keeps rising.

* This means that people are buying homes and can either rent them out to bring them more money using the monthly pay or selling it after some time and making a profit from the initial pricing that they had bought it as.

* This can also mean that some improvements have been done to the property hence increasing its value.

3. There are zipcodes to invest in that are at the top 5 Regioncodes - From the zillow data that we have seen which regioncodes are the top fives that have boon invested on in terms of real estate .The top 5 regioncodes are the best to invest in .  
