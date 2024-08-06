# Leaflet Challenge: Earthquake Visualization

## Overview

This project visualizes earthquake data provided by the United States Geological Survey (USGS) using Leaflet.js within a Jupyter Notebook. The visualization includes markers representing earthquakes, with their sizes corresponding to magnitude and colors corresponding to depth. Additionally, a legend and optional tectonic plates data overlay are included.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/leaflet-challenge.git
    ```

2. Navigate to the project directory:
    ```bash
    cd leaflet-challenge
    ```

3. Install the required Python packages:
    ```bash
    pip install folium requests branca
    ```

## Features

### Part 1: Earthquake Visualization

- **TileLayer**: Loads the base map using Leaflet.js.
- **Earthquake Markers**: Plots markers for each earthquake, with:
  - Size based on magnitude
  - Color based on depth
  - Popup with information about location, magnitude, and depth
- **Legend**: Shows the color scale for depth levels.

### Part 2: Optional - Tectonic Plates Data

- **Tectonic Plates Overlay**: Adds tectonic plates data to the map.
- **Layer Control**: Allows toggling between different base maps and overlays.
