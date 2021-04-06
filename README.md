# Forest-fire-in-Australia

## Overview

From september 2019 to march 2020, nearly [**19 million hectares of Australian land have gone up in smoke**](https://www.bbc.com/news/world-australia-50951043). Known as Black Summer, this bushfire season was a period of unusually intense bushfires in many parts of Australia. 

This project was done based on Kaggle datasets [Fires from Space: Australia](https://www.kaggle.com/carlosparadis/fires-from-space-australia-and-new-zeland).
The project was first based on the datas collected by MODIS (Moderate Resolution Imaging Spectroradiometer). It's a key instrument aboard the Terra and Aqua satellites which collect datas from August 2019 to January the 11th 2020.


### Data Structure
Two datasets were structured in the same way : 
  - latitude
  - longitude
  - brightness: Channel 21 brightness temperature of the fire pixel measured in Kelvin.
  - scan: Scan pixel size
  - track: Track pixel size
  - acq_date Date of MODIS acquisition.
  - acq_time: Time of acquisition of the satellite (in UTC).
  - satellite: A = Aqua and T = Terra.
  - instrument: Constant value for MODIS.
  - confidence
  - version of the instrument
  - bright_t31: Channel 31 brightness temperature of the fire pixel measured in Kelvin.
  - frp: Fire Radiative Power in MW (megawatts).
  - daynight: D = Daytime, N = Nighttime
