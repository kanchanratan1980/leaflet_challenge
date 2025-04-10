# leaflet_challenge
 Project Title:
Leaflet Challenge – Part 1: Earthquake Visualization

 Description:
This project uses Leaflet.js and D3.js to visualize real-time earthquake data from the USGS. It displays circle markers for each earthquake based on:

Magnitude → Marker size

Depth → Marker color

Location → Clickable popups

A legend explains color coding based on depth.  
 Folder Structure:


leaflet-challenge/
├── Leaflet-Part-1/
│   ├── index.html
│   └── static/
│       ├── css/
│       │   └── style.css
│       └── js/
│           └── logic.js
index.html – Entry point for the map

style.css – Full-screen map styling

logic.js – JavaScript logic for map creation and data visualization

 Live Data Source:
Earthquake data from USGS GeoJSON :
https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php

 How to Run This Project Locally  

 Option 1: Open Locally (No Install Needed)
Download the entire folder Leaflet-Part-1/ from this repo.

Open index.html in a web browser (Chrome recommended).

You will see the interactive map with earthquake data.

 Option 2: Clone via GitHub
If you use Git:

git clone https://github.com/kanchanratan1980/leaflet_challenge  

Then, open index.html in a browser.  

 Option 3: Use VS Code + Live Server (Recommended)
Open the folder Leaflet-Part-1 in Visual Studio Code

Install the Live Server extension

Right-click index.html → Click "Open with Live Server"
 Code Acknowledgment & Attribution
External Help & Code References:

Logic for marker size, color, popups, and legends was guided by:

Previous Class activities 

Leaflet documentation – https://leafletjs.com


Files with External Logic:

Leaflet-Part-1/static/js/logic.js:

Functions: getColor(), getRadius(), styleInfo()

GeoJSON layer with onEachFeature and popups

Legend control setup with depth color scale

 
