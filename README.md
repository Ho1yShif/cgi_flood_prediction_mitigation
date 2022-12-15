# CGI Flood Prediction and Mitigation
## [Final Presentation](https://docs.google.com/presentation/d/13MLbYKmZbhku9h3XqiFmrV2p6uzkDECL71DOnnmPDoA/edit?usp=sharing)

This repository stores code for a CGI Externship Project completed in the Fall 2022 semester via NJBDA in collaboration with the Rutgers MBS Exchange Program

**Overarching Goal**: Deliver a strategy to predict and mitigate flood effects in vulnerable NJ areas in order to help business and families suffering from the effects of flood events and storms such as Hurricane Ida

**Data Sources**: USGS, NJ Department of Environmental Protection, NJGIN, USDA, FEMA, NJ.gov

**Tools Used**: Python, Jupyter, ArcGIS, Time Series Modeling

### 3-Pronged Approach
**Water Level Prediction**
- Goal: Model Gauge (water level) in order to predict future floods, which are defined by the USGS as events with water levels at or above 8.5 ft
- The best-performing model was XGBoost with a R-squared of 99% and a mean absolute error of 0.02 ft
- Other models we explored include LSTM, SARIMA, and Rolling Window Regression
- Caveat: XGBoost is likely overfitting due to correlated features; this is addressed in the next steps we provided in our slide deck

**Flood Mapping**
- Goal: Build flood susceptibility map to view the most vulverable area in North Trenton
- Point:
--Assunpink Creek, which runs through North Trenton, is a main flood source
--The deep red area is prone to flooding due to the proximity to rivers 
--Every year, water levels tend to increase from December through May

**Flood Financial Analysis**
- Goal: 
- Point

### Takeaways and Next Steps
-Water Level Prediction:
Tune XGBoost model and fix correlated features
Analyze feature importance to simplify future models
Leverage exponential smoothing models
Explore other locations with accessible datasets
- Flood Susceptibility map:
Build county or city-level flood map
Explore more FEMA flood datasets
Select the city/county with highest flood susceptibility
Add interactive map features
- Flood Financial Analysis
Explore FEMA claims dataset county/city level
Study flood damage by industry
Risk management strategies for buildings in susceptible areas
Explore how floods affect financial and qualitative aspects of a business

## Team Members
- Jinglin Zhao (Team Lead)
- Shifra Isaacs
- Alvin Radoncic
- Priscilla Ramos
- Topu Saha
