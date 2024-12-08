# Leaflet Map with Current Location, Point Selection, Distance, and Area Calculation

This project is an interactive web application that allows users to interact with a Leaflet map to perform the following tasks:
- Display their current location on the map.
- Add markers to the map and calculate the distance between them.
- Draw polygons on the map and calculate their area.
- Save, load, and delete marker and polygon data using `localStorage`.

## Features

1. **Current Location:**
   - Automatically centers the map to the user's current location upon loading.

2. **Interactive Tools:**
   - Add markers to the map.
   - Draw polygons to measure the area.
   - Display the distance between selected markers.

3. **Data Management:**
   - Save marker and polygon data to `localStorage`.
   - Load previously saved data onto the map.
   - Delete saved data.

4. **Real-time Calculations:**
   - Calculates distances between markers.
   - Computes the area of drawn polygons using `Turf.js`.

## Demo

![Map Screenshot](https://via.placeholder.com/800x400.png?text=Map+Preview)

## Technologies Used

- **Frontend:**
  - HTML5, CSS3, JavaScript
- **Libraries:**
  - [Leaflet](https://leafletjs.com/) for interactive mapping.
  - [Leaflet Draw](https://leaflet.github.io/Leaflet.draw/) for drawing tools.
  - [Turf.js](https://turfjs.org/) for geospatial calculations.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/leaflet-map-project.git
