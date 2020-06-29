# Taxi-project

This project is a [Kaggle competition](https://www.kaggle.com/c/yellowtaxi?rvi=1) notebooks to predict NYC Taxi trips in various regions of the city

[Project presentation](http://www.pilotpu.eu/igor.papka/blog/)

[Raw Data](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

[Data Dictionary](https://www1.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf)

The objective of the project is to learn how to predict the number of trips in the coming hours in each district of New York; for simplicity, we define rectangular areas. In order to solve it, raw data needs to be aggregated by hour and district. Aggregated data will be hourly time series with the number of trips from each district.

1. Part 1
      * [Data preprocessing with Dask](https://htmlpreview.github.io/?https://github.com/ipapka/Taxi-project/blob/master/Part_1/Part_1_Data_preprocessing_dask_2016.html)
    * [Data preparation, cleaning and analyze](https://htmlpreview.github.io/?https://github.com/ipapka/Taxi-project/blob/master/Part_1/Part_1_data_preprocessing.html)
    
2. Part 2   *In this part of work, I studied and predicted the time series of taxi rides in New York in the area of Empire State Building.*

*The data preprocessing with Dask is also attached to the work.*

*The work concept: at this stage of work I mastered the features and trained a number of SARIMA models on them in a short period of time (one week) At the same time, the quality* *and time of training strongly depend both on the length of the samples, and I have them for almost 2.5 years for each region, and on the number of attributes*
     
 * [Data visualization](https://htmlpreview.github.io/?https://github.com/ipapka/Taxi-project/blob/master/Part_2/Part_2_Data_visualization.html)
     
3. Part 3
     * [Forecasting](https://htmlpreview.github.io/?https://github.com/ipapka/Taxi-project/blob/master/Part_3/Part_3_forecasting.html)

4. Part 4
