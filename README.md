# Urban Greenery and Proximity Analysis of good condition trees for buildings in Kingston upon Thames

This project analyzes urban greenery in London and includes detailed analysis on tree distribution, tree conditions, and their proximity to buildings for Kingston upon thames brorough. The goal is to assess accessibility to green spaces and highlight areas for potential environmental improvement.

## Overview of Analysis

**1.	Trees Per Capita:**

o	Calculated as the ratio of total trees to ward population for boroughs in London.

o	Highlighted boroughs with higher and lower trees per capita using the Choropleth map

![Urban Greenery Map](https://github.com/BHagya0402/Urban-Greenery-Analysis/blob/main/Greenery_analysis.png)

**2.	Tree Condition Analysis – Kingston upon Thames:**

o	The dataset categorises trees based on their condition (Good, Reasonable, Poor, and Dead).

o	Trees in good condition were identified and mapped for further analysis.

**3.	Spatial Analysis:**

o	The locations of trees were transformed into a GeoDataFrame for spatial operations.

o	Trees were mapped within the boundaries and wards of Kingston upon Thames.

**4.	Ward-Level Aggregation:**

o	Tree counts were aggregated by wards and categorized by condition.

o	A detailed breakdown of tree conditions per ward was generated.

**5.	Building Proximity to Trees:**

o	Using Overpass API, 27,521 building geometries were extracted.

o	Proximity to trees in good condition was calculated for each building.
o	Buildings were classified based on whether they were within 100 meters of a tree in good condition.
