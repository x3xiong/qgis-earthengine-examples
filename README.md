# qgis-earthengine-examples

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A collection of **200+** Python examples for using Google Earth Engine in QGIS

**Contact:** Qiusheng Wu (https://wetlands.io)

## 1. Description

This repository is a collection of **200+** Python examples for the [Google Earth Engine plugin for QGIS](https://github.com/gee-community/qgis-earthengine-plugin). I developed these Python examples by converting *all* (except those unsupported by QGIS) the JavaScript examples from the Google Earth Engine [API Documentation](https://developers.google.com/earth-engine/). Additionally, some examples were adapted from [Gena's examples](https://github.com/gee-community/qgis-earthengine-plugin/tree/master/examples) and the Earth Engine [API examples](https://github.com/google/earthengine-api/tree/master/python/examples). Kudos to [Gennadii Donchyts](https://github.com/gena) for developing this amazing Google Earth Engine plugin for QGIS.

## 2. Usage

* **Step 1:** [Sign up](https://earthengine.google.com/signup/) for [Google Earth Engine](https://earthengine.google.com/).
* **Step 2:** Install [QGIS](https://qgis.org/).
* **Step 3:** Install the [Google Earth Engine Plugin for QGIS](https://gee-community.github.io/qgis-earthengine-plugin/) and authenticate Google Earth Engine.
* **Step 4:** Git clone or [download](https://github.com/giswqs/qgis-earthengine-examples/archive/master.zip) this repository.
* **Step 5:** Open the Python console in QGIS and load any downloaded Python script into the QGIS Python Editor.
* **Step 6:** Click the *Run script* button on the Python Editor to execute the script.
* **Step 7:** Zoom in/out the QGIS Canvas to inspect the results.

## 3. Demo

![qgis-gee-demo](https://i.imgur.com/OuWQlsF.gif)

## 4. Examples

The Table of Contents below mimics the structure of the Google Earth Engine [API Documentation](https://developers.google.com/earth-engine). I strongly encourage you to check out the API Documentation if you need an in-depth explanation of each Python example. Please note that the list below does not include all the Python examples contained in this repository. You are welcome to explore the repository and find more examples to suit your needs. 

### [Get Started](https://github.com/giswqs/qgis-earthengine-examples/tree/master/GetStarted)

* [Hello world!](https://github.com/giswqs/qgis-earthengine-examples/blob/master/GetStarted/01_hello_world.py)
* [Adding data to QGIS](https://github.com/giswqs/qgis-earthengine-examples/blob/master/GetStarted/02_adding_data_to_qgis.py)
* [Finding images](https://github.com/giswqs/qgis-earthengine-examples/blob/master/GetStarted/03_finding_images.py)
* [Band math](https://github.com/giswqs/qgis-earthengine-examples/blob/master/GetStarted/04_band_math.py)
* [Mapping (what to do instead of a for-loop)](https://github.com/giswqs/qgis-earthengine-examples/blob/master/GetStarted/05_map_function.py)
* [Reducing](https://github.com/giswqs/qgis-earthengine-examples/blob/master/GetStarted/06_reducing.py)
* [Image statistics](https://github.com/giswqs/qgis-earthengine-examples/blob/master/GetStarted/07_image_statistics.py)
* [Masking](https://github.com/giswqs/qgis-earthengine-examples/blob/master/GetStarted/08_masking.py)
* [A complete example](https://github.com/giswqs/qgis-earthengine-examples/blob/master/GetStarted/09_a_complete_example.py)

### [Machine Learning](https://github.com/giswqs/qgis-earthengine-examples/tree/master/MachineLearning)

* Supervised Classification Algorithms
  * [Classification and Regression Trees (CART)](https://github.com/giswqs/qgis-earthengine-examples/blob/master/MachineLearning/cart_classifier.py) | [Support Vector Machine (SVM)](https://github.com/giswqs/qgis-earthengine-examples/blob/master/MachineLearning/svm_classifier.py) | [Confusion Matrix](https://github.com/giswqs/qgis-earthengine-examples/blob/master/MachineLearning/confusion_matrix.py)
* Unsupervised Classification Algorithms
  * [KMeans Clustering](https://github.com/giswqs/qgis-earthengine-examples/blob/master/MachineLearning/clustering.py)

### [Image](https://github.com/giswqs/qgis-earthengine-examples/tree/master/Image)

* [Image Overview](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Image/image_overview.py)
* [Image Visualization](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Image/image_vis.py)
* [Image information and metadata](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Image/image_metadata.py)
* [Mathematical operations](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Image/band_math.py)
* [Relational, conditional and Boolean operations](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Image/conditional_operations.py)
* [Convolutions](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Image/convolutions.py)
* [Morphological Operations](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Image/morphological_operations.py)
* [Gradients](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Image/gradients.py)
* [Edge detection](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Image/edge_detection.py)
* [Spectral transformations](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Image/spectral_unmixing.py)
* [Texture](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Image/texture.py)
* [Object-based methods](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Image/object_based.py)
* [Cumulative Cost Mapping](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Image/cumulative_cost_mapping.py)
* [Registering Images](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Image/image_displacement.py)

### [ImageCollection](https://github.com/giswqs/qgis-earthengine-examples/tree/master/ImageCollection)

* [ImageCollection Overview](https://github.com/giswqs/qgis-earthengine-examples/blob/master/ImageCollection/overview.py)
* [ImageCollection Information and Metadata](https://github.com/giswqs/qgis-earthengine-examples/blob/master/ImageCollection/metadata.py)
* [Filtering an ImageCollection](https://github.com/giswqs/qgis-earthengine-examples/blob/master/ImageCollection/filtering_collection.py)
* [Mapping over an ImageCollection](https://github.com/giswqs/qgis-earthengine-examples/blob/master/ImageCollection/map_function.py)
* [Reducing an ImageCollection](https://github.com/giswqs/qgis-earthengine-examples/blob/master/ImageCollection/reducing_collection.py)
* [Compositing and Mosaicking](https://github.com/giswqs/qgis-earthengine-examples/blob/master/ImageCollection/mosaicking.py)

### [Geometry, Feature, FeatureCollection](https://github.com/giswqs/qgis-earthengine-examples/tree/master/FeatureCollection)

* [Geometry Overview](https://github.com/giswqs/qgis-earthengine-examples/blob/master/FeatureCollection/creating_feature.py)
* [Geodesic vs. Planar Geometries](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Visualization/visualizing_geometries.py)
* [Geometry Visualization and Information](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Visualization/visualizing_geometries.py)
* [Geometric Operations](https://github.com/giswqs/qgis-earthengine-examples/blob/master/FeatureCollection/geometric_operations.py)
* [Feature Overview](https://github.com/giswqs/qgis-earthengine-examples/blob/master/FeatureCollection/creating_feature.py)
* [FeatureCollection Overview](https://github.com/giswqs/qgis-earthengine-examples/blob/master/FeatureCollection/from_polygons.py)
* [Feature and FeatureCollection Visualization](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Visualization/visualizing_feature_collection.py)
* [FeatureCollection Information and Metadata](https://github.com/giswqs/qgis-earthengine-examples/blob/master/FeatureCollection/metadata_aggregation.py)
* [Filtering a FeatureCollection](https://github.com/giswqs/qgis-earthengine-examples/blob/master/FeatureCollection/filtering_feature_collection.py)
* [Mapping over a FeatureCollection](https://github.com/giswqs/qgis-earthengine-examples/blob/master/FeatureCollection/map_function.py)
* [Reducing a FeatureCollection](https://github.com/giswqs/qgis-earthengine-examples/blob/master/FeatureCollection/reducing_feature_collection.py)
* [Vector to Raster Interpolation](https://github.com/giswqs/qgis-earthengine-examples/blob/master/FeatureCollection/idw_interpolation.py)

### [Reducer](https://github.com/giswqs/qgis-earthengine-examples/tree/master/Reducer)

* [Reducer Overview](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Reducer/min_max_reducer.py)
* [ImageCollection Reductions](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Reducer/median_reducer.py)
* [Image Reductions](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Reducer/image_reductions.py)
* [Statistics of an Image Region](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Reducer/stats_of_an_image_region.py)
* [Statistics of Image Regions](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Reducer/stats_of_image_regions.py)
* [Statistics of Image Neighborhoods](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Reducer/stats_of_image_neighborhoods.py)
* [Statistics of FeatureCollection Columns](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Reducer/stats_of_columns.py)
* [Raster to Vector Conversion](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Reducer/convert_raster_to_vector.py)
* [Vector to Raster Conversion](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Reducer/convert_vector_to_raster.py)
* Grouped Reductions and Zonal Statistics
  * [Statistics by group](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Reducer/stats_by_group.py) | [Zonal Statistics](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Reducer/zonal_statistics.py)
* [Weighted Reductions](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Reducer/weighted_reductions.py)
* [Linear Regression](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Reducer/linear_regression.py)

### [Join](https://github.com/giswqs/qgis-earthengine-examples/tree/master/Join)

* [Simple Joins](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Join/simple_joins.py)
* [Inverted Joins](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Join/inverted_joins.py)
* [Inner Joins](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Join/inner_joins.py)
* [Save-All Joins](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Join/save_all_joins.py)
* [Save-Best Joins](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Join/save_best_joins.py)
* [Spatial Joins](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Join/spatial_joins.py)

### [Array](https://github.com/giswqs/qgis-earthengine-examples/tree/master/Array)

* [Arrays and Array Images](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Array/array_images.py)
* [Array Transformations](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Array/array_transformations.py)
* [Eigen Analysis](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Array/eigen_analysis.py)
* [Array Sorting and Reducing](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Array/array_sorting.py)

### [Specialized Algorithms](https://github.com/giswqs/qgis-earthengine-examples/tree/master/Algorithms)

* Landsat Algorithms
  * [Radiance](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Algorithms/landsat_radiance.py) | [Surface Reflectance](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Algorithms/landsat_surface_reflectance.py) | [Simple cloud score](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Algorithms/landsat_cloud_score.py) | [Simple composite](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Algorithms/landsat_simple_composite.py) 
* [Sentinel-1 Algorithms](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Algorithms/sentinel-1_filtering.py)
* Resampling and Reducing Resolution
  * [Resampling](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Algorithms/resampling.py) | [Reducing Resolution](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Algorithms/reduce_resolution.py)
* [Linear fit](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Algorithms/ntl_linear_fit.py)
* Pattern recognition
  * [Center-pivot Irrigation Detector](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Algorithms/center_pivot_irrigation_detector.py)

### [Asset Management](https://github.com/giswqs/qgis-earthengine-examples/tree/master/AssetManagement)

* [Exporting Image](https://github.com/giswqs/qgis-earthengine-examples/blob/master/AssetManagement/export_raster.py)
* [Exporting ImageCollection](https://github.com/giswqs/qgis-earthengine-examples/blob/master/AssetManagement/export_ImageCollection.py)
* [Exporting Vector](https://github.com/giswqs/qgis-earthengine-examples/blob/master/AssetManagement/export_vector.py)
* [Exporting FeatureCollection](https://github.com/giswqs/qgis-earthengine-examples/blob/master/AssetManagement/export_FeatureCollection.py)
* [Exporting CSV](https://github.com/giswqs/qgis-earthengine-examples/blob/master/AssetManagement/export_csv.py)
* [Exporting Table](https://github.com/giswqs/qgis-earthengine-examples/blob/master/AssetManagement/export_table.py)
* [Exporting TimeSeries](https://github.com/giswqs/qgis-earthengine-examples/blob/master/AssetManagement/export_TimeSeries.py)

### [How Earth Engine Works](https://github.com/giswqs/qgis-earthengine-examples/tree/master/HowEarthEngineWorks)

* [Client vs. Server](https://github.com/giswqs/qgis-earthengine-examples/blob/master/HowEarthEngineWorks/ClientVsServer.py)
* [Deferred Execution](https://github.com/giswqs/qgis-earthengine-examples/blob/master/HowEarthEngineWorks/DeferredExecution.py)
* [Projections](https://github.com/giswqs/qgis-earthengine-examples/blob/master/HowEarthEngineWorks/Projections.py)

### [Visualization](https://github.com/giswqs/qgis-earthengine-examples/tree/master/Visualization)

* [RGB composite](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Visualization/image_rgb_composite.py)
* [Color palettes](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Visualization/image_color_palettes.py)
* [Color ramp ](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Visualization/image_color_ramp.py)
* [Hillshade](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Visualization/hillshade.py)
* [Image stretch](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Visualization/image_stretch.py)
* [Image thumbnail](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Visualization/image_thumbanil.py)
* [Rendering categorical maps](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Visualization/rendering_categorical_maps.py)
* [Styled layer descriptors](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Visualization/styled_layer_descriptors.py)
* [Terrain visualization](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Visualization/terrain_visualization.py)
* [Visualizing FeatureCollection](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Visualization/visualizing_feature_collection.py)
* [Visualizing Geometry](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Visualization/visualizing_geometries.py)
* [NLCD Land Cover](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Visualization/nlcd_land_cover.py)
* [US Counties](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Visualization/us_counties.py)

### [Datasets](https://github.com/giswqs/qgis-earthengine-examples/tree/master/Datasets)

* [Terrain](https://github.com/giswqs/qgis-earthengine-examples/tree/master/Datasets/Terrain)
* [Water](https://github.com/giswqs/qgis-earthengine-examples/tree/master/Datasets/Water)

### [Gena's Examples](https://github.com/giswqs/qgis-earthengine-examples/tree/master/Gena)

* [Map.addLayer()](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Gena/map_add_features.py) | [Map.centerObject()](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Gena/map_center_object.py) | [Map.setCenter()](https://github.com/giswqs/qgis-earthengine-examples/blob/master/Gena/map_set_center.py)
