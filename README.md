Urban Heat Island (UHI) Prediction Using Sentinel-2 Imagery

This project presents a machine learning pipeline to **predict Urban Heat Island (UHI) intensities** using **Sentinel-2 satellite data** for **Montgomery County, Maryland**, and evaluates its generalizability to **Manhattan, NYC**.

Objective

To model and interpret the drivers of urban heat by analyzing spectral, spatial, and environmental features—supporting data-driven urban planning interventions.

Data & Preprocessing

* **Source**: Sentinel-2 imagery (July–September 2022)
* **Features**: 11 spectral bands + 13 engineered indices (e.g., NDVI, NDWI, NDBI, UI)
* **Spatial Enhancements**: Distances to roads, water bodies, and parks
* **Tiling Strategy**: Grid-based bounding boxes (\~82 km²) for efficient data coverage and minimal cloud interference

Modeling Approach

* **Algorithm**: Random Forest Regressor
* **Performance**:

  * **Train R²**: 0.989
  * **Test R²**: 0.618 (moderate generalization to new geographies)

Key Insights & Recommendations

1. **Increase Urban Greenery**: Green roofs, vertical gardens, and parks in high-risk zones
2. **Cool Pavement Initiatives**: Replace traditional asphalt to reduce heat retention
3. **Pollution Control**: Monitor and reduce urban pollution as it traps heat

Impact

This model provides a *scalable and interpretable framework to identify* heat-prone urban zones, guide *sustainable development*, and improve *climate resilience*.
