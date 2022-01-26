# Mapping_Earthquakes

## Objectives

#### Map Layers

Create three different layers that will serve as the base map.

- Using https://api.mapbox.com/styles/ to grab three maps that will create the base layers.
  - `streets-v11` will be the default layer.
  
     <img src="https://user-images.githubusercontent.com/85756203/151225313-8a82cac1-0814-4e74-9a5c-ac9d78742317.png" width=60% height=50%>
   

  - `satellite-streets-v11` will be the second layer.
  
     <img src="https://user-images.githubusercontent.com/85756203/151225381-cd0c4f88-691e-481b-89d4-2a2bec9b1f2a.png" width=60% height=50%>

  - `outdoors-v11` will be the third layer.
    
     <img src="https://user-images.githubusercontent.com/85756203/151225399-5635a14a-da59-4fce-bb64-3e79e9a3b7c8.png" width=60% height=50%>


#### Data Layers
The next task added the three data layers to the base map.
The data layers would be composed of the different datasets.
- Recent earthquake [data](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson) from the USGS website.
- The overlay of tectonic plates can be found [here](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json).
- Earthquakes' whose magnitude registered above 4.5 was also gathered from the USGS website. Link [here](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson).

The final map results in the following image.
<img src="https://user-images.githubusercontent.com/85756203/151226418-fe1bee0a-eb1c-41ac-8624-9b8e2ad8bb40.png">
The earthquakes are classified by color and size. The legend in the lower right-hand corner displays the color intervals for each earthquake.
The size of the circle corresponds to the color of the circle. Green circles will be the smallest, while the largest red circles will represent the highest magnitudes.

When an earthquake is selected, a text box will appear, displaying the following information.
 - Magnitude
 - Location
 
 ![EQ_textbox](https://user-images.githubusercontent.com/85756203/151227462-1623a3b0-cf84-4438-b765-70e1d937514a.png)

