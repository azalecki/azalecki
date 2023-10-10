---
title: "Dealing with Uncertainty in GIS"
date: 2019-04-18T15:34:30-04:00
categories:
  - Blog
tags:
  - GIS
  - uncertainty
  - error 
---

A couple of days ago, I dedicated some time to start developing a method to investigate neighborhood level spatial variations in library services for my senior research project. While considering the different GIS tools at my disposal I kept coming back to this qoute from the Longely reading: 
" The way in which we conceive of a geographic phenomenon very much prescribes the way in which we are likely to set about measuring and representing it" (pg 129)

At this point I had spent most of my day sifting through shapefiles of census tracts and point data. Sitting in a computer lab hours on end is bound to make you a little philosophical. I couldn't stop thinking about this gap between perception, reality and its representation. How can I, to the best of my ability, accurately represent reality? For example, let's consider library service areas in Vermont. Unlike attendance boundaries that are used for primary school enrollment, libraries have specific geographic extent of use. Definitions of library service areas are vague and ambiguous. This makes perfect sense when you consider libraries' functions as public places but makes GIS analysis a little fuzzy. 

As the researcher, how do I conceive of library service areas based on my own experiences? Growing up in Chicago with access to several library branches my perception of library service areas may be more fluid than somebody who only grew up with one. My interpretation might distort representation of library service areas. Next is considering the instruments of analysis. If no shapefile exists for library service areas, I have to delineate those catchment areas. What tool is right for the job? Are Thiessen polygons right for the job or is there a better method out there? 

This gets even more complicated when you consider that geographies vary. The physical and social landscape changes depending on whether you're looking at rural Illinois or bustling Budapest. We can be extra careful while handling data, observe the results at different scales, and use statistics to try to calculate the precision of our estimates. Being aware of the limitations and clearly explaing our rationale for certain methods is the first step towards more certain use of GIS. Offering a full-proof plan to avoiding uncertainty in GIS is unrealistic but being transparent about the limitations of the tools we are using isn't. 
