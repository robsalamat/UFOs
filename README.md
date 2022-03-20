# UFOs

## I. Overview of Project

### Background
Dana wants to showcase her hometown that's famous for UFO sightings. She works on a JS file of UFO sightings data, and presents the information in a dynamic table in her webpage.

### Objective
Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date will be table filters for the city, state, country, and shape.


## II. [Results](index.html)

![](Static/images/webpage.PNG)

The **dynamic table on the right** will change and only show **relevant data** according to inputs typed on the **filter 
parameters on the left.** 

We can filter data using only one  or up to all of the parameters (Date, City, State, Country, Shape). Shown below is an example of sightings filtered using Ontario (state) and Canada (Country):

![](Static/images/search_result.PNG)


## III. Summary

While the webpage is functioning well, there are still some points for improvement.

### A. Limitations 

- The data is constrained to the avaialable data set.

- The inputs are case sensitive, so any wrong capitalization will not give the desired data.

- We cannot see the availabilities of the inputs for filtering. There will be states, cities, etc. with no sighting records but we will just know it once we type it in. 


### B. Recommendations

- There should be a webscraping function that updates the data. 

- The filters can have dropdown options to avoid case sensitivity mistakes and unavailable data.
