CEE 224X | Released: 180925 | Due: 181002
Name:

#### Q1: What are the “Combined” fields referring to? How do you think this information may affect our analyses?

The combined fields refer to zip codes that had fewer then the minimum customers per the California Public Utilities Commission aggregation requirements. As a results, the data from several zip codes are added together until the minimum aggregation requirements are met. The combining of zip codes means some zip codes will appear to use zero energy, while others show as using more energy than they actually would alone. This adds uncertainty into our data, especially the total kBTU for each zip code, and could impact our analysis.

#### Q2: Why are the “Average” fields likely not useful for our analyses?

The average is computed separately for electricity and gas customers. We want an average that considers the total energy consumption of each customer. There is likely some overlap between gas and electricity customers that would not be represented if we just manipulated the average fields.

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

Since we are currently looking an energy consumption data, it makes sense to define seasons by weather and the accompanying heating and cooling demands. Winter should be December, January, and February; the three months with the highest gas (heating) demand. Spring would be March, April, and May. Summer is June, July, and August, while Fall is September, October, and November. The seasons being the same number of months makes comparison between seasons (without normalization) easier. The seasons do not necessary need to start at the beginning of a month, but it streamlines sorting data, especially for data that only gives the month (like the current set).

#### Q6: Explain your choice of formula for "avgkbtu".

The formula I chose was avgkbtu=totkbtu/((totalelectriccustomers+0.05*totalgascustomers)/12).

I multiplied gas customers by 0.05 because the electric customers and gas customers overlapped by 95%. Most gas customers likely consume electricity as well. I divided the totals from the pivot table to twelve to prevent counting the customers in each month. If I just used the pivot table value, I would be calculating the monthly average energy consumption per customer. By dividing the total number of customers by twelve, I essentially averaged the number of customers per month over the year.

#### Q7 Paste a publicly viewable link to your Slides.

https://docs.google.com/presentation/d/1J0iFxFkLxBkn573mUC-p59ciFaQXL1Dprbcy-ciXRrM/edit?usp=sharing

#### Q8 In what ways do the results in or in the vicinity of your chosen zip code validate or contradict your expectations?

I was surprised by the variability in average annual kBTU per person found even within the small area of Stanford, Palo Alto, and Mountain View. I did not expect to see such variation in areas that feel so homogeneous.

I had expected Stanford to use a relatively large amount of residential energy per person. Students often do not have full times jobs, and use their residences for studying or resting during the day while residents of areas like Menlo Park may be a work, contributing to commercial energy use.

#### Q9 Any other reactions to completing Pass One? What was especially challenging or surprising in the workflow? How might you expand on this analysis if you had more time?

I was surprised by how much thought can go into an equation that seems as simple as taking an average. It was a good reminder to put thought into how I manipulate data in the future.

One thing I did not catch until after I had completed the analysis was the month of September was included in both the Quarter 3 and Quarter 4 reports. If I had more time I would go back and correct the data so September was not double counted. This would lower both the total and average annual kBTU.

The combination of several zip codes feels like it is skewing our data. I would like to find out which zip codes were combined, so the data could be displayed on all combined zip codes in the map.

#### Q10 How would you compare the experienced or apparent work involved, as well as the usefulness of the outcome, of Pass One vs. Pass Two? How would you rate the difficulty of this assignment?

It is hard to me to talk about the relative work between Pass One and Pass Two, I only copied the code and changed the file references for Pass Two. As far as I could tell, there was not too many lines of code. The output of Pass Two looks more professional than the output from Pass One. The output from Pass Two was also easier to interact with. My computer was a little slow when working with ArcGis.

I would rate the difficulty of the assignment as moderate. The instruction were clear and there was not much high level thinking required to generate the map. The process was tedious, especially installing all the new programs and learning how to work with them. For example, I am still not sure how GitHub desktop interfaces with GitHub.com.

#### Q11 In total, how long did Assignment 1 take?

Part 1: Tech Setup: 90 minutes

Part 2: Pre-Assessment: 40 minutes

Part 3: Readings: _ minutes

Part 4: Practice Data Dive: Pass 1: 330 minutes

Part 4: Practice Data Dive: Pass 2: 30 minutes

Peer Review: I found it really insightful that you noticed the overlap between the electricity and the gas customers. It was also clever that in your seasonal analysis option, the different seasons are the same number of months as that would make comparison easier.I divided it up a different way but having the same number of months in a season is efficient. 
