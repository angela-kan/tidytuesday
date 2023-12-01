# TidyTuesday (For STA199)
This project deals with the TidyTuesday data from 10/10/2023: Haunted Places in the United States. The link to this data is here: https://github.com/rfordatascience/tidytuesday/tree/master/data/2023/2023-10-10.

<img width="494" alt="image" src="https://github.com/angela-kan/tidytuesday/assets/53543497/77d53b1b-136c-43cf-840d-09e55ee9fff8">


The visualization I created is a Choropleth Map that displays the number of haunted locations across the United States. The data from the TidyTuesday repo, haunted_places.csv, is a table where each row represents a haunted location. The rows incluude variables that describe geographic data (city, country, state, state_abbrev, longitude, latitude, city_longitude, city_latitude) as well as variables that descibe the location (description, location). I calculated the number of haunted sites in each state to create the Choropleth Map. What immediately stands out is that California appears to have the highest number of haunted locations by far, followed by Texas and Pennsylvania. It seems that a larger number of haunted locations are present to the Northeast of the United States, making California an interesting datapoint since it strays from the trend. To create this visualization, I learned how to use tmap for thematic mapping by following this tutorial from Duke: https://map-rfun.library.duke.edu/031_thematic_mapping. 

Notes: Worked in the STA199 container and had to install the tigris package.
