# Taxi-project

This project is a [Kaggle competition](https://www.kaggle.com/c/yellowtaxi?rvi=1) notebooks to predict NYC Taxi trips in various regions of the city

[Project presentation](http://www.pilotpu.eu/igor.papka/presentation/)

[Raw Data](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

[Data Dictionary](https://www1.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf)

The objective of the project is to learn how to predict the number of trips in the coming hours in each district of New York; for simplicity, we define rectangular areas. In order to solve it, raw data needs to be aggregated by hour and district. Aggregated data will be hourly time series with the number of trips from each district.

1. <ins>Part 1</ins>
      * [Data preprocessing with Dask](https://htmlpreview.github.io/?https://github.com/ipapka/Taxi-project/blob/master/Part_1/Part_1_Data_preprocessing_dask_2016.html)
    * [Data preparation, cleaning and analyze](https://htmlpreview.github.io/?https://github.com/ipapka/Taxi-project/blob/master/Part_1/Part_1_data_preprocessing.html)
    
2. <ins>Part 2</ins>   
     * [Data visualization](https://htmlpreview.github.io/?https://github.com/ipapka/Taxi-project/blob/master/Part_2/Part_2_Data_visualization.html)
     
3. <ins>Part 3</ins>
     * [Forecasting](https://htmlpreview.github.io/?https://github.com/ipapka/Taxi-project/blob/master/Part_3/Part_3_forecasting.html)

In this part of work, I studied and predicted the time series of taxi rides in New York in the area of Empire State Building.

The data preprocessing with Dask is also attached to the work.

At this stage of work I mastered the features and trained a number of SARIMA models on them in a short period of time (one week) At the same time, the quality and time of training strongly depend both on the length of the samples, and I have them for almost 2.5 years for each region, and on the number of attributes

4. <ins>Part 4</ins>
     * [Cluster forecasting](https://htmlpreview.github.io/?https://github.com/ipapka/Taxi-project/blob/master/Part_4/Part_4_cluster_forecasting.html)
     
In this task, I used the k-Shape algorithm and its implementation in the *tslearn* library to create clusters. After that I calculated parametrs for SARIMA model with exog and forecast trips for 102 areas of New York. The result score for SARIMA model with exog was 37.19 MAE

5. <ins>Part 5</ins>
     * [XGBoost regression model](https://htmlpreview.github.io/?https://github.com/ipapka/Taxi-project/blob/master/Part_5/Part_5_regression.html)
     
At this stage of work, I mastered new features, added SARIMA models predictions as features, and trained new XGBoost regressions models on them for each of 102 areas of New York.
The new achieved score was 15.05, that is two times better than previous SARIMA model result

6. <ins>Part 6</ins>
     * [Mastering new features to improve the score](https://htmlpreview.github.io/?https://github.com/ipapka/Taxi-project/blob/master/Part_6/Part_6_new_features.html)
     
At this stage of work, I mastered much more new features from raw data and data related to traffic in NYC from other internet resources. I established, that adding new data not always improve the score and tried to understand why.

The final score of the work is 14.66 and is in the top 20 best results of the competition.
