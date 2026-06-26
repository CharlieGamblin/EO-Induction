# EO-Induction Notebooks

# Introduction 

A set of notebooks created during a temp contract as an EO data scientist at Space Park Leicester.

# Contents

## Practice Scripts

- Xarray Foundations: A walkthrough of the basics of the xarray library, including producing a synthetic thermal dataset, building a data array, basic data manipulation (e.g. resampling), plotting and netCDF4 conversion. 

- ESA Permafrost Extent: Reads in the V4 permafrost extent data from the ESA cci data on CEDA. Plots this as a heatmap for 1997.

- Victoria Island Skin Temp: Reads ERA5 skin temperature data for a location on Victoria Island (Canada) using both the netCDF library and the xarray library. Creates line and scatter plots of skin temperature over time.

## Outputs 

- Peramfrost extent 1997: The permafrost area fraction has been plotted for the arctic region (>50 degs latitude).

## Data 

- Example lst: A netCDF file created from synethic data used in the xarray foundations script.

- ERA 5 Skin Temperature: A netCDF file of ERA5 skin temperature data for Victoria Island from the climate data store (used in the Victoria Island skin temperature script).

## Envs

- Environment YAML file: Contains all the necessary libraries and dependencies in a .yml format.
