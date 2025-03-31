Bicycle Tracker
===============

Overview
--------

The Bicycle Tracker is a web application for real-time bicycle tracking that uses GPS and accelerometer data to monitor the user's location, speed, and heading. It features an interactive map with light and dark themes, dynamic updates, and reverse geocoding to display nearby cross streets.

Features
--------

*   **Real-Time Location Tracking**: Uses GPS to track the user's location and display it on an interactive map.
    
*   **Speed Calculation**: Combines GPS speed with accelerometer data for improved accuracy.
    
*   **Heading Display**: Shows the user's heading direction using a rotated map marker.
    
*   **Dynamic Map Updates**: The map recenters on the user's location every 2 seconds if the position changes significantly.
    
*   **Reverse Geocoding**: Fetches and displays nearby cross streets using OpenStreetMap's Nominatim API.
    
*   **Light and Dark Themes**: Allows users to toggle between light and dark map themes.
    
*   **Responsive Design**: Optimized for both portrait and landscape modes with a transparent info card.
    

Installation
------------

1.  git clone https://github.com/your-username/bicycle-tracker.git
    
2.  cd bicycle-tracker
    
3.  Open index.html in your browser to run the app.
    

Usage
-----

1.  Click the **Start Tracking** button to begin tracking your location.
    
2.  View your current speed, heading, and nearby cross streets in the info card.
    
3.  Toggle between light and dark themes using the switch in the top-right corner.
    
4.  The map will automatically recenter on your location as you move.
    

Requirements
------------

*   A modern web browser with support for:
    
    *   Geolocation API
        
    *   DeviceMotion API
        
    *   JavaScript ES6
        
*   Internet connection for map tiles and reverse geocoding.
    

Known Limitations
-----------------

*   **Indoor Environments**: GPS accuracy may degrade indoors, and the app may rely more on Wi-Fi or cellular networks.
    
*   **Battery Usage**: High accuracy mode and frequent updates may consume more battery power.
    
*   **Device Compatibility**: The DeviceMotion API may not be supported on all devices.
    

License
-------

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
---------------

*   [Leaflet](https://leafletjs.com/) for the interactive map.
    
*   [OpenStreetMap](https://www.openstreetmap.org/) for map tiles and reverse geocoding.
    
*   [Leaflet Rotated Marker](https://github.com/bbecquet/Leaflet.RotatedMarker) for marker rotation support.
