# Web-Design-Challenge
Web Design Homework - Web Visualization Dashboard (Latitude)

Created the following web pages with descriptions.
1. index.html - landing or home page
	The purpose of this project was to analyze how weather changes as you get closer to the equator. 
        To accomplish this analysis, we first pulled data from the OpenWeatherMap API to assemble a 
        dataset on over 500 cities.
	After assembling the dataset, we used Matplotlib to plot various aspects of the weather versus 
        versus latitude. Factors we looked at included: temperature, cloudiness, wind speed, and humidity.
        This site provides the source data and visualizations created as part of the analysis, as well as 
        explanations and descriptions of any trends and correlations observed.

2. max_temp.html - features latitude vs. max temperature plot
	As expected, the weather becomes significantly warmer as one approaches the equator
        (0 deg. Latitude). More interestingly, however, is the fact that the southern hemispere 
        tends to be warmer this time of year than the northern hemisphere.  This may be due to
        the tilt of the earth at the time of year this data was gathered.	

3. humidity.html - features latutude vs. humidity plot
	As expected, locations with warm climates, such as those near the equator, generally have higher 
        humidity than in cooler regions such as those near the poles.

4. cloudiness.html - features latutude vs. cloudiness plot
	Cloudiness appears to be consistent across the spectrum of the latitudes and to be unaffected 
        by proximity to the equator. 

5. wind_speed.html - features latutude vs. wind speed plot
	Wind speeds are observed to be less at the equator than in the northern and
        and southern hemispheres. 

6. comparison.html - features all (4) plots, 2 through 5 above

7. data.html - page listing all source cities data used to create plots

Created the following jupyter notebook, import_data.ipynb, to read in cities.csv
to a DataFrame and then converted Dataframe to html.
I then copied and pasted the resulting html tables code into the data.html file.