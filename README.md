# From an exported HEC_RAS WSE geotiff, create a dissolved shapefile that can be easily used as a boundary shp for mapping.

The Jupyter notebook is setup to search out .tif files from a specified directory. From there a list needs to be setup to specify an output shapefile filename for each processed tif. The tif will be vectorized using Rasterio and then dissolved to a single geometry using geopandas. The output will be the specified shapefile. This process will happen for each tif.

## Example Output
![image](https://github.com/mylesmc123/ras_wse_tif_to_shp_boundary/assets/64209352/77a881f5-ad57-4da1-b36f-579d0e01a110)
