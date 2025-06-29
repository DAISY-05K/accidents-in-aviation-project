##  ACCIDENTS IN AVIATION DATA ANALYSIS
## INTRODUCTION
 According to this article[article] ('https://www.icao.int/Meetings/FutureOfAviation/Pages/default.aspx') the air transport industry is expanding and the future of aviation is a bright one. Aviation sector is growing faster and will continue to grow,if this growth path is achieved by 2036 the air transport industry will then contribute 15.5 million in direct jobs and $1.5 trillion of GDP to the world economy.
 
 As good as that sounds the aviation industry also faces it's own fair share of challenges which include accidents due to the condition of the aircraft and the climate change and sustianability among others.
 
 Basic understanding of such factors and how they affect the Aviation industry will give us insists on what to invest in and how to navigate through such factors and challenges.
 This Analysis is going to look at venturing  into this industry and what air crafts have a low risk of investment.

  ## Tableau presentation, follow to this [link](https://public.tableau.com/app/profile/daisy.thomas8647/viz/ACCIDENTSINAVIATIONANALYSIS/ACCIDENTSINAVIATIONANALYSIS?publish=yes)

 ##  Non-technical presentation, refer to this [link](presentation.pdf)
 ## OBJECTIVES
* DATA UNDERSTANDING
* DATA CLEANING
* EXPLANATORY DATA ANALYSIS(EDA)
* DATA VISUALIZATION
* USE FINDINGS TO DERIVE RECCOMENDATIONS AND NEXT STEPS TO FOLLOW
  ## BUSINESS UNDERSTANDING
Before we venture into the Aviation industry we need to have an indebt analysis on how accidents due the different weather conditions and the type of aircraft affect the market and the risk involved in investing in the industry and by following trends over time and analyzing this trends and data, We get to answer the following questions:

 * How do different weather patterns influence accidents 
 * Difference in aircraft operations between the private and public enterprise
 * Air crafts with a high and low risk of investment 
 * The safety of air transport with time 
 * The future of the Aviation sector## 1. DATA UNDERSTANDING
 For this research, we collected data from Kaggle on the National Transportation Safety Board that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.

Each (row) represents information about a certain plane accident or  incident.

Each column contains a different type of data related to that incident. We are mostly dealing with the following columns:


* `Event.Id `: whether accident or incident
* `Purpose.of.flight `: reason for flying
*  `Event.Date `: when the accidents happened
* `Total.Uninjured`: number of people who  didn't get injured 
* `Location `: place 
* `Make `: type of aircraft
* `Accident.Number `
* `Investigation.Type`
* `Model`
* `Amateur.Built`
* `Country`
* `Number.of.Engines`          
* `Weather.Condition`          
* `Aircraft.damage`           
* `Registration.Number`     
* `Injury.Severity` 
 Among others we will see further into our analysis.
