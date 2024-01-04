# BIKE-DEMAND-PREDICTION
Introduction: Bike demand prediction is a crucial challenge faced by bike rental companies, where accurate forecasts play a pivotal role in optimizing inventory and pricing strategies. In this project, our goal was to develop a supervised machine learning model, specifically a regression model, to predict bike demand within a given time period.

Project Details: The original dataset comprised bike rental information, encompassing details such as the number of bikes rented, rental time, and date, along with various weather and seasonality features. Additional factors, such as holidays and the operational status of the day, were also considered.

## Methodology: 
Following data preprocessing and cleaning, the dataset was split into training and test sets. Multiple model architectures and hyperparameter settings were explored, with the best-performing model selected based on test data results.
Attribute Information:
Date : year-month-day
Rented_Bike_Count - Count of bikes rented at each hour
Hour - Hour of he day
Temperature-Temperature in Celsius
Humidity - %
Windspeed - m/s
Visibility - 10m
Dew point temperature - Celsius
Solar radiation - MJ/m2
Rainfall - mm
Snowfall - cm
Seasons - Winter, Spring, Summer, Autumn
Holiday - Holiday/No holiday
Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)
## Conclusion
The primary aim of this project was to enhance the stability of bike demand on an hourly basis. Key insights derived from the analysis include:

The XGBRegressor model emerged as a promising solution, showcasing a robust performance with an R2 score of 0.88. This makes it a suitable choice to address the challenge of stabilizing bike demand.

Discernible patterns in bike rentals were observed, with higher counts during working days compared to weekends.

Distinct peaks in bike demand were identified around 8-9 AM in the morning and 6-7 PM in the evening, aligning with typical commuting hours.

Seasonal influences were evident, showing increased bike demand during summer months as opposed to winter.

Weather conditions played a significant role, with clear days correlating to higher bike demand, while snowy or rainy days saw a decline.

The optimal temperature range for heightened bike demand was found to be between 22 to 25°C.

Several features, including 'Hour,' 'Temperature (°C),' 'Humidity,' 'Wind_speed,' 'Visibility,' 'Solar_Radiation,' 'Rainfall,' 'Snowfall,' 'Seasons,' and 'Day of Week,' were identified as crucial regulators of bike demand.
