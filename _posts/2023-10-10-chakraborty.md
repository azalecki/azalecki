---
title: "Chakraborty(2021) Reproduction"
categories:
  - Blog
tags:
  - GIS reproduction
---

For our first assignment in Open GIScience, as a class, we worked on contributing to the reproduction of [“Social inequities in the distribution of COVID-19: An intra-categorical analysis of people with disabilities in the U.S.” by Dr. Jayajit Chakraborty (2021)](https://www.sciencedirect.com/science/article/pii/S1936657420301394?via%3Dihub). Let me tell you that this process was surprisingly more difficult than I had anticipated. Not only did I have to intimately learn the methods of the study but also new software since Professor Holler’s reproduction was conducted in R, a programming language that I had never used before. Programming language barrier aside, I was able to contribute to this reproduction by improving aspects of the data visualization in the report. I troubleshooted a code issue regarding a missing table as well as updated the color ramp for the Race Model Weights by County map to enhance legibility. I was personally interested in the effectiveness of the models used in the study and wanted to expand upon the map of Race Model Residuals. To see how the spatial distribution of error changed depending on what model was used I created 3 other maps of the residuals for the other models that weren’t mapped. 

I still think there is a lot of work to be done to make this study better. One element that I wanted to study but couldn’t figure out was how to test for independence. Clusters were grouped up into states and Chakraborty assumes that there is a possible correlation within clusters(states) but not between clusters. I was thinking about certain metropolitan areas that cross over state boundaries and how there could be a possibility that those counties might exhibit correlations between clusters. I encourage anybody reading this to also consider this if they are interested in reproducing this study. You can access the report [here](https://azalecki.github.io/RPr-Chakraborty-2021/) which can also be found in this [GitHub repository](https://github.com/azalecki/RPr-Chakraborty-2021). 

