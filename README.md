# Title:
### Distribution of trees in NYC by zip code
--- 2018 Visualization Project CUSP

# Team members

Cheng Ma       NetID: cm4692

Hao Xi     NetID: hx517

# Objectives of the project
#### a brief context of the project, and what tasks you're aiming to solve using visualizations, domain(target user) and task abstraction.
Many people are interested in the plants around the city. What the species they are? If the trees ara healthy? What about the years, maintanance and distribution of them? So we decided to plot all the trees in NYC.

What you can do in our visualization:

- 1.Select your address and understand the trees around you. 

- 2.Get the distribution for all kinds of New York Trees directly. 

- 3.Know the numbers of trees within each zip code area.

#### a brief overview of our website


![Alt text](screenshot1.png)

![Alt text](screenshot2.png)


# Datasets involves

NYC Trees Distribution.      Link: https://data.cityofnewyork.us/api/views/uvpi-gqnh/rows.csv?accessType=DOWNLOAD

NYC Zipcode Shapefile.       Link: https://data.cityofnewyork.us/Business/Zip-Code-Boundaries/i8iw-xf4u

# Objective of the project

The type of our visualization is Choropleth Geospatial Map & Distributing points

Interactions:

- Users can select different species and know the distribution of that kind of trees in different zip code area. 
There is more trees in dark green area than in light green area.

- Users can make a selection on map as a circle with mobilable center and fragile edge, you can see the trees within the circle.


# Outcome and Evaluation

With our visualization, users can realize the distribution of every kind of trees in NYC by zip code. 
If you want to view the cherries in spring, you could easily know which zipcode area is most abundant with cherries.
And you can know the trees information around your address, just move the circle and select a proper edge.

# Visualization Tools Used
This data visualization uses D3.js, flask, altair, carto api, python.

# Link to the visualization 
check our website [here](http://macheng1994.pythonanywhere.com) ! 

# Possible future work
- add ability to show details of trees maintanance, years and healthy condition.
- give more detailed trees instruction.
- combine with other demographic data.





