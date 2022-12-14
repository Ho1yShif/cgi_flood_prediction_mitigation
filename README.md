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
- Goal: 
- Point

**Flood Financial Analysis**
- Goal: 
- Point

### Takeaways and Next Steps
- Point

## Team Members
- Jinglin Zhao (Team Lead)
- Shifra Isaacs
- Alvin Radoncic
- Priscilla Ramos
- Topu Saha