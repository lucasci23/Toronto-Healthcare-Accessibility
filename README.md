# Toronto-Healthcare-Accessibility

This project analyzes geographic accessibility to hospitals across Toronto using Geographic Information Systems (GIS). It focuses on measuring the shortest-path distance from each Forward Sortation Area (FSA) to the nearest hospital, visualizing patterns of health service distribution and potential inequities in access.

### Objectives
1. Quantify and visualize the proximity of each Toronto FSA to nearby hospitals using spatial analysis and road networks.
2. Identify geographic disparities in access to healthcare infrastructure.
3. Combine geographic and demographic data to explore health equity across different Toronto regions.

### Key Features
1. GIS-Based Distance Analysis: Computes centroid-to-hospital distances using both Euclidean and shortest driving paths.
2. Data Visualization: Choropleths, heatmaps, and network maps to depict hospital density and proximity by FSA.
3. Equity Lens: Integrates census data (median income, visible minority proportion) to highlight healthcare access disparities.
4. Toronto-Focused: Custom analysis using OpenStreetMap and Statistics Canada data for Toronto.

### Tools & Libraries
1. geopandas for spatial data handling
2. osmnx for road network and routing
3. folium and matplotlib for interactive and static visualizations
4. seaborn for heatmaps
5. rioxarray and mapclassify for raster and choropleth support

### Data Sources
1. OpenStreetMap — Hospital and clinic locations
2. Statistics Canada — FSA boundaries and census data
3. Course Datasets (via GitHub) — Pre-processed hospital and census info

### Visual Outputs
1. Choropleth Maps: Hospital proximity scores by FSA
2. Heatmaps: Distance matrix between FSAs and hospitals
3. Network Map: Road network with hospital overlay
4. Labeled Access Map: Visualizes FSAs with nearest hospital distance and FSA codes
