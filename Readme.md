# Modeling Paddy Crop Failure Using Machine Learning

This project utilizes **Sentinel Data**, **Climate Data (ERA5)**, **CHIRPS Rainfall Data**, **Radar Vegetation Index (RVI)**, and other geospatial datasets to model paddy crop failures using **XGBoost**. By integrating diverse geospatial and climatic datasets with a powerful gradient boosting algorithm, the project aims to predict crop failure risks, analyze contributing factors, and provide actionable insights for agricultural stakeholders.

---

## 📋 **Objectives**

- **Predict Crop Failures**: Develop an XGBoost-based machine learning model to forecast paddy crop failures.
- **Analyze Influencing Factors**: Evaluate the effects of climatic, vegetation, and geospatial data on crop health.
- **Support Decision-Making**: Enable early intervention and risk management through data-driven insights.

---

## 🛠️ **Key Features**

1. **Integration of Multi-Source Data**:

   - Fuse Sentinel-1 data, ERA5 climate reanalysis, CHIRPS rainfall data, RVI, and other geospatial data to create a comprehensive dataset.

2. **XGBoost Model**:

   - Train and optimize a gradient boosting model using engineered features from geospatial datasets.
   - Evaluate the model’s performance using metrics such as accuracy, precision, recall, and F1-score.

3. **Spatial and Temporal Analysis**:

   - Perform geospatial visualization of risk areas using GIS tools.
   - Conduct temporal analysis to study changes in vegetation and climate over time.

4. **Insights and Recommendations**:
   - Identify critical factors contributing to crop failure and suggest mitigation strategies.

---

## 📊 **Data Sources**

### 1. **Sentinel Data**

### 2. **Climate Data (ERA5)**

### 3. **CHIRPS (Climate Hazards Group InfraRed Precipitation with Station Data)**

### 4. **Radar Vegetation Index (RVI)**

### 5. **Other Geospatial Data**

---

## ⚙️ **Technologies Used**

- **Programming Language**: Python
- **Libraries and Tools**:
  - **Data Handling**: `pandas`, `numpy`, `xarray`
  - **Machine Learning**: `xgboost`, `scikit-learn`
  - **Geospatial Analysis**: `geopandas`, `rasterio`, `shapely`, `GDAL`
  - **Visualization**: `matplotlib`, `seaborn`, `folium`, `plotly`
  - **Remote Sensing**: `SentinelHub`, `earthpy`, `pyproj`

---

## 🚀 **Getting Started**

### Prerequisites

1. Install Python (3.7 or above).
2. Obtain necessary datasets:
   - Sentinel data from the [Copernicus Open Access Hub](https://scihub.copernicus.eu/).
   - ERA5 climate data from [Copernicus Climate Data Store](https://cds.climate.copernicus.eu/).
   - CHIRPS rainfall data from the [CHIRPS database](https://www.chc.ucsb.edu/data/chirps).

### Steps

1. **Data Collection**: Download Sentinel, ERA5, CHIRPS, and other datasets.
2. **Preprocessing**:
   - Align datasets spatially and temporally.
   - Extract features such as NDVI, RVI, rainfall indices, and soil properties.
3. **Feature Engineering**:
   - Create a feature matrix by combining geospatial data with crop health metrics.
4. **Model Training**:
   - Train the XGBoost model on the preprocessed data.
   - Perform hyperparameter tuning for optimal performance.
5. **Evaluation**:
   - Validate the model using a holdout dataset and compute metrics like RMSE, precision, and recall.
6. **Visualization**:
   - Generate geospatial heatmaps and dashboards to display risk areas.

## 🤝 **Contributions**

We welcome suggestions and contributions to enhance the project. Please submit issues or pull requests for improvements.

---

## 📜 **License**

This project is licensed under the MIT License.

---
