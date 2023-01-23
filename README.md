# CAPITAL BIKE SHARE RENTAL ANALYSIS

![image](https://user-images.githubusercontent.com/115487795/214151729-d4267c1b-ecce-4690-ac48-ce56fe2edbdc.png)

# INTRODUCTION
Living in a city can present a significant transportation challenge, particularly due to the high volume of cars on the road and the resulting traffic congestion. To combat these issues, many citizens are turning to alternative forms of transportation. One such alternative is cycling, which is becoming increasingly popular due to its health benefits and its eco-friendly nature. Understanding the factors that influence individuals' decisions to cycle is an interesting and valuable task.

The Capital Bikeshare company has made this kind of analysis possible by sharing data on bike rental behavior in Washington D.C. The CapitalBikeShareRentalAnalysis repository contains a data analysis that aims to understand the behavior of people who rented bikes in Washington D.C. between 2012 and 2018. By utilizing this data, the project aims to gain insight into the factors that influence individuals' decisions to cycle, as well as to understand overall trends in bike rental behavior in the city.

# STEPS
To make the analysis more interesting and informative, the project not only examines the frequency and duration of bike rentals but also takes into account information about the weather and the location of the rental stations. The data collection folder within the repository contains scripts for downloading and scraping raw data.

Before working with the data, it's essential to get to know it better. To this end, the distribution of features was analyzed in the exploratory analysis stage. This helped to understand the dataset better, detect outliers, and decide how to handle them. As a result, a final version of the data was prepared and made ready for analysis. Scripts with exploratory analysis can be found in the data exploration folder.

The next step was to build a regression model that could predict the number of bike rentals on a given day. The regression model directory contains scripts for preparing predictors and obtaining new data (such as from Google Trends). Simple regression models were built as a baseline and later the last notebook focuses on building top-performing model by feature engineering and hyperparameters tuning.
