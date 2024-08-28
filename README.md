# LULC Change Detection

## About

Land Use and Land Cover (LULC) Change Detection is a critical field of study within the realm of environmental monitoring and geospatial analysis. It focuses on tracking alterations in the way land is utilized and the evolving patterns of surface cover over specific time intervals. For that i use the QGIS Software [QGIS](https://qgis.org/download/).

## Project Aspect

1.Study Area Selection:Choose the geographical area of interest based on the project objectives. Consider factors such as size, ecological diversity, and the relevance of the area to the issues being addressed.
2.Data Sources:Identify and acquire appropriate data sources, such as satellite imagery, aerial photographs, or LiDAR data. Consider the spatial and temporal resolution of the data based on the project requirements.
3.Data Preprocessing:Conduct preprocessing steps, including image calibration, atmospheric correction, and geometric correction, to ensure the accuracy and reliability of the data.
4.Change Detection Methods:Select appropriate change detection methods to compare different time periods. This may involve pixel-based or object-based change detection approaches.
5.Integration with Other Data:Consider integrating LULC data with other relevant datasets, such as socio-economic data or climate data, to provide a more comprehensive understanding of the factors influencing land use changes.

## Software Use
The software requirements are as follows :

QGIS (Quantum GIS):
Role: QGIS is an open-source Geographic Information System (GIS) software that provides powerful tools for spatial analysis, mapping, and data visualization.

Google Earth Pro:
Role: Google Earth Pro is a user-friendly and widely accessible tool that allows users to explore and analyze geospatial data globally. 

Bhoonidhi:
Role: Bhoonidhi is a GIS software developed by the National Remote Sensing Centre (NRSC) in India. It is specifically designed for land management and natural resource monitoring, making it suitable for LULC change detection in the Indian context.

Copernicus (Sentinel Hub):
Role: Copernicus, specifically through the Sentinel Hub, is part of the European Union's Earth Observation program. It provides access to a wealth of Sentinel satellite data, making it valuable for monitoring land changes at a global scale.

### Indices Calculation
QGIS does not have built-in tools for calculating change detection indices directly, but you can achieve this using raster calculator or plugins. Common indices for change detection include :
index‐based built‐up index (IBI) soil adjusted vegetation index (SAVI) normalized difference built‐up index (NDBI) build-up index (BUI) new built-up index (NBI) Built-up Area Extraction Index (BAEI) Urban Index (UI)

## Classification
Land Use and Land Cover (LULC) change detection involves analyzing changes in the types of land use and land cover over time. There are several classification methods used for LULC change detection, each with its advantages and limitations. Here are some common methods:

1.Supervised Classification: This method requires training samples for each land cover class, which are used to train a classifier algorithm. Once trained, the classifier is applied to classify land cover types in the images of different time periods. Changes between classifications indicate land cover change.

2.Unsupervised Classification: In this method, the algorithm identifies clusters of similar pixels without the need for predefined training samples. The user specifies the number of classes desired, and the algorithm groups pixels with similar spectral characteristics. Changes in cluster membership between different time periods indicate land cover change.


### Conclusion

In conclusion, this LULC Change Detection project has provided valuable insights into the dynamic nature of the studied landscape, contributing to a deeper understanding of land use changes over time. Through the integration of advanced geospatial technologies and comprehensive analysis methodologies, we have gained significant knowledge that has implications for environmental monitoring, resource management, and sustainable development.As we conclude this phase of the project, we recognize the need for ongoing research, collaboration, and data-sharing initiatives to address emerging challenges and contribute to the global discourse on sustainable land use practices.
