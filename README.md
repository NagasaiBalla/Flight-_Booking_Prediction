Flight Price Prediction using Python

Project Overview:-

This project analyzes airline booking data and identifies factors affecting flight ticket prices. The dataset contains over 300,000 flight records, including airline information, source and destination cities, departure and arrival times, travel duration, days left before departure, and ticket prices.

Objectives:-

Perform Exploratory Data Analysis (EDA)
Identify factors influencing ticket prices
Analyze airline-wise fare trends
Examine the impact of departure date on ticket prices
Detect multicollinearity using VIF
Prepare data for machine learning models

Dataset Features:-

Feature	                 Description
Airline	                 Airline name
Source City	             Departure city
Destination City	       Arrival city
Departure Time	Flight   departure time
Arrival Time	           Flight arrival time
Stops	                   Number of stops
Class	                   Economy/Business
Duration	               Flight duration
Days                    Left	Days before departure
Price	                  Ticket price

Technologies Used:- 

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Statsmodels

Key Insights:- 

Ticket prices decrease as the number of days before departure increases.
Business-class tickets are significantly more expensive than economy-class tickets.
Vistara and Air India show higher average ticket prices.
Flight duration has a positive correlation with ticket prices.
No significant multicollinearity was found among selected features after removing redundant variables.

Visualizations:- 

Airline vs Price Analysis
Days Left vs Price Trend
Source & Destination City Analysis
Correlation Heatmap
Category Frequency Analysis

Results:-

The project successfully identified key factors affecting flight prices and prepared the dataset for predictive modeling.


