from calculate_distance import myfunctions

# example usage of the haversine function
lon1, lat1 = -74.005974, 40.712776  # new york coordinates
lon2, lat2 = 2.352222, 48.856613    # paris coordinates

# calculate the distance between new York and paris
distance = myfunctions.haversine(lon1, lat1, lon2, lat2)

print(f"distance between new york and paris: {distance} km")