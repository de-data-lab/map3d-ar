# map3d-ar
Mapping application in 3D.

## Overview
This application maps point data as 3D towers with variable height, positioned across the state of Delaware.

   Each tower represents a cluster of data points, and the height of the tower corresponds to the number of points.  
   In a typical 2D map with clustering, the greater the number of points within an area, the larger the circle,  
   but in this map, the greater the number of points, the taller the tower.  

In this map, there are two datasets:
* Roadway intersections data in Delaware as of August 2021 - from the DE Open Data Portal (<https://opendata.firstmap.delaware.gov/datasets/delaware::delaware-intersections-2-0/explore>)
* Vehicular crashes data within 2022 - from the DE Open Data Portal (<https://data.delaware.gov/Transportation/Public-Crash-Data/827n-m6xc>)

Either, both, or neither of these datasets can be toggled on and off using the tool panel at the right edge of the screen.
Just click the '>' arrow on the right edge of the screen, and the tool panel will slide out.

## Live Demo
View the live demo of [3D map of intersections and crashes](https://de-data-lab.github.io/map3d-ar/build-html/map_traffic.html)
