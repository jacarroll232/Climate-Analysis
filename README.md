# SQLalchemy
SQLAlchemy 



Step 1 - Climate Analysis and Exploration

Used Python and SQLAlchemy to do basic climate analysis and data exploration of my climate database. Analysis completed using SQLAlchemy Pandas, and Matplotlib.


Used hawaii.sqlite files to complete my climate analysis and data exploration.



Precipitation Analysis


Designed a query to retrieve the last 12 months of precipitation data.
Selected only the date and prcp values.
Loaded the query results into a Pandas DataFrame and set the index to the date column.
Sorted the DataFrame values by date.
Plotted the results using the DataFrame plot method.





Use Pandas to print the summary statistics for the precipitation data.



Station Analysis


Designed a query to calculate the total number of stations.

Designed a query to find the most active stations.


Listed the stations and observation counts in descending order.




Designed a query to retrieve the last 12 months of temperature observation data (tobs).


Filtered by the station with the highest number of observations.
Plotted the results as a histogram with bins=12.









Step 2 - Climate App

Designed a Flask API based on the queries that I developed.





