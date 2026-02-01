# Airline Analysis Project
## Overview
This project analyzes aircraft data to support decision-making for an aviation business expansion by identifying aircraft with lower operational risk and better performance.

## Business Understanding
The objective of this analysis is to help stakeholders choose suitable aircraft models for a new business venture by evaluating operational risk, cost, and performance factors.

## Data Understanding
- Dataset includes aircraft and airline operational information
- The dataset had 2500 rows and 8 columns
- Used to compare aircraft suitability for expansion
- There were 118 missing values and 1199

## Data Cleaning
The following steps were performed:
- Removed missing values
- Dropped duplicate records
- Standardized column names and data types

## Exploratory Data Analysis
EDA was conducted to examine relationships between aircraft type, operational cost, and performance metrics using multiple visualizations.

## Insights
- Out of 506 unique aircraft types, the Dassault Falcon series (7X, 900B, 900EX, 900EX EASy) and ATR 42-300 recorded zero fatalities.
- The Boeing 737 MAX 8 is the riskiest with 346 fatalities, followed by Ilyushin Il-76TD (258) and other Boeing 737 variants.
- Substantial damage is the most common outcome across all incidents (661 out of 1,199), meaning most accidents result in serious damage.
- Write-offs (315) are the second most common, meaning the aircraft is destroyed.

## Recommendations
- The company should prioritize purchasing Dassault Falcon aircraft (7X, 900B, 900EX) as they have the lowest operational risk.
- The company should avoid Boeing 737 variants, especially the 737 MAX 8, due to the high fatality and damage record.
- The ATR 42-300 is also a safe option if the company needs smaller aircraft.

## Next Step
- Compare the total costs of the Dassault Falcon series and the ATR 42-300 to help decide which offers better long-term value.
- Check the company’s flight needs to ensure the chosen aircraft meets operational requirements.
- Validate the safety trends identified by exploring more recent aviation safety data.
- Find current market pricing and availability for the Dassault Falcon and ATR aircraft from manufacturers or dealers.
- Use these results to help make a final aircraft choice based on cost, safety, and operational fit.
