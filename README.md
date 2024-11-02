Notebook for Hut et al. 2022
================

Original article [here](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0264392)

[![DOI](https://zenodo.org/badge/365004681.svg)](https://zenodo.org/badge/latestdoi/365004681)

# Getting the data from the bovi-analytics blob storage

You will need to get access key via Miel Hostens (<m.m.hostens@uu.nl>)

The data contains data from 8 farms using 2 NEDAP sensors (leg and neck). 

  - HerdIdentifier - Identifier for the herd
  - Animalidentifier : Identifier for the animal (her eartag)
  - AnimalNumber : Secondary identifier for the animal
  - Parity: 1, 2 and 3+
  - CalvingTime : Date of calving
  - CalvingSeason: season of calving e.g. Jan/Feb/Mar: winter
  - MonthsInMilk: 30d average accounts for 1 month except for month 0: d-1, d0, d+1
  - Hour: 2 hourly blocks per 24h
  - MilkingType: automatic milking system (AMS) or conventional milking system (CMS)
  - SensorDaysInMilk : Days in milk at sensor observation
  - SensorValue: Eating time, rumination time, lying time, standing time, walking time, leg activity: number of steps (min/2h, ,min/day, no. of steps/2h, no. of steps/day)

# Models MonthsInMilk

## Lying and walking behavior 

  - [Link to model Standing time](https://github.com/Bovi-analytics/hut-et-al-2021/blob/master/Lactation%20models/StandingTime_MonthsInMilk.ipynb)
  - [Link to model Walking time](https://github.com/Bovi-analytics/hut-et-al-2021/blob/master/Lactation%20models/WalkingTime_MonthsInMilk.ipynb)
  - [Link to model Leg Activity](https://github.com/Bovi-analytics/hut-et-al-2021/blob/master/Lactation%20models/LegActivity_MonthsInMilk.ipynb)
  - [Link to model Lying Time](https://github.com/Bovi-analytics/hut-et-al-2021/blob/master/Lactation%20models/LyingTime_MonthsInMilk.ipynb)


## Eating behavior

  - [Link to model Eating Time](https://github.com/Bovi-analytics/hut-et-al-2021/blob/master/Lactation%20models/EatingTime_MonthsInMilk.ipynb)

## Rumination behavior

  - [Link to model Rumination Time](https://github.com/Bovi-analytics/hut-et-al-2021/blob/master/Lactation%20models/RuminatingTime_MonthsInMilk.ipynb)

# Models 24h patterns
## Lying and walking behavior 

  - [Link to model Standing time](https://github.com/Bovi-analytics/hut-et-al-2021/blob/master/Daily%20models/StandingTime_24h_pattern.ipynb)
  - [Link to model Walking time](https://github.com/Bovi-analytics/hut-et-al-2021/blob/master/Daily%20models/WalkingTime_24h_pattern.ipynb)
  - [Link to model Leg Activity](https://github.com/Bovi-analytics/hut-et-al-2021/blob/master/Daily%20models/LegActivity_24h_pattern.ipynb)
  - [Link to model Lying Time](https://github.com/Bovi-analytics/hut-et-al-2021/blob/master/Daily%20models/LyingTime_24h_pattern.ipynb)


## Eating behavior

  - [Link to model Eating Time](https://github.com/Bovi-analytics/hut-et-al-2021/blob/master/Daily%20models/EatingTime_24h_pattern.ipynb)

## Rumination behavior

  - [Link to model Rumination Time](https://github.com/Bovi-analytics/hut-et-al-2021/blob/master/Daily%20models/RuminatingTime_24h_pattern.ipynb)

## overall graphs
![image](https://user-images.githubusercontent.com/49685958/120319276-22128000-c2e1-11eb-9233-70f34d0e50b3.png)
![image](https://user-images.githubusercontent.com/49685958/120319365-38204080-c2e1-11eb-9e15-fecfb75c4e58.png)

# Remarks and meeting notes

# Review
