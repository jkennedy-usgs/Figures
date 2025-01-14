### Install Figures:
Clone or download the repository and then  

```
>python setup.py install
```
or via pip:

```
pip install https://github.com/aleaf/Figures/archive/master.zip
```

### Requirements
* python packages: numpy and matplotlib (both standard with the [Anaconda Distribution](https://www.continuum.io/downloads))
* for full USGS formatting, the **Univers** font is required. See [here](https://github.com/aleaf/Figures/blob/master/Notebooks/Univers.ipynb) for instructions on getting **Univers** working with ``matplotlib``.
*  note: the ``xsection`` module requires flopy, but it needs some work
*  the ``map`` module requires ``basemap, fiona, shapely, descartes and GIS_utils``. The first four can be installed from `gis.yml` using conda:

```
>conda env create -f gis.yml
```

**GIS_utils** can be obtained from [https://github.com/aleaf/GIS_utils](https://github.com/aleaf/GIS_utils)


Or installed using pip:  

```
>pip install https://github.com/aleaf/GIS_utils/archive/master.zip
```


### Demonstration Notebooks
[USGS Report formatting](https://github.com/aleaf/Figures/blob/master/Notebooks/Figures_demo.ipynb)  
[USGS Report map](https://github.com/aleaf/Figures/blob/master/Notebooks/Maps_demo.ipynb)



