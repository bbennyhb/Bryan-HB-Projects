[Home Page](https://bbennyhb.github.io/Bryan-HB-Projects/) | [Visualizing Government Debt](visualizing-government-debt) | [Critique by Design](Critique-by-Design) | [Final Project Part I](Final-Project-Part-I)| [Columns](https://www.dailycal.org/users/profile/bryan%20hernandez%20benitez/) 


# Outline

## Purpose:
Regions across the United States are dealing with the reality of climate change: increases to temperatures year over year. Research shows that with increasing annual temperatures, the duration of heat-driven seasons also increases.
In essence, summers are getting hotter and longer. Rising temperatures are especially dangerous for highly populated cities with dense urban centers. High temperatures in dialogue with urbanized areas are susceptible to heat island effects, a byproduct of climate change and urbanization that results in urban areas facing 1-7 degrees Fahrenheit higher than temperatures in outlying areas.
In summary, my project focuses on finding the right locations to build green spaces to lower high temperatures in dense cities.
As city residents, it's understandable to want lower temperatures and more parks so that city residents can enjoy going outside to romanticize the city without overheating.
This can be done by urging policymakers to build more parks by calling local representatives, attending city council meetings, and spreading the word.

### Why this matters
Think of a heat island as an elevator, crowded given the start of the lunch hour, inside a building without a functioning air conditioning system—during the month of July. 
The elevator will undoubtedly feel hotter than the sparse layout of the building lobby. How much hotter will it feel? About 1-7 degrees hotter.
The effects of heat islands are tangible, costly, and as follows:

- Increased energy consumption
- Elevated emissions of air pollutants and greenhouse gases 
- Comprised human health and comfort
- Impaired water quality

A progression of these effects without proper guardrails would be detrimental to cities across the nation. 
 
### Intended Story Structure

![story_outline](story_outline.jpg)  

In building out the anticipated story structure, the image above is what I hope to follow as I develop my story.



## Initial sketches

Based on the type of data that I plan on using, the following sketches might help drive my call to action. The following can be done using a combination of R, Tableau, and ArcGIS Pro. 

### Sketch One

![income_parks_correlation](income_parks_correlation.jpg)

### Sketch Two

![temp_parks_correlation](temp_parks_correlation.jpg)

### Sketch Three

![network_analysis](network_analysis.jpg)



# The data

The following subheaders and linked sources are what I intend to use as my data sources. The Parks data will give me the number of parks by 


## Weather

Visual Crossing | https://www.visualcrossing.com/weather/weather-data-services/Houston,%20TX?v=api# | Produces a URL link that can be included in R Studio using the read.csv command. The website uses APIs to gather air temperature data for a given location and can filter on assigned dates.
National Centers for Environmental Information | https://www.ncdc.noaa.gov/cdo-web/search | Much like Visual Crossing, this website can retrieve air temperature data for a given location but can also produce precipitation data based on "stations" located in select counties or zip codes. I'm not fully sure if I'll be using this database, but it's good to have in the back pocket.


## Parks

ParkServe | https://www.tpl.org/park-data-downloads | Database of Parks by Location Search, which produces CSV files of the number of parks with associated names.
National Neighborhood Data Archive | https://www.openicpsr.org/openicpsr/project/117921/version/V1/view?path=/openicpsr/117921/fcr:versions/V1.3/nanda_parks_tract_2018_01P_csv_with_readme.zip&type=file | Similar to ParkServe by can filter park data by Census Tract.


# Method and medium

Given the type of data that I plan on using, a number of methods can be used to run statistical analyses and create visualizations. R's capabilities in statistical methods might be the default for the correlation tests whereas ArcGIS Pro is better suited for the Network Analysis to highlight discrepancies between income levels and access to greenspaces. Additionally, Tableau's versatility might serve as the middle ground for both visualizations and analysis, though I presume that Tableau might function as the go-to tool for visualizations that I can't create in R using ggplot of ArcGIS Pro's focus on maps. 
Following our lab on Shorthand and leveraging online tutorials, Shorthand might be the best option for presenting my story.

