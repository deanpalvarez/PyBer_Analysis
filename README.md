# Using Matplotlib to Display Rideshare Company Data

## Overview
We analyzed a large dataset for the fictional ridechare company "PyBer" to display trends on a line chart of fare prices over time for different types of cities. Utilizing the functionality of Pandas/NumPy, we could create dataframes and run formulas to extract/isolate data from very large spreadsheets, then display information for analysis on a line chart, using Matplotlib.

## Results
![image](https://user-images.githubusercontent.com/79726572/112736723-3924a280-8f2b-11eb-8f3b-42c5973a4e43.png)
Pictured above is the result of our work. Total fare cost was calculated to be the sum of all ride fares for each single day across a 4 month period, seperated by the 3 types of cities in our dataset (Urban, Suburban, & Rural). Despite all the coding that had to be executed to acheive this, the desired analyais can essentialy be boiled down to this one chart.

### Process to Acheive Results
We reached such information by first seperating the data. A new data frame was made to only display the columns of information we need (Date, City Type, & Fare) Then the city type was pivoted to be displayed as columns, and from there we created the dataframe needed to display the first 4 months of the year we want to retrieve our data from.

## Results of Analysis
For this 4 month period, there really is no significant change/fluctuation in fare price relative to time of year/type of city. We can note the overall difference of fair price  between the city type, which is really nothing surprising frankly, as it would make sense for fare prices to be higher in larger/more populated cities like in the Urban areas. This is not unlike any other analysis of a business' products or service, having prices be relative to demand. In terms of reccomendations to the CEO, not much can be suggested out of common knowledge based off the information presented. Some suggestions perhaps worth mentioning in further analysis would be to analyze other factors not covered in our dataset. These could be things like trip length, peak periods/days throughout a year, outliers of particularly low/high traffic in a given time period, etc. These can all be analyzed with python libraries if given the necessary datasets.
