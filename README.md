# NASA-Sentinel-Data-Extraction

- To reproduce, go to any satellite data on earthdata and click, select your period, satellite, and region, and click on download multiple links. 
- It will download a .txt file, containing the list of links of all the data files. Use that in the codes to map the images as per your preference.
- There are lot of trials using netcdf, hdf5 and other such formats. For various datasets, this will vary and such. Try to find out which suits your dataset best and work out well for it. Typically rasterio works with most satellite data files.
