CEE 224X | Released: 180925 | Due: 181002
Name:

#### Q1: What are the “Combined” fields referring to? How do you think this information may affect our analyses?

The combined fields refer to zip codes that had fewer then the minimum customers per the California Public Utilities Commission aggregation requirements. As a results, the data from several zip codes are added together until the minimum aggregation requirements are met. The combining of zip codes spreads out the data. It provides a more general and average picture. It may be hard to spot hyperlocal trends.



#### Q2: Why are the “Average” fields likely not useful for our analyses?

Our interest is purely in the distribution of energy and gas usage in the area, not the energy habits of individuals in each zip code.



#### Q3: What type of calculations should "X" and "Y" be in the step above? Why?

Q3 Response Here (<100 words)



#### Q4: What is the total KBTU combined electricity and gas consumption in PG&E territory in 2017? What is the average annual electricity consumption per customer, and average annual gas consumption per customer?

Total Gas and Electrical Energy Consumption: 2.892 x 10^11 kBTU
Total Annual Electrical Consumption: 1.062 x 10^11 kBTU
Average Electrical Customers per Month: 4,814,478
Average Annual Electrical Consumption per Customer: 22056 kBTU
Total Annual Gas Consumption: 1.830 x 10^11 kBTU
Average Gas Customers per Month: 4,411,676
Average Annual Gas Consumption per Customer: 41484 kBTU

#### Q5: How would you explain the results of this chart to an average property owner in Northern California? What would be the value of conducting further "seasonal" analyses of energy use, compared to "year-long" analyses, and how would you define seasonal boundaries?

The chart displays the total amount of energy in the form of gas and electricity consumed by customers of PG&E in Northern California during 2017. The data is split by month. This allows identification of yearly trends.

Seasonal analysis can be valuable because they give a better idea of the peak demand. A system could be designed to deliver the total demand of gas in a year, but fail during the high demands in December and January.

Since we are currently looking an energy consumption data, it makes sense to define seasons by weather and the accompanying heating and cooling demands. Winter should be December, January, and February; the three months with the highest gas (heating) demand. Spring would be March, April, and May. Summer is June, July, and August, while Fall is September, October, and November. The seasons being the same number of months makes comparison (without normalization) easier. The seasons do not necessary need to start at the beginning of a month, but it is easier, especially for data that only gives the month (like the current set).

#### Q6: Explain your choice of formula for "avgkbtu".

The formula I chose was avgkbtu=totkbtu/(sumoftotalcustomers/12).

I chose this formula because the pivot table summed the customers from every month into the total sum. If I just used this value, I would be calculating the monthly average energy consumption per customer. By dividing the total number of customers by twelve, I essentially averaged the number of customers per month over the year.



#### Q7 Paste a publicly viewable link to your Slides.

Q7 Response Here



#### Q8 In what ways do the results in or in the vicinity of your chosen zip code validate or contradict your expectations?

Q8 Response Here (<100 words)



#### Q9 Any other reactions to completing Pass One? What was especially challenging or surprising in the workflow? How might you expand on this analysis if you had more time?

Q9 Response Here (<250 words)



#### Q10 How would you compare the experienced or apparent work involved, as well as the usefulness of the outcome, of Pass One vs. Pass Two? How would you rate the difficulty of this assignment?

Q10 Response Here (<250 words)



#### Q11 In total, how long did Assignment 1 take?

Part 1: Tech Setup: 90 minutes

Part 2: Pre-Assessment: 40 minutes

Part 3: Readings: _ minutes

Part 4: Practice Data Dive: Pass 1: _ minutes

Part 4: Practice Data Dive: Pass 2: _ minutes
