# GeoPandas Cheatsheet

```python
import geopandas as gpd
gdf = gpd.read_file("data.geojson")
gdf.to_crs("EPSG:3857", inplace=True)
gdf.buffer(100)
gdf.sjoin(other, predicate="intersects")
gdf.plot()
```
