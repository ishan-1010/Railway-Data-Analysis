# Railway Data Analysis

This repository contains code snippets for analyzing railway data using Python and various libraries such as `pandas`, `plotly`, and `folium`. The code snippets perform different analyses on railway data including visualization of train schedules, station statistics, geographical mapping of stations, and route planning.

## Code Snippets

1. [Visualization of Station Data](#visualization-of-station-data)
2. [Train Count by Zone](#train-count-by-zone)
3. [Distribution of Departure Hours](#distribution-of-departure-hours)
4. [Busiest Train Stations](#busiest-train-stations)
5. [Analyzing Railway Network in Himachal Pradesh](#analyzing-railway-network-in-himachal-pradesh)
6. [Filtering GeoJSON Data](#filtering-geojson-data)
7. [Geographical Mapping of Stations](#geographical-mapping-of-stations)
8. [Interactive Railway Map of India](#interactive-railway-map-of-india)
9. [Route Planning](#route-planning)
10. [Station Statistics](#station-statistics)
11. [GeoJSON Data Visualization](#geojson-data-visualization)

### Visualization of Station Data

This code snippet reads a CSV file containing station data and visualizes the stations on a map using the `folium` library. It filters out stations with missing coordinates and creates circle markers for each station with tooltips. 

### Train Count by Zone

This code snippet analyzes train data and calculates the count of trains in each zone. It uses the `pandas` library to read a JSON file containing train data and creates an interactive bar chart using the `plotly` library to display the train count by zone.

### Distribution of Departure Hours

This code snippet analyzes train schedule data and plots the distribution of departure hours using the `pandas` and `plotly` libraries. It filters out rows with null or invalid departure times, extracts the hour component from the departure times, and creates an interactive histogram.

### Busiest Train Stations

This code snippet analyzes train schedule data and calculates the count of trains at each station. It uses the `pandas` and `plotly` libraries to group the data by station and create an interactive bar chart of the busiest train stations.

### Analyzing Railway Network in Himachal Pradesh

This code snippet analyzes railway network data in Himachal Pradesh. It reads station and train data from CSV and JSON files, merges the datasets, and generates a scatter plot using the `plotly` library to visualize the busiest junctions in Himachal Pradesh.

### Filtering GeoJSON Data

This code snippet demonstrates how to filter GeoJSON data based on specific criteria. It reads a GeoJSON file containing Indian state boundaries, filters the features for a specific state (Himachal Pradesh), and saves the filtered data to a new file.

### Geographical Mapping of Stations

This code snippet reads station data from a CSV file, filters the data for a specific state (Himachal Pradesh), and visualizes the stations on a map using the `folium` library. It creates circle markers for each station with tooltips and differentiates between main busy stations and other stations using marker colors.

### Interactive Railway Map of India

This code snippet creates an interactive map of Indian railway stations using the `folium` library. It reads station data from a CSV file, filters the data for stations in Himachal Pradesh, and visualizes the stations on a map centered around North India. It also adds the boundary of Himachal Pradesh to the map.

### Route Planning

This code snippet performs route planning for Indian railways. It reads train, schedule, and station data from CSV and JSON files and provides a function to plan the shortest route between two stations. It finds trains departing from the source station, checks if they pass through the destination station, and selects the train with the shortest route.

### Station Statistics

This code snippet analyzes station data and calculates the number of stations in each state and zone. It reads station data from a CSV file using the `pandas` library and calculates station counts by state and zone.

### GeoJSON Data Visualization

This code snippet reads a GeoJSON file containing Indian state boundaries, generates random colors for each state, and visualizes the states on a map using the `folium` library. It creates a choropleth map with different colors for each state.

## Requirements

The code snippets require the following libraries:

- `pandas`
- `plotly`
- `folium`

Make sure to install these libraries using the following command:

```
pip install pandas plotly folium
```

## Usage

To use the code snippets, follow these steps:

1. Clone the repository or download the code snippets.
2. Make sure you have the required libraries installed.
3. Run each code snippet individually and observe the output.

Please note that the code snippets assume the presence of specific input files (CSV, JSON, GeoJSON) in the specified file paths. Make sure to adjust the file paths accordingly or provide the correct file paths to avoid any errors. 

Feel free to modify and customize the code snippets according to your requirements.


## Illustration
<img width="413" alt="Himachal Rail Network" src="https://github.com/ishan-1010/Railway-Data-Analysis/assets/98383932/01a9a4b9-f3e4-40f1-91af-036165739236">

