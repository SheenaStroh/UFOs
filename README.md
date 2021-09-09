# UFO Sightings

## Overview
Now that the UFO sightings website and table are up and running, there are some updates that can be made
that will make the filters even more useful. This will allow users to filter the sightings data by city, state, country, and shape as well as the date.

## Results
The webpage now has dynamic filtering for date, city, state, country, and shape. In order to use the 
filters all you have to do is enter search criteria and then click away from the field you are searching 
on. For example, when you first arrive to the webpage, the filter will look like this and all of the 
data will be visible:
![NoFilter](https://user-images.githubusercontent.com/85318060/132605920-7fc07da8-f303-4650-9779-8e7e0bff37da.png)

If you wanted to filter by shape, only finding triangle sightings for example, you would enter triangle 
into the shape criteria and click away. This would be the result:
![TriangleFilter](https://user-images.githubusercontent.com/85318060/132606068-b01fe23d-82df-424d-b972-14dee0851da3.png)

Then you could filter even farther and narrow it down by state to only sightings in California:
![StateFilter](https://user-images.githubusercontent.com/85318060/132606133-ca7ef453-f1d1-4c6d-97f5-63ee71082a7e.png)

From there you could filter down by any of the other criteria to get to whichever sighting you were 
interested in seeing.

## Summary

Overall the webpage works as expected, and you are able to filter through the results with great 
precision. One drawback of this layout is the fact that you have to match what you are looking for 
exactly within the filter, so if you are looking for sightings in California and you type 'CA', or 
'California', or anything other than 'ca', you won't get any results. So in order to use the filter you 
have to have an understanding of how the data is formatted. One recommendation for further development 
would be to make the filter criteria broader, allow searches with any case or allow for partial 
searches. Another recommendation would be to add a dropdown menu of what is available in certain filter 
criteria, such as the shape, country, or state. Then people could select which sighting they are looking 
for without already knowing how the data is structured.
