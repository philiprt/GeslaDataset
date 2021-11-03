# GeslaDataset
 
 File `gesla.py` defines `GeslaDataset`, a python class for loading GESLA data files into convenient in-memory data objects. By default, single file requests are loaded into `pandas.DataFrame` objects, which are similar to in-memory spreadhseets. Multifile requests are loaded into `xarray.Dataset` objects, which are similar to in-memory NetCDF files.  
    
See the [example usage](https://github.com/philiprt/GeslaDataset/blob/main/read_gesla_v3.ipynb) notebook for a demonstration of how to initialize and use the class.
