Notebook for Hut et al. 2021
================

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

# Models

## Lying and walking behavior 

  - [Link to model Standups](StandUps/StandUps.md)
  - [Link to model Leg Activity](LegActivity/LegActivity.md)
  - [Link to model Lying Time](LyingTime/LyingTime.md)
  - [Link to model Lying Bouts](LyingBouts/LyingBouts.md)
  - [Link to model Lying Bout
    Length](LyingBoutLength/LyingBoutLength.md)

## Eating behavior

  - [Link to model Eating Time](EatingTime/EatingTime.md)
  - [Link to model Eating Bouts](EatingBouts/EatingBouts.md)
  - [Link to model Eating Bout
    Length](EatingBoutLength/EatingBoutLength.md)

## Rumination behavior

  - [Link to model Rumination Time](RuminationTime/RuminationTime.md)
  - [Link to model Rumination Bouts](RuminationBouts/RuminationBouts.md)
  - [Link to model Rumination Bout
    Length](RuminationBoutLength/RuminationBoutLength.md)

# Remarks and meeting notes

# Review
