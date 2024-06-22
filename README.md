# NES-Read-netCDF

This repository contains example code used to extract northern elephant seal diving and tracking data and metadata that are stored in netCDF-4 (.nc) files. Example scripts have been written for R and MATLAB. The scripts written here are not exhaustive, but meant to act as a guide for users who are unfamiliar with netCDF format files.

MATLAB has native functions for reading and building netCDF files (details [here](https://www.mathworks.com/help/matlab/network-common-data-form.html)).

In R, the package [ncdf4](https://www.rdocumentation.org/packages/ncdf4/versions/1.22) provides functions for reading and building netCDF files.

We have provided a .pdf [here](https://github.com/rholser/NES-Read-netCDF/blob/main/NES_netCDF_readme.pdf) that gives additional details on the contents of the files, including the global attributes (animal, deployment, and file creation metadata) and the names and organization of all groups and variables.

For additional information and documentation about netCDF files, please visit the [Unidata website](https://www.unidata.ucar.edu/software/netcdf/).

## Encountering Problems?
If code is not working as expected, please post an issue [here](https://github.com/rholser/NES-Read-netCDF/issues). Please provide detail about the issue - what species and instrument type are you trying to work with, and what step of the process is not working.

