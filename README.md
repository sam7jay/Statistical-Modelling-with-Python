# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The main goals of this project are to gain insights into the bike station data, analyze the relationship between bike stations and nearby Points of Interest, assess the quality of API data, and build a statistical model to understand the factors influencing bike station usage.

## Process
### COLLECT DATA
Access data using CityBikes API.
Store the API key in the machine's environment.
Retrieve data by calling the API URL and specifying the desired location data.
Convert the Convert the list of dictionaries to a DataFrame.
Convert the DataFrame to a CSV file.
### CLEAN DATA
Remove duplicate and NULL values from the data.
Eliminate unnecessary columns.
Organize the data in a structured manner..
### SQLITE DATABASE
Create a SQLite database using Python.
Define tables and import values from CSV files.
### VISUALIZATION
Present the data using various charts and graphs for improved understanding and visual appeal.
Creat a map centered on the mean coordinate.
Plot average bikes available by location.
plot bikes available versus distance.
### REGRESSION MODEL
Create a regression model to analyze the correlation between dependent and independent variables.
Split the data into features and target.
Train and evaluate the model.

## Results
RESULTS: the model is not good fit because R-square is too low which show a low correlation.

## Challenges 
API Limitations: The APIs you are working with, such as CityBikes, Foursquare, and Yelp, have limitation
Data Quality and Completeness: The data obtained from APIs are not always perfect.
Authentication and API Keys: Some APIs require authentication using API keys.
Data Integration and Joining: Joining data from different sources, such as CityBikes, Foursquare, and Yelp, can be challenging.
Database Management: Creating and managing a SQLite.
## Future Goals
Spend more time on data cleaning and preprocessing.
Conduct a more comprehensive EDA to gain deeper insights into the data.
Explore additional data visualization techniques to effectively communicate insights and findings from the analysis
