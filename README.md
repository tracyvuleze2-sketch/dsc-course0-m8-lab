# Aviation Accident Analysis

## Project Overview
This project analyzes aviation accident data from 1983-2023 to identify the safest aircraft across different makes and models for an airline/airplane insurer. 
The analysis provides separate recommendations for small and large aircraft 
and identifies key factors that contribute to aviation safety.


## Business Problem (Problem Statement)
The client (an airline/airplane insurer) wants to know:
- Which aircraft makes/models have low rates of total destruction
- Which aircraft makes/models have low likelihood of fatal or serious passenger injuries in the event of an accident
- What general variables/conditions and key factors affecting aviation safety outcomes

## Objectives
- Clean and prepare the raw aviation accident data
- Perform exploratory data analysis
- Compare aircraft by size(large vs small aircrafts) and model
- Identify key factors affecting the safety outcomes of the aviation
- Give insights and recommendations to the client

## Data
- Source: NTSB Aviation Accident Database (1948-2023)
- Filtered to: Professional builds, accidents from 1983 onwards
- Final dataset: 63,746 accidents across 79 makes

## Key Findings and Insights

### Small Aircraft Recommendations (≤20 passengers)
- The Cessna 172 has the lowest injury rate with highest number of records
- The Cessna 182 has consistently low injury and destruction rates
- The Piper PA-28 has reliable safety profile with large sample size

### Large Aircraft Recommendations (>20 passengers)
- The Boeing 737 has lowest injury rate among large commercial jets
- The Boeing 757 has strong safety record with reliable statistics
- Airbus A320 has competitive safety profile with large sample size

## Key Factors Affecting Safety

### Factor 1: Engine Type
- Turbo Fan and Turbo Jet engines have significantly lower injury rates
- Reciprocating (piston) engines have the highest injury and destruction rates
- Turbine engines benefit from stricter maintenance and redundant systems

### Factor 2: Number of Engines
- Single engine aircraft have the highest injury and destruction rates
- Each additional engine significantly reduces risk
- Multi engine aircraft provide redundancy when one engine fails

## Recommendations

- 1 Small Aircraft
 -Cessna 172 is the most recommended small aircraft since it has the 
  largest sample size giving us the most reliable statistics and 
  consistently low injury and destruction rates
- Piper PA-28 is a strong second choice with a large sample size 
  and competitive safety profile
- Cessna 182 rounds out the top 3 with reliable statistics and 
  low destruction rates


2. Large Aircraft
- Boeing 737 is the most recommended large aircraft with the 
  largest sample size and lowest injury rate among commercial jets
- Airbus A320 is a strong alternative with competitive safety 
  profile and large sample size
- Both Boeing and Airbus benefit from strict regulatory oversight,
  redundant safety systems and highly trained pilots

3. Insurance recommendations
- Single engine piston aircraft should carry higher premiums
- Multi engine turbine aircraft represent lower risk profiles
- Flights in IMC conditions should be flagged as higher risk
- Cessna and Piper dominate small aircraft safety rankings
- Boeing and Airbus dominate large aircraft safety rankings  

## Insurance Recommendations

### Premium Pricing Guidelines

1. High Risk with  Higher Premiums:
- Single engine piston aircraft have the highest injury rate (0.28) 
  and destruction rate. These should carry the highest premiums as 
  engine failure leaves the pilot with no backup options
- Flights operating in IMC (Instrument Meteorological Conditions) 
  are 2-3x more likely to result in fatal or serious injuries compared 
  to VMC flights. Policies covering IMC operations should reflect 
  this elevated risk
- Amateur built aircraft should be avoided entirely as they fall 
  outside professional manufacturing standards

2. Lower Risk with Lower Premiums:
- Multi engine turbine aircraft (Turbo Fan, Turbo Jet) have the 
  lowest injury rates. If one engine fails the aircraft can still 
  fly safely on the remaining engines
- Commercial jets operated by major airlines benefit from strict 
  FAA regulatory oversight, mandatory maintenance schedules and 
  highly trained pilots — all of which reduce accident severity

### Manufacturer Risk Profiles

1. Small Aircraft (≤20 passengers):
- Cessna and Piper are the lowest risk manufacturers with the 
  largest accident records to support this conclusion
- Specifically Cessna 172 and Piper PA-28 are the safest models 
  with thousands of accident records confirming their safety profile
- Beech is also a strong low risk option worth considering

2. Large Aircraft (>20 passengers):
- Boeing and Airbus represent the lowest risk large aircraft 
  manufacturers with well documented safety records
- Boeing 737 and Airbus A320 are the safest specific models 
  supported by the largest sample sizes
- McDonnell Douglas and Bombardier are competitive alternatives 
  with good safety profiles

