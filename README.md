# polynyatimeseries

Code to reproduce figures in Savidge et al. (submitted).

Notebooks 'visible_effectivepixel_area' and 'thermal_effectivepixel_area' produce the output files (thermal_area_effectivepixel_fixed and visible_area_effectivepixel_fixed) that are  used in all the figure notebooks. These notebooks ('visible_effectivepixel_area', 'thermal_effectivepixel_area') are quite large and take some time to run as they go through a total of 342 MODIS scenes.

We include the output pickle files (thermal_area_effectivepixel_fixed, visible_area_effectivepixel_fixed) which are the polynya area time series data, one from thermal imagery and one from visible imagery, but otherwise formatted exactly the same in pandas dataframes so they can easily be concatenated if needed. Therefore, the 'visible_effectivepixel_area' and 'thermal_effectivepixel_area' notebooks do not need to be run to reproduce the figures. To visualize the polynya area time series with all data run fig2.ipynb.

Figures SX are supplemental figures.

The timeseries_scenes.xlsx file contains the dates, file names, and links to all scenes used.

All MODIS imagery can be visualized in [NASA Worldview](https://worldview.earthdata.nasa.gov/) and downloaded from [NASA Earthdata](https://search.earthdata.nasa.gov/). 

[![DOI](https://zenodo.org/badge/674354609.svg)](https://zenodo.org/doi/10.5281/zenodo.10042119)
