# example usage

this package includes a `haversine` function to calculate the great circle distance between two points on earth given their longitude and latitude 
below is an example of how to use this function

```python
from calculate_distance import myfunctions

# example usage of the haversine function
lon1, lat1 = -74.005974, 40.712776  # new york coordinates
lon2, lat2 = 2.352222, 48.856613    # paris coordinates

# calculate the distance between new york and paris
distance = myfunctions.haversine(lon1, lat1, lon2, lat2)

print(f"distance between new york and paris: {distance} km")