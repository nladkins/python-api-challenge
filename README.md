# python-api-challenge

Weatherpy:
   -  The purpose of this repository is to generate a random list of city data into a data frame using citipy to identify weather trends and comparisons in the northern and southern hemispheres (weatherpy folder).  A data frames are developed to split the data from a northern hemisphere to a southern hemisphere.
   -  Plots are developed to compare wind, humidity, temperature (farenheit), and cloudiness within the hemispheres.
   -  This plots are commented with trends with summary findings at the top of the file that contains the code.

Vacationpy:
   -  To expand this, an analysis is conducted with the cities data to assist in identifying ideal vacation spots based on my personal preference.
   -  A heatmap is generated looking at humidity across the random list of cities.  
   -  Formulas are developed to identify the preferred weather which includes colder temperatures and lower windspeed.  
   -  This data is then placed into a hotels_df which is the same data frame as the cities_df with the exception of the prior having a "Hotel" column.
   -  A for loop is used to look up the closest hotel to the latitude and longitude listed in the dataframe.  
   -  The hotel results are populated into the new column that was added.  
   -  Null values are identified and then removed from the results.  
   -  The clean data is used to populate an updated heatmap pin marks for the hotel as well as the cities.  
   
About the folders:
   -  The folders named "Script Outputs" contain the key tables, plots, and heatmaps in the corresponding folders that contain the code.  
   -  The "Images" folder include other images of results and heatmaps.
   -  The "Output_Data" folder includes additional plot images as well as the original city data that was ready by the code.  
