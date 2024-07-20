# EV Market Size Analysis

This repository contains the analysis of the electric vehicle (EV) market using data on EV registrations. The analysis explores various aspects such as the adoption of EVs over the years, geographical distribution, popularity of EV types and manufacturers, and electric range distribution. It also includes forecasting future EV market trends.

## Dataset

The dataset used for this analysis is the "Electric Vehicle Population Data" containing information on EV registrations from 1997 to 2024. The data includes fields such as 'VIN (1-10)', 'County', 'City', 'State', 'Postal Code', 'Model Year','Make', 'Model', 'Electric Vehicle Type','Clean Alternative Fuel Vehicle (CAFV) Eligibility', 'Electric Range','Base MSRP', 'Legislative District', 'DOL Vehicle ID',
'Vehicle Location', 'Electric Utility', '2020 Census Tract'

## Analysis Overview

### 1. Data Loading and Preprocessing

The dataset is loaded and cleaned by removing any missing values.

### 2. EV Adoption Over the Years
<div style="display: flex;">
    <img src="https://github.com/aarish22/EVMarketSizeAnalysis/blob/main/Plots/EV%20Adoption%20Over%20time.png" alt="EV Adoption Over Time" style="width: 100%; margin-right: 10px;">
</div>
This section analyzes the trend of EV adoption over the years.

**Insights:**
- EV adoption has been increasing over time, with a significant upward trend starting around 2016.
- The year 2023 shows a particularly sharp increase in the number of registered EVs.

### 3. Geographical Distribution at County Level
<div style="display: flex;">
    <img src="https://github.com/aarish22/EVMarketSizeAnalysis/blob/main/Plots/Top%20cities%20in%20top%20counties.png" alt="Top Cities in Top Counties by EV Registrations" style="width: 100%; margin-right: 10px;">
</div>
Analyzing the distribution of EVs within the top counties and cities.

**Insights:**
- Seattle, in King County, has the highest number of EV registrations.
- King County dominates EV registrations among the three counties analyzed.

### 4. Distribution of Electric Vehicle Types
<div style="display: flex;">
    <img src="https://github.com/aarish22/EVMarketSizeAnalysis/blob/main/Plots/Distribution%20of%20vehicle%20types.png" alt="Distribution of Electric Vehicle Types" style="width: 100%; margin-right: 10px;">
</div>
Analyzing the popularity of different types of electric vehicles.

**Insights:**
- Battery Electric Vehicles (BEVs) are more popular than Plug-in Hybrid Electric Vehicles (PHEVs).

### 5. Popularity of EV Manufacturers
<div style="display: flex;">
    <img src="https://github.com/aarish22/EVMarketSizeAnalysis/blob/main/Plots/top%2010%20popular%20ev%20makes.png" alt="Top 10 Popular EV Makes" style="width: 100%; margin-right: 10px;">
</div>
Analyzing the top EV manufacturers based on the number of registered vehicles.

**Insights:**
- Tesla leads by a substantial margin with the highest number of vehicles registered.
- Nissan and Chevrolet follow but with significantly fewer registrations than Tesla.

### 6. Distribution of Electric Vehicle Ranges
<div style="display: flex;">
    <img src="https://github.com/aarish22/EVMarketSizeAnalysis/blob/main/Plots/Distribution%20of%20electric%20vehicle%20ranges.png" alt="Distribution of Electric Vehicle Ranges" style="width: 100%; margin-right: 10px;">
</div>
Analyzing the distribution of electric vehicle ranges.

**Insights:**
- There is a high frequency of vehicles with a low electric range.
- The mean electric range is approximately 58.84 miles.

### 7. Forecasting Future EV Market Trends
<div style="display: flex;">
    <img src="https://github.com/aarish22/EVMarketSizeAnalysis/blob/main/Plots/Current%20and%20estimated%20ev%20market.png" alt="Current & Estimated EV Market" style="width: 100%; margin-right: 10px;">
</div>
Using exponential growth to forecast the number of EVs for the next five years.

**Insights:**
- The number of actual EV registrations remained relatively low until around 2010, after which there was a consistent and steep upward trend.
- Forecasted EV registrations predict a dramatic increase in the near future, indicating a significant expansion in the EV market size.

## Summary

Market size analysis is crucial for understanding demand magnitude, assessing market saturation, and identifying growth opportunities. From our EV market size analysis, we found a promising future for the EV industry, indicating a significant shift in consumer preferences and a potential increase in related investment and business opportunities.


