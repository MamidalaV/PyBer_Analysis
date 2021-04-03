# PyBer_Analysis

# PURPOSE:
  ## The purpose of this project is to analyze all the rideshare data from January to early May of 2019 and create a compelling visualizations for the CEO.

# RESULTS:
  ## Two datasets have been used for this analysis:
  City Data and Ride Data
    
   ![city_df](https://user-images.githubusercontent.com/74985818/113456477-577f1800-93db-11eb-98b2-878955e27360.png) ![ride_df](https://user-images.githubusercontent.com/74985818/113456491-5e0d8f80-93db-11eb-97e5-975e035dc24e.png)
   
  - These have been combined to generate a new DataFrame:
  ![merged](https://user-images.githubusercontent.com/74985818/113462244-fdd41900-93ed-11eb-8634-3e92f2f52c77.png)
  
   - This is inturn sliced to create 3 new DataFrames one for each city type.
   - For every city type, 3 new variables were used to get the **Ride Ccount, Average Fare** and **Driver Count**.
   - These are then plotted into a single scatter plot to provide a hollistic view.
   ![Fig1](https://user-images.githubusercontent.com/74985818/113462727-560c1a80-93f0-11eb-916f-6a1cf125c7c9.png)

   
   ### Statistical Visulization of Ride Count, Ride Fare & Driver Count (Summary View):
   
   ![Ride_count](https://user-images.githubusercontent.com/74985818/113462989-928c4600-93f1-11eb-9721-718a17ecb885.png) ![Ride_Fare](https://user-images.githubusercontent.com/74985818/113462991-94eea000-93f1-11eb-9079-60f176d7fb9e.png) ![driver_count](https://user-images.githubusercontent.com/74985818/113462998-9ddf7180-93f1-11eb-9665-ce6c72e144bb.png)
  
  ## For further analysis, for each city type, No. of rides, No. of drivers, sum of fares, average fare per ride, average fare per driver have been retreived

   - Total Rides
   
   ![1_total_rides](https://user-images.githubusercontent.com/74985818/113463287-f95e2f00-93f2-11eb-8176-92b7e4db7c50.png)

   - Total Drivers
   
   ![2_total_drivers](https://user-images.githubusercontent.com/74985818/113463289-011dd380-93f3-11eb-90a9-736def212525.png)
   
   - Total Fares
   
   ![3_total_fares](https://user-images.githubusercontent.com/74985818/113463294-067b1e00-93f3-11eb-8a86-235b8f6d8e8c.png)
   
   - Average Fare per Ride
   
   ![4_avg_fare_per_ride](https://user-images.githubusercontent.com/74985818/113463308-1561d080-93f3-11eb-8135-2d9c5b539f3c.png)

   - Average Fare per driver
   
   ![5_avg_fare_per_driver](https://user-images.githubusercontent.com/74985818/113463316-21e62900-93f3-11eb-824c-3d22cc709649.png)
   
   ### Additionally, a new Summary DataFrame has been created along and cleaned in order to generate a pivot.
   
   - Summary DataFrame:
   
   ![6_Pyber_summary](https://user-images.githubusercontent.com/74985818/113463385-6671c480-93f3-11eb-8411-7849907e2b53.png)
   
   - cleaned DataFrame to remove index:
   
   ![7_clean_df](https://user-images.githubusercontent.com/74985818/113463393-74bfe080-93f3-11eb-9c41-22bbfdafeb2f.png)

  ### The data within the new dataframe has been resampled to get weekly a snapshot and used to generate the final line graph.
  
  ![PyBer_fare_summary](https://user-images.githubusercontent.com/74985818/113463445-a8026f80-93f3-11eb-89d1-4d2a3ab26df0.png)

   

# SUMMARY:

  ## 
