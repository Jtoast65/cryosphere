NASA MODIS Tiles via GIBS API
Tile coordinates: zoom=3, y=1, x=4 (central Arctic overview)

Layer-specific formats:
  MODIS_Terra_CorrectedReflectance_TrueColor : 250m, .jpg
  MODIS_Terra_Land_Surface_Temp_Day          : 1km,  .png
  MODIS_Terra_L3_NDSI_Snow_Cover_Daily                : 500m, .png

Custom fetch pattern:
  https://gibs.earthdata.nasa.gov/wmts/epsg4326/best/{LAYER}/default/{DATE}/{TMS}/{Z}/{Y}/{X}.{EXT}

Layer browser: https://worldview.earthdata.nasa.gov/
API docs:      https://nasa-gibs.github.io/gibs-api-docs/access-basics/
