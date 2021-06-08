# soil_erosion_detection
### Loading data
For loading data two packages were used: 
- rasterio 
Rasterio reads and writes GeoTIFF and other formats to organize and store gridded raster datasets such as satellite imagery and terrain models and provides a Python API based on Numpy N-dimensional arrays
- geopandas
The goal of GeoPandas is to make working with geospatial data in python easier. It combines the capabilities of pandas and shapely, providing geospatial operations in pandas and a high-level interface to multiple geometries to shapely. GeoPandas enables you to easily do operations in python that would otherwise require a spatial database such as PostGIS

### Research about model for detection
 - article 'Facing Erosion Identification in Railway Lines Using Pixel-Wise Deep-Based Approaches'
 There were described 6 techniques:
  * Pixelwise strategy that using context windows
  * Fully Convolutional Network
  * Deconvolution Network
  * Fully convolutional DeepLab
  * Mask R-CNN
  * Dynamic Dilated ConvNet
- article 'Evaluation of Different Machine Learning Models for Predicting Soil Erosion in Tropical Sloping Lands of Northeast Vietnam'
  * fuzzy k-nearest neighbor (FKNN)
  * artificial neural network (ANN)
  * support vector machine (SVM)
  * least squares support vector machine (LSSVM)
  * relevance vector machine (RVM)
- article 'A Remote Sensing Based Method to Detect SoilErosion in Forests'
Various remote sensing based methods have been developed and applied to detect features relatedto soil erosion:
  * Normalized Difference Vegetation Index(NDVI)
  * Normalized Difference Soil Index (NDSI)
  * Tasselled Cap Transformation (TCT)
  * along withLinear Spectral Unmixing Analysis (LSMA)
Model thst was described:
  * SEUFM through Principal Components Analysis (PCA)
- article 'Gully erosion susceptibility mapping (GESM) using machine learning methods optimized by the multi‑collinearity analysis and K-fold cross-validation'
  * artificial neural network (ANN)
  * random forest (RF) models within 4-fold cross-validation (CV)
- article 'A Deep Learning Approach for Burned Area Segmentation with Sentinel-2 Data'
  * convolutional neural network based on a U-Net
