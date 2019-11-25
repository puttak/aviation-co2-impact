# Aviation and global carbon emissions

## Abstract

Talking about being "eco responsible" is the trend. We are told by newspapers, scientists, social medias and Greta that we should consume less, or at least make efforts. Since in our team, we are true students, we were already talking about the next summer holidays. In the middle of the discussion, we suddenly became worried about a particular aspect of the holidays.

This is why, for this research, we decided to focus on planes. Indeed, planes are subject to more and more taxes, and are criticized for being extra pollutant. But is it really true ? In our analysis, we are going to compute and measure different metrics related to CO2 emissions of airplanes and airlines. The outcome should help us to be aware of the impact of our travel decisions. For example: "Does the choice of the airline company have an impact on my carbon footprint?".

## Research questions

We chose four questions that will help us to approach our research theme, which is the role of aviation in the global carbon emissions.

### Questions

## Initial questions

* What role does aviation play in the global carbon emissions?
  * Is there significant difference in CO2 emissions between different airlines?
  * Is there an ideal distance to travel to reduce our CO2 emissions per km?
  * Are airplanes usually on time? Does this have an impact on CO2 emissions?
  
## Updated questions - **NEW**

During our analysis, we noticed that it could also be interesting, in addition to the airlines, to focus on carbon emissions by country. We also spent some time trying to look at delays, but we realized that it would produce irrelevant results, since aircrafts tend to catch up departure delays on route, leading to on-time arrivals. It would have been complicated calculating the increase of fuel burn, due to the dependance of multiple variable and the specificity of every aicraft.

* What role does aviation play in the global carbon emissions?
  * Is there an ideal distance to travel to reduce our CO2 emissions per km?
  * Is there significant difference in CO2 emissions between different airlines?
  * ~~Are airplanes usually on time? Does this have an impact on CO2 emissions?~~
  * **Is there a significant difference in CO2 emissions between different countries ?**
  * **As swiss travellers, is there better destination according to the CO2 emissions ?** 

## Datasets

Even though the aviation industry is quite protective of its data, we were able to find several open source datasets that will help us to achieve our goal:

* https://en.wikipedia.org/wiki/Fuel_economy_in_aircraft

By scraping this page, we will infer the following informations: airplanes average seat number and fuel burn (CO2)

* ~~https://github.com/lukes/ISO-3166-Countries-with-Regional-Codes/blob/master/all/all.csv~~

~~ISO-3166 country code dataset~~

* https://openflights.org/data.html

List of routes (up to 2014) and planes models

* ~~https://www.transtats.bts.gov/databases.asp?Mode_ID=1&Mode_Desc=Aviation&Subject_ID2=0~~

~~Delay information of the US aviation industry. Name of the dataset is Airline On- Time performance data~~

*We did not use this data because we are not looking at whether aircrafts are on time or not anymore.*

* https://opensky-network.org/data/impala

Historical data of aircrafts. Dataset partners by Swiss confederation, Bern university, Oxford University

**NEW** 

* https://www.planespotters.net

All aircrafts models by airline

### Annexes

These annexe sources, will be used either for secondary questions or further analysis:

* https://ourairports.com

List of airports in the world

* https://developers.google.com/maps/documentation/

Google maps API (could be used for car comparison)

* https://github.com/juliuste/flix

Flix bus API (could be used for bus comparison)

* https://dev.blablacar.com/hc/en-us/articles/360009002899--API-documentation

BlaBla car API (could be used for car sharing comparison)

## Internal milestones up until milestone 2

* Data wrangling:
  * Explore the data
  * Fetch clean and check integrity of datasets (pre-processing)
* Merge datasets and compute anwsers to questions:
  * Check feasibility of unanswered questions 
* Analysis of obtained results
* Choose and test tools for visualization of results

## Internal milestones up until milestone 3

* Week 12:
  * 
* Week 13:
  *
* Week 14: 
  *
* End of semester:
  * Fixing bugs

## Questions for TAs

* None for now
