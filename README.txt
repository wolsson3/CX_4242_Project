DESCRIPTION
-----------
This package intends to simplify the process of road trip planning. This set files contains all necessary dependencies and datasets to calculate the optimal road trip given a set of desired destinations. 

Vehicle data has been scraped and cleaned from XXX. Over 50,000 data points are included for vehicle mpg rates. The Google Maps API and Places API have the capacity to search over 20 petabytes of data. Despite this extremely large amount of data, Intripid ensures the optimal sites along your route in an efficient manner.

Google API's have specific rate limits for their services. The Google Maps JavaScript API provides 2,500 free map loads per 24 hours. Above this, it charges $0.50/1000 additional requests, up to 100,000 per 24 hours. The Google Places Javascript API provides 1,000 free requests per 24 hours, and 150,000 free requests if billing is enabled to verify your identity. For standard route searches, free API usage and rates should be sufficient.




INSTALLATION
------------
1. You will need a Google API Key. Instructions are located here: https://developers.google.com/maps/documentation/javascript/get-api-key

2. Install a text editor such as Sublime or Atom. Download link for Sublime is here: https://www.sublimetext.com/3

3. Open Intripid.html with your text editor. On line XXX, paste your API key where it says "key=". Then save the file. Now the package is ready to run.




EXECUTION
---------
1. Open Intripid.html with your preferred web browser. We recommend Google Chrome.

2. Under the Destinations dropdown, enter your starting location (such as "Atlanta, GA"), desired destinations separated by a semicolon (such as "Savannah, GA; Jacksonville, FL"), must-go destinations (if we must see Savannah, enter "Savannah, GA"), and preferred site categories ("amusement_park, movie_theater, spa, zoo").

3. Under the Car Details dropdown, enter the make, model, and year of the vehicle. For this demo, select 2015 BMW i8.

4. For Additional Trip Options, leave all blank for this demo except for Distance Off Route For Stops. Leave this at the default 3 miles. Click Calculate Route.

5. The output shows route details, expected enjoyment, and the top three sites along the route.