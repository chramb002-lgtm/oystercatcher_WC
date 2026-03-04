# oystercatcher_WC
GIS Honours assignment
[https://rawcdn.githack.com/chramb002-lgtm/oystercatcher_WC/b9e7c03181e87194eba87529b8e4333844ac5844/WC_oystercatcher.html]

This project looks at the distibution of African Oystercatchers (Haematopus moquini) across the Western Cape Province of South Africa. Observation data has been colour coded by the year in which the observations were made. Data was downloaded into R from iNaturalist, an open source citizen science platform.

Workflow: 
The workflow begins by downloading occurance data from iNaturalist using rinat package. Observations are filtered to ensure data quality is set to research grade, within the boundaries of the Western Cape, and removing observations in captive specimens. The filtered data is transformed into spatial objects using the sf package. Visualisation of their distribution patterns is accomplished through a static map (ggplot2, ggspatial) and an interactive map (leaflet, mapview), allowing individuals to explore observations and temporal patters in osytercatcher distribution across the region.  
