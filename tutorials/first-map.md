# Your First Map in Python

```python
import geopandas as gpd
import matplotlib.pyplot as plt
from geodatasets import get_path
world = gpd.read_file(get_path("naturalearth.land"))
world.plot()
plt.show()
```
