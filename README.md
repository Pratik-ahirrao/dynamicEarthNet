# dynamicEarthNet
# Problem Statement
The task is to reduce the computation time of calculating MNDWI and NDVI in-
dices for satellite images from the DynamicEarthNet Dataset and storing them in
GeoTIFF format using Dask. DynamicEarthNet is the first dataset that provides
this unique combination of daily measurements and high-quality labels. It consists
of daily, multi-spectral satellite observations of 75 selected areas of interest (AOIs)
distributed over the globe with imagery from Planet Labs. These observations are
paired with pixel-wise monthly semantic segmentation labels of 7 land use and land
cover (LULC) classes. The dataset can be downloaded from [DynamicEarthNet](https://mediatum.ub.tum.de/1650201). Out
of these 75 AOIs, we will focus mainly on two AOIs i.e. planet16N and planet18N.

# Installation Steps

Before running the notebook, create two folders ndvi-images and mndwi-images in the same
directory. The following modules/libraries should be installed in your system before
running the notebook:
1. rasterio: A Python module for reading and writing geospatial raster data. It allows
users to work with a wide variety of raster data formats, including GeoTIFF.

```sh
# pip and python must be installed in your system
$ pip install rasterio
```
2. Dask: Dask is a parallel computing library for Python that enables parallel and
distributed computing across multiple CPU cores or clusters. It allows users to
work with large datasets that are too big to fit into memory on a single ma-
chine, by breaking them into smaller partitions and distributing them across
multiple processors or machines.

```sh
# pip and python must be installed in your system
$ pip install dask
```
3. PyTorch is a Python package that helps in Tensor computation (like
NumPy) with strong GPU acceleration

```sh
# pip and python must be installed in your system
$ pip install torch
```
4. Make sure modules like numpy, matlpotlib are installed.


