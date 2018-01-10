## Introduction and Learning Goals

In this session we will introduce the concept of "thinking spatially" as well as a few tools and concepts commonly used when engaging in spatial projects.  None of the tools will be covered in depth but rather you will get exposed to several different commonly used tools with an emphasis on the "spatial thinking" required when using these tools.

## Schedule
1. Introduction to mapping and thinking spatially
2. Georeference Historical Map – Map Warper OR David Rumsey
3. Omeka and Neatline
4. Break 
5. Open Refine and Geocoding
7. ArcGIS Online and analysis and publishing
8. Group Discussion

## Workshop Materials
**Websites**  
The Geospatial Revolution http://geospatialrevolution.psu.edu/  
Burrito Source data https://github.com/srcole/burritos  
Georeferencing maps http://davidrumsey.com (create an account to get the most out of the exercise)  
Neatline Mapping http://neatline.org  
Neatline Mapping http://btinker.digitalscholar.rochester.edu/DSI/admin   
U: DSI  
P: dsipass  
Example Neatline Exhibit: http://dslab.lib.rochester.edu/esw/neatline/show/esw-nile  

ArcGIS Online http://arcgis.com  

**Data**  
Burrito Data https://docs.google.com/spreadsheets/d/18HkrklYz1bKpDLeL-kaMrGjAhUM6LeJMIACwEljCgaw/edit#gid=1703829449  
ArcGIS Data - Burrito Geocoded  https://drive.google.com/open?id=1AFHMWuNPhE1L1msinq0RJ04TEzkXN0Xx

**Software and Accounts**  
David Rumsey Map Collection http://davidrumsey.com (create an account)  
OpenRefine (should be installed already for the data visualization course)

**Slides**  
Introduction and Overview https://drive.google.com/open?id=1mITOgssY2OMauZoD_bNl-sj6vvcYn4Pi  
  
Activity- Georeferencing https://drive.google.com/open?id=1nTL05ZlIYuC6g0c98aAFMYdaqVNVLlctcbya6ojVRiM  
  
Activity- Neatline Mapping https://drive.google.com/open?id=1erAlqJrqtT7wagVyQzRLeiNgdyAfEK9mk5UQJ5bW1lQ  
  
Activity- Geocoding in OpenRefine https://drive.google.com/open?id=11MyKjhRJwCnk4mH7xYIPEGkHhMjKhG9B9jFRHZTXosk    
Code for OpenRefine  

"http://nominatim.openstreetmap.org/search?format=json&email=your_email_here&addressdetails=1&polygon=0&limit=1&q="+ escape(value, 'url') + "," + escape(cells.Neighborhood.value, 'url') + escape(", California", 'url')  

value.parseJson()[0].lat  
value.parseJson()[0].lon  

import json, math #import the needed modules
lat = cells["lat"]["value"] #pull the latitude value out of the resulting field
lon = cells["lon"]["value"] #pull the longitude value out of the resulting field
x = math.radians(float(lon))*6378137 #convert the lat and lon to Mercator meters
y = math.log(math.tan(float(lat)*(math.pi/180/2)+math.pi/4))*6378137 
return "POINT(" + str(x) + " " + str(y) + ")" #create the string to put in the coverage field in Omeka




