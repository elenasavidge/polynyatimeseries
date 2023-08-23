# polynyatimeseries

Code to reproduce figures in Savidge et al., XXXX.

Notebooks 'visible_effectivepixel_area' and 'thermal_effectivepixel_area' produce the output files (thermal_area_effectivepixel.pkl and visible_area_effectivepixel.pkl) that are  used in all the figure notebooks. These notebooks ('visible_effectivepixel_area', 'thermal_effectivepixel_area') are quite large and take some time to run as they go through a total of 340 MODIS scenes.

We include the output pickle files (thermal_area_effectivepixel.pkl, visible_area_effectivepixel.pkl) which are the polynya area time series data, one from thermal and one from visible imagery, but otherwise formatted exactly the same in pandas dataframes so they can easily be concatenated if needed. Therefore, the 'visible_effectivepixel_area' and 'thermal_effectivepixel_area' notebooks do not need to be run to reproduce the figures. To visualize the polynya area time series with all data run fig2.ipynb.

Figures SX are supplemental figures.

All MODIS imagery can be visualized in NASA Worldview and downloaded from NASA Earthdata. 
