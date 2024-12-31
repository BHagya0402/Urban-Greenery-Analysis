# Urban Greenery and Building Proximity Analysis in Kingston upon Thames

This project explores urban greenery distribution and evaluates building proximity to trees in "Good" condition within Kingston upon Thames, aiming to provide insights for urban planning and sustainable development.

Project Overview

The analysis includes:

Tree Health and Distribution:

Categorization of urban trees based on health conditions: Good, Reasonable, Poor, and Dead.

Spatial distribution of trees across the borough of Kingston upon Thames.

Ward-Level Insights:

Aggregation of tree condition data by wards.

Identification of wards with limited access to healthy greenery.

Proximity Analysis:

Evaluation of building proximity to trees in "Good" condition.

Classification of buildings into:

Within 100 meters of a "Good" tree.

Beyond 100 meters from a "Good" tree.

Interactive Visualization:

Creation of dynamic maps showing:

Ward boundaries.

Trees categorized by condition.

Buildings classified based on their proximity to "Good" condition trees.

Data Sources

Tree Dataset: Urban tree data including health condition, location, and species.

Building Footprints: Extracted using Overpass API from OpenStreetMap.

Ward Boundaries: London ward boundaries from statistical GIS shapefiles.

Tools and Libraries

Python Libraries:

pandas, geopandas for data manipulation and geospatial operations.

shapely for geometric transformations.

folium for interactive map visualization.

overpy for querying OpenStreetMap data.

Coordinate Reference Systems (CRS):

EPSG:4326 for geographic coordinates.

EPSG:27700 for British National Grid.

Methodology

Data Preparation:

Transform coordinates and harmonize CRS across datasets.

Clip data to the Kingston upon Thames boundary.

Analysis:

Group and count trees by condition and wards.

Compute the nearest tree distance for each building.

Visualization:

Develop interactive maps using Folium to highlight key insights.

Proximity Classification:

Identify buildings within 100 meters of a "Good" tree and those beyond this threshold.

Key Findings

Tree Health Distribution:

Majority of trees are in Reasonable or Good condition.

Uneven distribution of Dead and Poor condition trees.

Ward Analysis:

Wards like Tudor and Coombe Hill have higher counts of healthy trees.

Areas with fewer healthy trees are flagged for intervention.

Building Proximity:

13,615 buildings are within 100 meters of a "Good" condition tree.

13,906 buildings lack proximity to such trees, highlighting areas with potential greenery deficits.
