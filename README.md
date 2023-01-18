# live-viewer-2022-map
So, here's the deal:

## current_map.html
  This file creates a mapbox based display of the data from the current_map_data.php endpoint, which is json-based. You will need to supply your own mapbox api key if you directly wanna use this. 
  Fairly messy and you probably wanna just get the "core" of this and throw out the rest, Dr. Chou.

## current_map_data.php
  Creates the json output from our own database dump, which you likely don't care about at all, but wrt some implementation details, you might want it.
