Leaflet Map with Current Location, Point Selection, Distance, and Area Calculation
This project is an interactive web application that uses Leaflet.js to display a map with additional functionality for:

Getting the user's current location.
Selecting points on the map and calculating the distance between them.
Drawing polygons and calculating the area enclosed.
Saving, loading, and deleting markers and polygon data.
Features
Map Integration:
The map is rendered using the Leaflet.js library with OpenStreetMap tiles.

Current Location:
The application can locate the user's current position and display it on the map.

Distance Calculation:
Users can place multiple markers on the map, and the app calculates the total distance between them.

Area Calculation:
Users can draw polygons to calculate the enclosed area using Turf.js.

Data Persistence:
The app supports saving, loading, and deleting markers and polygon data using localStorage.

Interactive UI:

Saved data can be loaded or deleted via a dropdown menu.
Current distance and area are dynamically displayed.
How to Use
1. Initial Setup
Open the application in a modern web browser.
The map will attempt to fetch your current location. Allow location access if prompted.
2. Adding Markers
Click the "Marker" button in the map's toolbar.
Click anywhere on the map to place markers.
If more than one marker is added, a dotted line connects them, and the total distance is displayed in meters.
3. Drawing Polygons
Click the "Polygon" button in the toolbar.
Draw a polygon by clicking to place vertices.
Double-click to finish the polygon.
The area enclosed by the polygon is displayed in square meters.
4. Saving Data
Click the Save Data button to save the current markers and polygon.
Data is stored in localStorage and timestamped for easy identification.
5. Loading and Deleting Data
Select a saved data entry from the dropdown menu.
Click Load Data to restore markers and polygons to the map.
Click Delete Data to remove the selected entry from localStorage.
Technical Details
Libraries Used
Leaflet.js:
Used for interactive map rendering.
Leaflet Draw:
Provides drawing tools for markers and polygons.
Turf.js:
Used for geospatial calculations like area and distance.
File Structure
plaintext
Copy code
index.html       - Main HTML file with embedded JavaScript
style.css        - CSS styles for the map and UI elements
Local Storage Format
Data is stored as an array of entries in the browser's localStorage. Each entry contains:

markers: Array of coordinates ([longitude, latitude]) for all markers.
polygon: Array of coordinates ([longitude, latitude]) defining the polygon vertices.
timestamp: A human-readable timestamp of when the data was saved.
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/leaflet-map-project.git
Open index.html in a browser to view the application.
Demo
To see the app in action, visit: Demo Link
(Replace # with your deployed application link, if hosted)

Screenshots
Map Interface

Saved Data

Future Enhancements
Add support for exporting data as JSON files.
Enable user authentication to store data on a server instead of localStorage.
Provide measurement units in imperial (miles, acres) for regions where applicable.
License
This project is licensed under the MIT License.

Feel free to use, modify, and distribute as per the license terms.

Contribution
If you want to contribute:

Fork the repository.
Create a new branch for your feature/bugfix.
Submit a pull request.
