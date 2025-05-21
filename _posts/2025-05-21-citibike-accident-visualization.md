---
layout: default
title: "Open-Data Visualizations"
date: 2025-05-21
---

# Open-Data Visualizations

Over the past day, I built a simple interactive map using public data to visualize accident locations in NYC.


The project started from a past homework assignment in my Data Management & Analysis class, where I used a large dataset from [NYC Open Data](https://opendata.cityofnewyork.us/) containing crash reports from 2020. After cleaning the data and filtering for valid borough and location values, I converted it into a GeoJSON format for the browser. 


I used [Leaflet.js](https://leafletjs.com/) to render the map and display each accident as a colored dot. All the points on the map are color-coded by borough and can be clicked to see individual metadata. The entire site is built on plain HTML, CSS, and JavaScript—no external frameworks.


My main goal in building this visualization was to explore civic data in a visual, user-oriented way. I've previously worked with geospatial data and the Google Maps API as a research assistant at the NYU School of Medicine. Still, I wanted to build a standalone website (without logins/libraries) and practice working with such data through JavaScript.


You can [view the interactive map here!](https://navunni.com/citibike-accident-visualization/)


Working with public data helped me think more about how we present existing information. A "simple map" still consists of thousands of data points (~70,000).


I plan to do more short visual projects like this using NYC datasets and civic information APIs. It's a shame Google shut down its Civic Information API last month.

Till next time.