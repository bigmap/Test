# Taxi tip prediction NYC test
This Git contains the information and files for use in the Carto test for taxi tip prediction on NYC yellow taxies.
* The scripts are done in R language.
* All the process about data cleanup, feature engineering and model can be found on folder Rmarkdown.
* Script for Rmarkdown can be found at folder Rscript.
## API creation
For API creation we should use a simple approach to make it ligther and fast on response. We should identify what variables (existing or created during the process) are the most correlated to the tip amount.
  * In this test it has been found that the variables more important for this prediction where.
    * Total amount of money(tip excluded).
    * Passenger count
    * Fare amount
    * Trip distance
    * Trip time
    * It should be interesting as I mention in the markdown to see how the departure NB and dropoff NB affect to the tip, and 
      also do more detailed analysis to see how the time of day, day of week affects. If a correlation is found with those we 
      should think to add more variables as GPS lat/long, time period of the day (morning, afternoon, evening,...) and or day 
      day of week (weekend, mid week,...).
