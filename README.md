# Forest-fire-in-Australia

## Overview

From september 2019 to march 2020, nearly [**19 million hectares of Australian land have gone up in smoke**](https://www.bbc.com/news/world-australia-50951043). Known as Black Summer, this bushfire season was a period of unusually intense bushfires in many parts of Australia. 

This project was done based on Kaggle datasets [Fires from Space: Australia](https://www.kaggle.com/carlosparadis/fires-from-space-australia-and-new-zeland).
The project was first based on the datas collected by MODIS (Moderate Resolution Imaging Spectroradiometer). It's a key instrument aboard the Terra and Aqua satellites which collect datas from August 2019 to January the 11th 2020.


### Data Structure
Two datasets were structured in the same way : 
  - latitude
  - longitude
  - brightness: *Channel 21 brightness temperature of the fire pixel measured in Kelvin.*
  - scan: *Scan pixel size.*
  - track: *Track pixel size.*
  - acq_date: *Date of MODIS acquisition.*
  - acq_time: *Time of acquisition of the satellite (in UTC).*
  - satellite: *A = Aqua and T = Terra.*
  - instrument: *Constant value for MODIS.*
  - confidence
  - version of the instrument
  - bright_t31: *Channel 31 brightness temperature of the fire pixel measured in Kelvin.*
  - frp: *Fire Radiative Power in MW (megawatts).*
  - daynight: *D = Daytime, N = Nighttime.*


## Data Visualisation

The dataset is a recording of MODIS from August 2019 to January the 11th 2020. There are 219,604 observations within the dataset.

The [Forest_fire_in_Australia.ipynb](Forest_fire_in_Australia.ipynb) workbook contains the code to produce all the visualisation in this section.

### Fire detected by month

Simple barchart with the datas grouped by month that show a very hig value for the month of December.
*Note: the datas stopped the 11th January, so the number of fire detected is undervalued compared to the other months. But in only 12 days, there is already 27 000 fires detected.* 
<p align="center">
<img src="/img/Fire detected by month.png"/>
</p>
/img/Fire detected by month.png

### Map of the fire detected by day

To add some value to this dataset, a map have been done on Plotly Express to show the evolution of the fire by day all over the Australia. The image below is just a static screenshot, but you can find the [interative map in html](/img/map_fire.html) in the folder img.

<p align="center">
<img src="img/Bushfire in Australia from August 2019 to January 2020.png" width="700"/>
</p>
