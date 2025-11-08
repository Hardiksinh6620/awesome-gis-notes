# Rasterio

```python
import rasterio
with rasterio.open("x.tif") as src:
    band = src.read(1, masked=True)
    print(src.crs, src.transform, src.nodata)
```
