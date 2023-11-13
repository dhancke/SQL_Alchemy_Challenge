# SQL_Alchemy_Challenge
# SurfsUp_DH
Activity 10

This task had 2 parts:

Part 1: Analyse and Explore the Climate Data
This required the use of Python and SQLAlchemy to do a basic climate analysis and data exploration of the climate database.

The provided files are climate_starter.ipynb and hawaii.sqlite.

The SQLAlchemy automap_base() function was to be used to reflect tables into classes, and then references saved to the classes named station and measurement.

Finally Python was to be linked to the database by creating a SQLAlchemy session.

Precipitation Analysis
Finding the most recent date in the dataset, there was a requirement to get the previous 12 months of precipitation data by querying the previous 12 months of data.

This query's results were to be put into a Pandas DataFrame, explicitly setting the column names and sorted by date.

These results were to be plotted by using the DataFrame plot method and using Pandas to print the summary statistics for the precipitation data.

Station Analysis
This required designing a query to calculate the total number of stations in the dataset and finding the most-active stations (that is, the stations that have the most rows).

Here the following questions needed to be answered:
 - Which station id has the greatest number of observations?
 - Using the most-active station id, calculate the lowest, highest, and average temperatures.
 - Design a query to get the previous 12 months of temperature observation (TOBS) data. 

The results were to be plotted as a histogram with bins=12.

Part 2: Designing a Climate App

Once the analysis hd been completed, a Flask API was to be developed.

A JSON list of temperature observations for the previous year was also to be supplied.



