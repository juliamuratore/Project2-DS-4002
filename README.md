# Project2-DS-4002
Welcome to our Project 2 info!

## Contents of our repository:
> Section 1: Software and platforms

> Section 2: Map of documentation

> Section 3: Instructions for reproducibility

## Section 1: Software and platforms
* Software
  * Visual Studio Code
* Packages needing installation
* Platforms
  * Windows
  * Mac
 
## Section 2: Map of documentation
* Project1-DS-4002
  * README.md
      * Orientation of repository
  * LICENSE.md
      * Terms and conditions
  * SCRIPTS
      * Project2_EDA
      * Project_2_ARIMA
  * DATA
      * weatherdata.csv - original download
      * data.csv - cleaned and updated dataset
  * OUTPUT
      * precip_over_time
      * snow_over_time
      * temperature_over_time
      * totalPrecip_rainfall
      * wind_direction_general
      * wind_direction_specific
  * REFERENCES
      * [1] Available: https://open-meteo.com/en/docs/historical-weather-api. [Accessed: Feb. 28, 2024]

      * [2] “Complete Guide on Time Series Analysis in Python.” Available: https://kaggle.com/code/prashant111/complete-guide-on-time-series-analysis-in-python. [Accessed: Feb. 28, 2024]
      * [3] J. Brownlee, “How to Create an ARIMA Model for Time Series Forecasting in Python,” Machine Learning Mastery . Available: https://machinelearningmastery.com/arima-for-time-series-forecasting-with-python/
   
## Section 3: Instructions for Reproducibility
1. Collecting and cleaning Data: In order to compile the data set, Open-Meteo APIis must be accessed. A set of different weather metrics (max temperature, min temperature, mean temperature, sunrise, sunset,  daylight duration, sunshine duration, precipitation sum, rain sum, snowfall sum, precipitation hours, wind speed, and wind direction) must be pulled from the Historical Weather API. This data must pulled for each day from 2/11/2014 to 2/25/24 in Charlottesville, Virginia. No instances were dropped from the dataset since there were no missing values, but columns must be changed for readability, and parameters must be added for wind direction.
2. Creating Models and Looking at Trends: 
3. ARIMA Analysis
4. Results
