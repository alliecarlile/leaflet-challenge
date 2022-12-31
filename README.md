Background

https://alliecarlile.github.io/usgs-earthquake-map/

The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

For this project, I developed a way to visualize USGS earthquake data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

This project was completed using the following workflow:

Part 1: Create the Earthquake Visualization

Part 2: Gather and Plot More Data (Optional)

Part 1: Create the Earthquake Visualization
2-BasicMap

Visualizing earthquake dataset:

Get your dataset. To do so, follow these steps:

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON FeedLinks to an external site. page and choose a dataset to visualize. The following image is an example screenshot of what appears when you visit this link:
3-Data

When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization. The following image is a sampling of earthquake data in JSON format:
4-JSON

Import and visualize the data by doing the following:

Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.

Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.

Include popups that provide additional information about the earthquake when its associated marker is clicked.

Create a legend that will provide context for your map data.

Your visualization should look something like the preceding map.

Part 2: Gather and Plot More Data (Optional)
Plot a second dataset on your map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in this dataset and visualize it alongside your original data. Data on tectonic plates can be found at https://github.com/fraxen/tectonicplatesLinks to an external site..

5-Advanced

Perform the following tasks:

Plot the tectonic plates dataset on the map in addition to the earthquakes.

Add other base maps to choose from.

Put each dataset into separate overlays that can be turned on and off independently.

Add layer controls to your map.

![earthquakemap](https://user-images.githubusercontent.com/105824024/208499282-9c450fc5-6fe7-42d4-a02c-bf281508a002.png)


**Methods used:**

HTML

CSS

JavaScript

Leaflet.js

API keys


