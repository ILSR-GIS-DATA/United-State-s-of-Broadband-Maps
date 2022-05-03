# United-State-s-of-Broadband-Maps
Map displays data granularity of state broadband maps and links to the state map webpages. 

# Map Methodology
Our search for state-wide broadband maps involved a Google search for "state-name + broadband" or "state-name + broadband map." We considered maps "up-to-date" if they included FCC 477 or other data sources that were dated 2020 or later. Then, each state map was evaluated in terms of the types of data displayed. We categorized and displayed the most precise data used in each state map and displayed four data categories in our final map that include (in order from most detailed to least detailed): 
1. Broadband Serviceable Locations (BSLs) 
2. household speed test data 
3. privately shared ISP service areas 
4. FCC 477
5. No up-to-date map available - included states that have no publicly shared map or have no map with current data (i.e., 2020 or later). 

It is important to note that many states include a combination of these data sources in their maps, however, we only sought to highlight the most precise data source that was included in the map. 

# US_BroadbandMapsData.csv
The data that were used to create the map can be found in this csv file. 
STATEFP and GEOID: Individual state identification numbers  
NAME: State name  
GranularityFeatures: Short description of the data type that is used in the map.  
GranularityScore: A numeric value representing the GranularityFeatures.  
MapDetails: A more detailed description of the state broadband map(s) that are publicly available. When more than one map was available, we numbered the description.  
MapLink: The weblink to the primary state broadband map  
MapLink2: the weblink to the secondary state broadband map (where applicable). 