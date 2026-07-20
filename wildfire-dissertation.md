# Lightning-Ignited Wildfires in Canada 2010-2024: A Spatiotemporal Analysis
## 🌍Overview 
This project investigates the spatial and temporal dynamics of lightning-ignited wildfires across Canada between 2010 and 2024, using GIS, statistical analysis in MATLAB and multiple large geospatial datasets 

The study integrates national-scale geospatial lightning, wildfire, and climate datasets to examine:

- Spatial and temporal patterns in lightning occurrence
- Spatial and temporal patterns in burned area
- Climatic drivers of wildfire behaviour
- Changes in Canadian fire season length
- Case study regions (Jasper, 2024; White Rock Lake, 2021)

## 🎯Key Objectives
- Analyse spatial and temporal variation in lightning activity
- Map wildfire hotspots across Canada
- Investigate relationships between lightning, climate oscillations and burned area
- Examine changes in wildfire season length

## 🧠Skills demonstrated
### Technical Skills
- QGIS
- MATLAB 
- Google Earth Engine
### GIS & Spatial Analysis
- Raster analysis
- GeoTIFF generation
- Cartography
- Spatial hotspot analysis
- Digital Elevation Model analysis
### Data Analysis 
- Regression modelling
- Statistical analysis
- Data visualisation
- Processing of large datasets 

## 📊Data 
- Lightning Data: Canadian Convective Parameters and Lightning Dataset v1 (Canadian Government, 2024)
- Burned Area Data: Canadian Fire Spread Dataset (Barber _et al._, 2024)
- Climate Oscillation Data: National Oceanic and Atmospheric Administration monthly measurements (2025)
- Land Classification Data: Operational Land Imager Landsat Sensor Data (Canadian Government Open Data Source, 2020)

## 🛠️Methods 
### MATLAB
- Data cleaning
- Combined 3-hourly lightning data into annual density GeoTIFF maps
- Statistical analysis of lightning frequency against BA and climate indicators, including regression models
- GeoTIFF generation

### QGIS 
- Lightning density maps (annual, total, mean, standard deviation)
- Burned area maps (annual, total, hotspot)
- Case studies: identifying individual lightning strikes, land classification analysis, DEMs (Google Earth Engine)
- 

## 💭Results & Discussion
- Lightning became increasingly spatially diverse
- Lightning occurrence appears to be decreasing, but ignition efficiency is increasing so LIWs are becoming more frequent and severe
- Large- and local-scale climate conditions strongly influence a region's ability to ignite and for the fire to spread
- The Arctic Oscillation, El Nino Southern Oscillation, and the Pacific Decadal Oscillation influence lightning occurrence and burned area
- The Canadian fire season is both starting earlier and ending later, which correlates with a lengthening lightning season
- It is likely that extreme fire years, such as 2023, will become more frequent

## 🗺️Example Figures
<p align="center">
<img src="map.png" width="48%">
<img src="hotspot.png" width="48%">
</p>

<p align="center">
<img src="wrl.png" width="48%">
<img src="wrl2.png" width="48%">
</p>

## ⚙️Challenges
- Analysing national-scale gridded datasets, including the CLDN lightning data, required efficient data handling in MATLAB, where it was exported as a GeoTIFF file to allow further analysis to be conducted in QGIS
- 3-hourly lightning data over a 15-year period required precise scripts to be generated to allow optimal analysis

## 🔮Future Improvements 
- Projections for future wildfires
- More focus on the Arctic and the influence of permafrost degradation
- Interactive web maps/temporal maps
