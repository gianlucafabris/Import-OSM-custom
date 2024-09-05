# Import OSM custom

This is a custom osm importer for BeamNG that could also use the elevation.
It offers the follow features:
- custom filters
- ai drivable roads
- possibility to choose how to use the elevation (`both` recommended)

## download osm.py
The inputs for the download phase are: an area defined by a minimum and maximum latitude and longitude, alternatively can be used a name of a city (one of these is mandatory, if both inputs are given, the city will be used) and a custom filter (optional). It is also possible to decide which elevation API will be used and whether to use the elevation (`none`, `road`, `terrain`, `both`). These imputs can be customized in the main function.

The following APIs are used https://nominatim.openstreetmap.org/search, https://overpass-api.de/api/interpreter and elevation api (it can be customized in getHeight.py).

## import osm.py
The BeamNG folders and output of download osm.py can be customized in the main function.
