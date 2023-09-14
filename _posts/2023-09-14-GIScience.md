---
title: "GIS: Science or Tool"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - GIS
  - GIScience
---

Geographic Information Systems (**GIS**) brought large and easily analyzed spatial data to the world of geography, introducing a host of powerful applications for research, commercial, and organizational fields. As GIS gained prominence, academia posed the question: Is GIS a distinct science in its own right, or just a powerful tool that can be used to advance scientific exploration? This ambiguity has led to the emergence of three distinct schools of thought among GIS users.

**1. GIS as a Tool:** Some argue that GIS is primarily a tool, it can be used to facilitate research and further scientific exploration, but lacks distinction from similar fields to situate itself as a stand alone science.

**2. GIS as a Science:** On the other end of the spectrum are those who see GIS as a science in itself. They view GIS science as a communal effort to ask and answer spatial questions about our world. They believe that the reproducible and replicable process of avoiding spatial errors, developing and testing new spatial tools/algorithms constitutes GIS as a science. GIS now dominates the methods in which geographical information is gathered, managed and implemented. (Wright, 1993). 

**3. The Gray Zone:** Here the line between science and tools is blurred. Some acknowledge GIS as science but see it as inherently connected with geography and computer science. Others claim the tool-building and engineering of the software constitutes science while the use does not. 

My GIS experience started with Google Earth Engine (GEE), a cloud based platform for remote sensing. Here, all projects with this platform used GIS as an educational tool and did not constitute science. I went on to gain familiarity with QGIS as a tool for cartography and as another educational tool for a human geography class, again, neither as science. 

I first used GIS as a tool for science while working as a research assistant for Professor Erin Eggleston of Middlebury College’s microbiology department. I was to assemble a method to identify the spatial extent of lake ice over 20+ years of landsat imagery for analysis alongside Eggleston's in-situ lake microbe data. Here, I adapted an existing GEE code script (Yang et. al 2020) to a GEE app that can extract 20+ years of lake ice data with a drop of a pin. During the course of this project we tested for accuracy and confidence in our model and explored possible alternative source codes to create an accurate as possible ice model. While this project used GIS as a tool, the mutability, communal enterprise, and reasearch question expanded the scope of GIS as just a tool. 

My work this summer with the environmental remote sensing group SkyTruth fell somewhere in between the spectrum of GIS as a tool and GIS as a science. I spent a few weeks creating an automated tool that would tile and feed satellite imagery into a coworker’s machine learning neural network model to identify oil well pads. Once run through the machine learning model the tool would stitch and georeference the images using GDAL python API. While I wouldn't qualify this project as science, I was aiding in the creation of new tools for others to use; several iterations of the script needed to be written before it could be successfully implemented and it was a communal enterprise. This likey falls within the gray zone of toolbuilding. 

Ultimately, the perception of GIS as a tool or science hinges on the user's purpose (Rao, 1993). As a student, I employed GIS as a tool for learning projects. In my role as a researcher, I engaged in scientific pursuits by using GIS to address spatial questions. In the geospatial workforce, I found myself operating within the ambiguous territory between GIS as a tool and GIS as a science. Personally, I embrace this ambiguity and believe that allowing GIS to exist in this gray zone offers the most opportunities for relevant applications and scientific discoveries.

Sources: 
NASEM (National Academies of Sciences, Engineering, and Medicine). 2019. *Reproducibility and Replicability in Science*. Washington, D.C.: National Academies Press. DOI:10.17226/25303

Wright, D. J., M. F. Goodchild, and J. D. Proctor. 1997. GIS: Tool or science? Demystifying the persistent ambiguity of GIS as “tool” versus “science.” *Annals of the Association of American Geographers* 87 (2):346–362. DOI:10.1111/0004-5608.872057

St. Martin, K., and J. Wing. 2007. The discourse and discipline of GIS. *Cartographica* 42 (3):235–248. DOI:10.3138/carto.42.3.235-248


