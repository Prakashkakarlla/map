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

![Map Screenshot](https://github.com/Prakashkakarlla/map/blob/main/Assets/Distance%20map.png)

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
   git clone https://github.com/Prakashkakarlla/map


2. Clone the repository and navigate to the project directory:
   ```bash
   cd map

3. Open index.html in your preferred web browser to view the project.

## Project Structure
### File Details

- **`index.html`**: The main HTML file containing the structure and functionality of the map application.
- **`README.md`**: The project documentation file, providing an overview and usage instructions.
- **`assets/`**

---

## Usage

### Start the Map
- Open the web application in your browser.
- The map will automatically center on your current location (if location permissions are granted).

### Add Markers
- Use the marker tool from the map controls to place markers on the map.
- The application calculates the distance between the markers in real time.

### Draw Polygons
- Use the polygon tool to draw shapes on the map.
- The application calculates and displays the area of the polygon in real time.

### Save and Load Data
- Save the current markers and polygon data using the **Save Data** button.
- Reload previously saved data using the dropdown menu and **Load Data** button.

### Delete Data
- Remove saved data using the **Delete Data** button.
