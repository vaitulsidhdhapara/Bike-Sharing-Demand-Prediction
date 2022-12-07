# Bike-Sharing-Demand-Prediction---Seoul![image](https://user-images.githubusercontent.com/112719599/202780066-cf28f091-187d-4ba3-aef1-e596397ce55a.png)


**Problem Statment:-**

  Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
  
  
  **Data Description:-**
  
  The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.
  
  
  **Attribute Information:-**
  
  • Date : year-month-day

• Rented Bike count - Count of bikes rented at each hour

• Hour - Hour of the day

• Temperature-Temperature in Celsius

• Humidity - %

• Windspeed - m/s

• Visibility - 10m

• Dew point temperature - Celsius

• Solar radiation - MJ/m2

• Rainfall - mm

• Snowfall - cm

• Seasons - Winter, Spring, Summer, Autumn

• Holiday - Holiday/No holiday

• Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)


**Algorithms Used :-**

• Linear Regression

• Ridge Regression

• Lasso Regression

• Elastic Net Regression

• Decision Tree regression

• Random Forest Regression

• Gradient Boosting Regression


**Conclusion:-**

● We started with loading the data, then we did Exploratory Data Analysis (EDA), null values treatment, feature selection, encoding of categorical columns, and then model building. In all of these models, our accuracy ranges from 75% to 98%, which can be said to be good for such a large dataset. This performance could be due to various reasons like the proper pattern of data, large data, or because of the relevant features.

● After passing data into these models, we get different evaluation matrices. On the basis of these matrices, we can say Gradient Boosting Regressor model is best fitted in this dataset.
