# Mapping_Earthquakes

## Overview

This challenge focused on our ability to expand on the exercises we did in the Module 13 coursework.
At the beginning of the challenge, our map had three layers: two map layers and one data layer.

Our first task was adding a second data layer, an overlay of tectonic plates around the globe.

We could refactor code from previous exercises to make this challenge easier.

For formatting the Tectonic Plate lines, I took the style we used in 13.5.5 and put that into the geoJson function for deliverable one.

After that, our second task was adding a final data layer that focused on major earthquakes.

Again, we could refactor the code we used for the earthquake data layer to complete this task quicker. The most significant changes were grabbing a different JSON data source that mapped major earthquakes, changing the getColor function to have magnitudes greater than 6, greater than 5, and the remaining earthquakes.

The final addition was adding a third map layer to follow the streets and satellite layers.

![Challenge 13 image 1](https://user-images.githubusercontent.com/85756203/135353233-94b480b6-a25e-408e-a73a-9b7593daf716.png)

Above is one of the code blocks that created one of the existing layers in our map. There was only one thing we needed to change for an additional layer.

![Challenge 13 image 2](https://user-images.githubusercontent.com/85756203/135353245-057e8bd2-befa-4278-adfe-730b06b2d281.png)

Changing the Mapbox style and adding the new variable to the baseMaps variable added the final layer.

![Challenge 13 image 3](https://user-images.githubusercontent.com/85756203/135353265-5a754b36-37e3-4a3a-babc-3cb6dafa4f93.png)
