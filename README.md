# Dublin Bikes Data Analysis & Clustering

A high-scale data science project analyzing 36 million rows of Dublin Bikes availability data.

## Key Features
* **Big Data Handling:** Implemented chunked data processing to merge 33 CSV files (36M rows) without memory crashes.
* **Feature Engineering:** Calculated real-time station occupancy rates and bike stand capacity.
* **Advanced ML:** Applied KMeans clustering validated by both the **Elbow Method** and **Silhouette Score**.
* **Interactivity:** Created a geospatial dashboard using Folium with custom CSS legends.

## Notebooks
1. **Data Loading:** Memory-safe merging of historical bike data.
2. **Data Cleaning:** Type optimization and handling missing values.
3. **EDA:** Statistical analysis of bike usage patterns across Dublin.
4. **Clustering:** Segmenting stations by usage intensity and capacity.

## Libraries Used
`pandas`, `scikit-learn`, `folium`, `matplotlib`