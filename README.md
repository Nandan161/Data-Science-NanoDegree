Boston Airbnb Data Analysis

Business Understanding

Airbnb has transformed the travel industry by offering a unique way for guests to explore destinations like Boston, MA, while providing hosts with opportunities to share their spaces. This dataset from Airbnb Inside provides insights into the listing activity of homestays in Boston. The goal of this analysis is to uncover key insights related to Airbnb rentals in Boston, including factors influencing rental prices, neighborhoods with the highest rental prices, and seasonal variations in rental prices.


File Descriptions

listings.csv: Contains information about Airbnb listings in Boston.

calendar.csv: Contains information about the availability and price of listings on specific dates.

reviews.csv: Contains information about reviews left by guests.

Code Description

data_analysis.ipynb: Jupyter Notebook containing Python code for data cleaning, analysis, and visualization.

Dependencies
pandas
seaborn
matplotlib
numpy
scikit-learn
lightgbm


Analysis Steps


Data Cleaning: The data is cleaned to remove irrelevant columns, handle missing values, and prepare the data for analysis.

Exploratory Data Analysis (EDA): Descriptive statistics and visualizations are used to explore the dataset and uncover patterns.

Feature Engineering: Data preprocessing techniques are applied to prepare the data for modeling.


Modeling: The LightGBM regressor model is trained to predict rental prices based on various features.

Visualization: Charts and graphs are created to visualize insights such as popular amenities and rental price trends.


Results

Factors Influencing Rental Prices: The LightGBM model identifies the major factors contributing to Airbnb rental prices in Boston.

Neighborhoods with Highest Rental Prices: Analysis reveals which neighborhoods command the highest rental prices for Airbnb listings.


Seasonal Variations in Rental Prices: Rental price fluctuations throughout the year are analyzed to identify peak seasons and understand the impact of seasonality.


Conclusion
This analysis provides valuable insights for both Airbnb hosts and guests in Boston. Hosts can optimize their listings based on factors that influence rental prices, while guests can make informed decisions when booking accommodation.



Link for the Blog Post:

https://medium.com/@nandanchoudhary.iitr/uncovering-insights-from-boston-airbnb-data-a-data-analysis-journey-4051bb802afd
