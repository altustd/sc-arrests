# Columbia, SC Arrest Data Analysis (2016–2024)

A data science portfolio project analyzing public arrest records from the City of Columbia, South Carolina.  
Explores trends over time, demographics, crime types, and spatial hotspots using Python (Pandas, Seaborn, Folium, scikit-learn).

![Columbia SC Skyline](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0a/Columbia_SC_skyline.jpg/800px-Columbia_SC_skyline.jpg)  
*(Image: Columbia, SC skyline – for illustration)*

## Features / Skills Demonstrated
- Data cleaning & feature engineering
- Time-series EDA (trends by year, month, day)
- Demographic analysis (age, sex, race)
- Crime type frequency
- Geospatial visualization (Folium heatmaps)
- Clustering for hotspot detection (K-Means)

## Dataset
- Source: City of Columbia Open Data Portal  
  [Arrest Data (1/1/2016 – 12/31/2024)](https://coc-colacitygis.opendata.arcgis.com/datasets/ColaCityGIS::arrest-1-1-2016-to-12-31-2024/about)
- Format: CSV with fields like Arrest_Date, Offense_Description, Age, Sex, X/Y coordinates (State Plane feet)

## Key Visualizations

### Top Crime Types (Offense Descriptions)
![Top Offenses](top_offenses.png)  
*(Horizontal bar chart of most frequent offense types)*

### Age Distribution by Sex
![Age by Sex](age_distribution_by_sex.png)  
*(Stacked histogram showing age groups colored by sex)*

### Arrest Heatmap (Spatial Hotspots)
![Arrest Heatmap](columbia_arrest_heatmap.png)  
*(Folium-generated heatmap of arrest locations across Columbia – saved as static image or view interactive HTML)*

### K-Means Clustering of Arrest Locations
![Clusters](arrest_clusters.png)  
*(Scatter plot with color-coded clusters highlighting potential hotspots)*

## How to Run Locally
1. Clone the repo:
   ```bash
   git clone https://github.com/altustd/sc-arrests.git
   cd sc-arrests
