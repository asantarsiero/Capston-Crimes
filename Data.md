# Data
My project will be based on two datasets:

<b>1. Crimes in Chicago - 2019</b><br>
Extracted from the official dataset of the City of Chicago - Chicago Portal at https://data.cityofchicago.org/Public-Safety/Crimes-2019/w98m-zvie
I extracted the entire dataset regarding 2019 crimes and subsequently sliced it to obtain only data regarding two crime categories: "Homicides" and "Burglaries". The latter was further sliced to only obtain burglaries that happened in "Apartments" and "Residences".
A sample row will include a date of the crime, location (langitude, latitude), category of the crime (homicide or burglary), primary location (apartment, residence, street, train station, etc.) and other additional data.

<b>2. Foursquare data</b><br>
This data will, available from Foursquare and exctracted through API requests, will be used to assess the closest three venues to the crimes.
The goal is to get the venue type (i.e. bar, restaurant, office, etc.) 
