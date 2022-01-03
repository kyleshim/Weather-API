### Weather-API
#### <i> An analysis of weather patterns in relation to the equator</i>

----------------------

**Description:**

I used Python APIs, Matplotlib, GMaps, and Pandas to analyze weather patterns in relation to the equator. Specifically Wind Speed, Cloudiness, Humidity, and Maximum Temperature. I then used this informaton to determine hotels in loactions with ideal weather.

<b>Datasets used:</b>

* [City Data](output_data/city_data.csv)

### Tools used:
----------------------

  - Python
  - Pandas
  - Matplotlib
  - Jupyter
  - Citipy
  - Numpy
  - Scipy
  - pprint
  - Weather API
  - JSON
  - GMaps

### Analysis:
----------------------

#### Scatter Plots

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

#### Linear Regressions

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

#### Heat Maps
* Humidity by City
* Ideal Hotel Markers
  * A max temperature lower than 80 degrees but higher than 70
  * Wind speed less than 10 mph
  * Zero cloudiness

###  Data Visualization:
----------------------

#### Temperature (F) vs. Latitude
![Temperature_Latitude](output_data/lat_temp.png)

#### Humidity (%) vs. Latitude
![Humidity_Latitude](output_data/lat_hum.png)

#### Cloudiness (%) vs. Latitude
![Cloudiness_Latitude](output_data/lat_cloud.png)

#### Wind Speed (mph) vs. Latitude
![Wind_Speed_Latitude](output_data/lat_wind.png)

#### Northern Hemisphere - Temperature (F) vs. Latitude
![Northern_Temperature_Latitude](output_data/lat_temp_north.png)

#### Southern Hemisphere - Temperature (F) vs. Latitude
![Southern_Temperature_Latitude](output_data/lat_temp_south.png)

#### Northern Hemisphere - Humidity (%) vs. Latitude
![Northern_Humidity_Latitude](output_data/lat_hum_north.png)

#### Southern Hemisphere - Humidity (%) vs. Latitude
![Southern_Humidity_Latitude](output_data/lat_hum_south.png)

#### Northern Hemisphere - Cloudiness (%) vs. Latitude
![Northern_Cloudiness_Latitude](output_data/lat_cloud_north.png)

#### Southern Hemisphere - Cloudiness (%) vs. Latitude
![Southern_Cloudiness_Latitude](output_data/lat_cloud_south.png)

#### Northern Hemisphere - Wind Speed (mph) vs. Latitude
![Northern_Wind_Speed_Latitude](output_data/lat_wind_north.png)

#### Southern Hemisphere - Wind Speed (mph) vs. Latitude
![Southern_Wind_Speed_Latitude](output_data/lat_wind_south.png)

#### Heat Map - Humidity
![Heat_Map_Humidity](output_data/Heat_Map.png)

#### Heat Map - Ideal Hotel Markers
![Heat_Map_Hotels](output_data/Hotel_Marker_Heat_Map.png)