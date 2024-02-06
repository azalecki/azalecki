---
title: "Dealing with Geographic Threats to Validity"
categories:
  - GIScience Blog
tags:
  - project validity 
  - shape effects 
  - gis
---

One of the most significant threats to validity that I can think of regarding my independent project is the idea of edge/shape effects when creating polygons to represent library service/catchment areas. Visualizing catchment areas for libraries is my first objective because, unlike primary schools that have definite attendance boundaries, libraries do not have proper "service areas." In the past, Thiessen/Voronoi polygons have been used to map catchment or service areas by proximity to points. As explained by Flitter et al, GIS tools that generate Thiessen polygons draw shapes around a layer of point data where every location within one shape is nearer to its center point than all other points in the layer. These proximal regions assume that people are more likely to visit the library closest to them and as a result library services should reflect their local constituents. I recognize that this method has its flaws because this is not always the case. Some people may frequent libraries outside of their residential neighborhood for a variety of reasons and there is no way of accurately tracking that. The other option would be to draw buffers around library points like in the method we saw in the Kang et al. (year) study or calculate a network analysis. Thiessen polygons are, however, the simpler and computationally less intense option to a full-on network analysis. Although they might seem arbitrary I have attempted to improve the validity by including a population-weighted aggregation to more accurately estimate the neighborhood characteristics of the library service areas. 

References 

Flitter, H., Weckenbrock, P., & Weibel, R. (n.d.). Thiessen Polygon. Retrieved December 16, 2023, from http://www.gitta.info/Accessibilit/en/html/UncProxAnaly_learningObject4.html

