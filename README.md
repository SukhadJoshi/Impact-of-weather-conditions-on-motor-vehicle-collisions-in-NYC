## Overview
This project examines the relationship between weather conditions and vehicle collisions using historical weather data from Meteostat and collision data. The analysis identifies patterns in collision frequency, severity, contributing factors, and vehicle types.

## Datasets Used:
Motor Vehicles Collisions - Crashes 
Link: "https://catalog.data.gov/dataset/motor-vehicle-collisions-crashes"

Weather Data meteostat python
Link: "https://dev.meteostat.net/python/"

## Key Research Questions
1. How do weather conditions influence the frequency and severity of vehicle collisions?
2. What are the peak times for vehicle collisions under different weather conditions?
3. Which vehicle types are most involved in fatal collisions?
4. What are the top contributing factors in sedan-related collisions?
5. How do sedan collisions vary across different boroughs?

## Features
1. **Data Preprocessing**:
   - Merged hourly weather data with collision records.
   - Categorized weather conditions into Clear, Rainy, Stormy, and more.
   - Removed outliers based on geographical and temporal factors.

2. **Weather-Collision Analysis**:
   - Explored collision frequency and severity metrics (injuries and fatalities).
   - Identified weather conditions like Heavy Rain as critical contributors to severe collisions.

3. **Peak Collision Times**:
   - Highlighted rush hours (8 AM and 5 PM) as high-risk periods.
   - Found Rainy and Overcast conditions dominate evening collisions.

4. **Vehicle-Type Analysis**:
   - Sedans and SUVs are the most involved in severe collisions.
   - Highlighted vehicle-specific risks, like motorcycles having higher fatality rates despite lower involvement.

5. **Borough-Wise Analysis**:
   - Brooklyn and Queens have the highest sedan collision rates, while the Bronx and Staten Island have the lowest.

6. **Top Contributing Factors**:
   - Driver inattention, following too closely, and failure to yield are leading causes of collisions.

## Visualizations
- Collision frequency and severity by weather condition.
- Peak collision times for different weather categories.
- Top vehicle types contributing to fatal crashes.
- Contributing factors in sedan collisions.
- Borough-wise distribution of sedan collisions.
