# Atmospheric Data Acquisition
This project contains information on how to acquire and analyze data from 3 different sources 
1. Sentinel 5-p API
2. CAMS 
3. ERA5-Reanalysis

Greek mainland is our area of interest and we collect data regarding this specific region.  
## Folder Description
### Code folderCode folder
#### Sentinel5  
Contains code regarding sentinel5p data acquisition. It contains an .ipynb used for data accumulation. This specific notebook uses [s5p-tools](https://github.com/bilelomrani1/s5p-tools) and geojson files which are provided in aux-files/geojson folder

#### CAMS-Analysis 
Notebook used to analyze data from CAMS. 
|||
|-|-|
|Input|Two .nc files and two shapefiles provided in aux-files/shapefiles|
|Output|Information regarding PM10,PM2.5,NO2,SO2,O3,CO,NO|

#### ERA5-Reanalysis
Notebook used to analyze data from ERA5


**Input**: .grib file and two shapefiles </br>
**Output**: Information for urban areas and prefecture about u-component , v-component, temperature 2m, net solar radiation , net thermal radiation.

For more information about the data see:
1. [ERA5-Reanalysis Land](https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-land?tab=overview)
2. [CAMS Analysis](https://ads.atmosphere.copernicus.eu/cdsapp#!/dataset/cams-europe-air-quality-forecasts?tab=form)

### Raw-data folder
Contains semi-raw data files from ERA5 and CAMS (used in the ERA5-Reanalysis.ipynb and CAMS-Analysis.ipynb respectively)

### aux-files
auxiliary files for Analysis. Shapefiles and geojson files

