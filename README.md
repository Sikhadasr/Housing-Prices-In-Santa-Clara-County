# Housing Prices In Santa Clara County
# Objective:

We plan to explore the relationship between  population, income and  inventory on housing prices, focusing on data from the years 2013 to 2018.

## Datasets: 
Dataset 1, House Price Dataset:It consists of house price data for different counties and states.[Dataset 1 Link](https://www.zillow.com/research/data/)
Dataset 2, Inventory for Sale: The reason we want to find the number of houses available for sale is to understand the housing supply situation. When the supply is lower, the house price should go up.(https://www.zillow.com/research/data/)
Dataset 3, Income Dataset & Price Dataset for Affordability:
To explore the effect high housing prices have on people, we wanted to look at housing affordability. We have defined the affordability as the ratio between House Price to median income.
Dataset 4, Population and Housing units: To see how much the population and the number of housing units increase or decrease over the years.[Population Dataset Link](https://fred.stlouisfed.org/series/CASANT5POP),
[Housing Units Dataset Link](https://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?src=bkmk)

## Findings1: 
We found that we can forecast the house prices by changing the inventory for sale and population change. House price is positively correlated to population change and negatively correlated with change in housing units. For every 1,000 people moving to the county, the house price rises by approximately 9,500 dollars. For every 100 new houses built, the house price lowers by approximately 8,000 dollars.
![Finding 1]( https://github.com/Sikhadasr/Housing-Prices-In-Santa-Clara-County/blob/master/Images/Finding1.PNG)

[Tableau Link](https://public.tableau.com/profile/katharine.grant#!/vizhome/HousePriceandForecast/HousePriceandForecast)

## Finding 2:
We found that the house prices increase faster than median household income which suggests more and more people can't afford houses in Santa Clara County. As we increase the new housing variable, we can see that the price to income ratio reduces, meaning that the affordability improves.

![Finding 2]( https://github.com/Sikhadasr/Housing-Prices-In-Santa-Clara-County/blob/master/Images/Finding2.PNG)

[Tableau Link](https://public.tableau.com/profile/katharine.grant#!/vizhome/Affordability_6/Affordability)

Finding 3:
While housing units have increased every year, the rate of increased housing has not been consistent. Meanwhile, the net migration to Santa Clara County, while still positive, has reduced consistently over the last five years. While we do not want to make any conclusions with regards to causality, this may show how a lack of increased, and therefore affordable, housing has led to fewer people choosing to move to Santa Clara County

![Finding 3](https://github.com/Sikhadasr/Housing-Prices-In-Santa-Clara-County/blob/master/Images/Finding3.PNG)



[Tableau Link](https://public.tableau.com/profile/katharine.grant#!/vizhome/HousingandMigration/PopandUnits)

##  [Final Dashboard Link](https://public.tableau.com/profile/katharine.grant#!/vizhome/IncreasedHousingWillReduceOurHousingCrisis/FinalDashboard)
