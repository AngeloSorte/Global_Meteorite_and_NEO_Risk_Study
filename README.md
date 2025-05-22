# Near Earth Objects (NEO) Monitoring and Analysis

This project uses NASA's Near Earth Object Web Service (NeoWs) API to monitor, analyze, and visualize data about asteroids and other objects passing near Earth.

## Notebooks Overview

1. **Historical NEO Data Analysis**  
   - Analysis of past Near Earth Object events  
   - Extraction of data on mass, metal composition, and impact history  

2. **7-Day NEO Forecast (NASA API)**  
   - Real-time forecast for the next 7 days via NASA NeoWs API  
   - Visualization of closest approaches, miss distances, estimated diameters  
   - Distribution of hazardous object distances

3. **Planned: Cross-Analysis & Impact Risk Evaluation**  
   - Match NEOs by composition or characteristics  
   - Evaluate Moon phase influence on minimum distance or velocity  
   - Geolocate potential impact points (if orbital data available)  

## Goals
- Provide accessible, transparent tools for public and research use
- Connect real-time NEO data with historical and compositional analysis
- Share open-source resources for the space science community  

## Requirements
- Python 3.x
- Libraries: `requests`, `matplotlib`, `pandas`, `ephem`, `datetime`

## Author
Angelo Sorte

## License
MIT License  
