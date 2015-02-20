Homework 4 (parts 1-5)
Kevin Gong (kg2445)
Due 11/20/14



1.

We'll be making a simple choropleth map of per-capita income
by state in the US. Hovering over a state on the map will
show the name of the state as well as the per-capita income
for that state. The data is from the US Census Bureau's 2014
datasets. As with many choropleth maps, states with higher
per-capita income will have a darker shading.


2.

The data will consist of 2 columns: one with the names of
the states, and another with the per-capita income of
each state. 


3.

(see income.csv tab)

or please find the csv here: http://bit.ly/1F1AZYQ


4.

See index.html tab


5.

Steps (we'll be using GeoJSON):

1) load our data (done!)
2) use var map and mapbox to get a basic states map
3) add color to the states based on their per-capita income using ColorBrewer
4) create a function that changes the fillColor of each state so that it 
   depends on the per-capita income
5) add a mouseover event and a mouseout event (reset to default map using
   geojson.resetStyle)
6) create a custom control so that the info that appears when hovering over
   a new state changes
7) add CSS to make control look nice













