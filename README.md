# 🌍 TerraMind: ML/DL-Based Spectral Index Prediction & Land Use Change Detection

A **dual-path geospatial intelligence project** combining satellite imagery, machine learning, and cloud-based analytics to:

- 📈 Predict key **spectral indices** (NDVI, EVI, NDBI, BSI) from **Sentinel-2** using regression models.
- 🌆 Detect decade-scale **land use/land cover (LULC)** changes using **Landsat-8** via classification in **Google Earth Engine (GEE)**.

This project showcases the synergy of **remote sensing**, **AI/ML**, and **cloud platforms** for scalable environmental monitoring.

---

## 🛰️ Data Sources

| Satellite | Purpose | Organization |
|-----------|---------|--------------|
| **Sentinel-2** | Spectral index prediction | ESA |
| **Landsat-8** | LULC classification & change detection (2013–2023) | USGS / NASA |

- 🛠️ **Tools Used**: Google Earth Engine, Python, Jupyter Notebook  
- 📁 **Data Format**: GeoTIFF, CSV

---

## 🎯 Objectives

- ✅ Predict vegetation and urban indices using ML/DL regressors
- 📊 Evaluate multiple models for index prediction
- 🌱 Detect land use/cover transitions between 2013 and 2023
- 🗺️ Visualize & quantify urban growth, vegetation loss, and barren land expansion

---

## 🧠 ML/DL Models Used

| Model | Use Case | Performance |
|-------|----------|-------------|
| **Linear Regression** | Baseline prediction | Good |
| **Ridge Regression** | Regularized regression | Better |
| **Random Forest** | Ensemble regression | Great |
| **Extra Trees Regressor** | 🌟 Top performer for spectral prediction | ✅ ~94.5% R² |
| **Gradient Boosting** | Regression accuracy | High |

**Evaluation Metrics**:
- R² Score  
- Mean Absolute Error (MAE)  
- Root Mean Square Error (RMSE)  
- Relative Accuracy

---

## 🌐 Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Google Earth Engine (GEE)** | Preprocessing, classification, change detection |
| **Python (scikit-learn, pandas, NumPy)** | Modeling, data analysis |
| **Jupyter Notebook** | Workflow execution |
| **Matplotlib/Seaborn** | Visualization |
| **GeoTIFF, CSV** | Data exchange |

---

## 📊 Key Results

| Result | Insight |
|--------|---------|
| 🌿 **Extra Trees Regressor** | Achieved **~94.5% R²** for spectral index prediction |
| 🏙️ **Random Forest Classifier (GEE)** | Detected **~16.3% increase in urban area** (2013–2023) |
| 🌳 **Vegetation Loss** | Observed **~13.7% decrease in green cover** |
| 🗺️ **Change Maps** | Validated spatial transformations visually and statistically |

---

## 🧭 Future Work

- 🔍 Integrate **CNNs/LSTMs** for spatio-temporal modeling
- 🔄 Fuse **climate + socio-economic** datasets for enriched insights
- 🌐 Expand to other regions under ecological stress

---

## 📌 Applications

- 🏗️ Urban Planning
- 🌿 Environmental Monitoring
- 🧑‍⚖️ Policy-Making for Climate Resilience
- 🌾 Sustainable Land Management

---

## 📎 Folder Structure (Optional)

```bash
TerraMindNet/
├── README.md
├── TerraMind_Spectral_LULC_Analysis.ipynb
├── .gitignore
