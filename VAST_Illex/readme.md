This folder contains files to run a VAST model for northern shortfin squid. 

### Files:
1. Illex_VAST_2021-10-01.Rmd  -  Main script for running the model. Cleaning and better documentation in progress.
2. NWA_offshore-inshore-region.Rmd  -  Script to create custom regions for use in VAST. 
3. NWA_day_2020_06-25.csv - Survey data from Fall NEFSC, NEAMAP, and Maine/New Hampshire bottom trawl surveys.
  + Tow coordinates, year, date and time (EST), area swept (km2), survey or vessel name, depth (m), bottom temperature (C), catch (kg), presence (0/1), zenith angle (calculated using fishmethods::astrocalc4r()), and "daytime" (1 == tow occurred during the day, i.e. between sunrise and sunset; 0 == tow occurred at night, i.e. after sunset).

### Data Acknowledgements 
Sara Murray, James Gartland, Rebecca Peters, KimMcKown, Matt Camisa, and Linda Barry provided data from state inshore surveys.
Phillip Greyson and Nancy Shackle provided the Canadian DFO survey data.
