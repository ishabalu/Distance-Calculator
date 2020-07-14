# Distance-Calculator
For this project, the chosen cloud service is Google Cloud Platform (GCP) and have used python as the programming language.

Google Cloud Platform provides a variety of map APIs from which we have chosen two APIs to accomplish our task. 
The following are those listed APIs:
Geocoding map API
Convert between addresses and geographic coordinates.
Convert addresses into geographic coordinates (geocoding). 
This API also allows you to convert geographic coordinates into an address (reverse geocoding).
To use the Geocoding API, you must first enable the Map API and obtain the proper authentication credentials. 
------------------------------
Distance matrix map API
With this API you can access travel distance and time for a matrix of origins and destinations.
The information returned is based on the recommended route between start and end points and consists of rows containing duration and distance values for each pair.
Just like the Geocoding Map API, we must enable this API and produce an API key as well before using else will be thrown an ERROR message.
------------------------------

Below listed are the Python Modules used: 
1.googlemaps: Imported in order to access the Distance matrix API which finds the distance between two locations that is given
2.geocoder: Imported to access the Geocoding API which will help convert the address into latitude and longitude 
3.Geopy: This contains Nominatim which is imported to help with reverse coding i.e. to convert latitude and longitude to an address
4.subprocess: You can start a process in Python using the Popen function call, which is very handy when you want to run a system. Here, we used it in order to access the GPS location of our device to obtain the current location
5.tkinter: This module was used to create the GUI of the application.
6.PIL: used to put the background image in our GUI   

--------------------------------


