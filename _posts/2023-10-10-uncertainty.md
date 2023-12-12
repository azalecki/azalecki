---
title: "Dealing with Uncertainty in GIS"
categories:
  - Blog
tags:
  - GIS
  - uncertainty
  - error 
---

A couple of days ago, I started developing a potential methodology for investigating neighborhood-level characteristics to examine how library services vary across different socioeconomic landscapes. GIS is a useful tool for examining landscapes of socioeconomic unevenness or highlighting spatial patterns of social inequality. After all, using GIS for this reason is what got me into Geography. However, in this slow and arduous research process, I have run into some challenges. 
While considering the different GIS tools at my disposal I kept coming back to this quote: 

> "The way in which we conceive of a geographic phenomenon very much prescribes the way in which we are likely to set about measuring and representing it"(Longley et al, 2008). 

When writing this blogpost I had already spent most of my day sifting through dozens of Census shapefiles and library point data. Sitting in a computer lab for hours on end is bound to make you a little philosophical. I just couldn't stop thinking about this gap between perception, reality, and its representation. From my first GIS class, I was taught that a completely accurate rendering of Earth’s geography is tricky. Maps are representations rather than the truth. They often lie. **So, how can I, to the best of my ability, accurately represent reality?**

For example, let's consider library service areas in Vermont. Unlike attendance boundaries that are used for primary school enrollment, libraries don't have specific delineated geographic extents of use. Definitions of library service areas are vague and ambiguous. This makes perfect sense when you consider libraries' functions as public places but makes GIS analysis a little fuzzy. Just because there is a library in Bristol, town residents may choose to travel the extra mile to Middlebury for services that Bristol’s library doesn’t offer. As GIS analysts we have to make *assumptions* and then *decisions* on how to proceed with the data we have at our disposal. 

Another issue is the data and the instruments of analysis that are available to us. If no shapefile exists for library service areas, I have to delineate those catchment areas. Sometimes there are tools that are right for the job. I can generate Thiessen polygons from the QGIS processing toolbox but is that the right tool for the job? Considering the limitations of these tools and issues like positional errors is critical. 

This gets even more complicated when you consider that geographies vary. The physical and social landscape changes depending on whether you're looking at rural Illinois or bustling Budapest. We can be extra careful while handling data, observe the results at different scales, and use statistics to try to calculate the precision of our estimates. Being aware of the limitations and clearly explaining our rationale for certain methods are steps I can take toward a more certain use of GIS. Offering a foolproof plan to avoid uncertainty in GIS is unrealistic but being transparent about the limitations of the tools we are using isn't.

References
 
Longley, P. A., M. F. Goodchild, D. J. Maguire, and D. W. Rhind. 2008. Geographical information systems and science 2nd ed. Chichester: Wiley.
 
