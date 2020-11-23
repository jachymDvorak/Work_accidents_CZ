# Work accidents in Czechia - comparing Brno + Moravskoslezský region with Praha + Středočeský region.

I compared the yearly amount of work accidents in these two regions with the unemployment rates. I excluded years that had missing data. Data was collected from the Ministry of Health of the Czech Republic [open data catalogue.](https://opendata.mzcr.cz/)

All files can be found in the datasets folder.

As can be seen below, unemployment somehow seems to relate to work accidents. As one would expect, if unemployment gets higher, as less people are working, work accidents may plummet. With that said, it seems like the data is of questionable quality, as it seems to have unreasonably high spikes year after year, and possibly unexplainable differences in regions. My guess is that the process of collecting the data is not fully standardized.

![Plot of work accidents](https://github.com/jachymDvorak/Work_accidents_CZ/blob/main/plot_accidents.jpg?raw=true)

# Choropleth map using GeoJSON Czechia region data and work accidents 

I collected JSON data for Czechia regions and plotted average work accidents in years 1995 - 2017 (excluding 2014 and 2015 due to missing data).

![Plot of work accidents](https://github.com/jachymDvorak/Work_accidents_CZ/blob/main/Accidents_in_Czechia.png?raw=true)

All files can be found in the datasets and geodata folders.
