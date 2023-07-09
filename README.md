# WaterSatOnCloud
Water specific Satellite Imagery processing on Cloud Platforms

This project includes tools we developed when attending a [Algal Bloom Contest]()

## Introduction
This repository provides tools for collecting Sentinel-2 MSI (S2MSI) and Landsat 8/9 (LST8) matchups with in situ water samples and building bio-optical models that derive water properties, such as [Chl], of small water bodies through remote sensing.


## Tools
Here are a list of tools that provided in this package.

1. GEE S2 satellite data extraction (Level 1 and level 2), with user-defined locations and time (lat, lon, datetime field in a .csv)
2. GEE LST8 satellite data extraction (level 1 and level 2), with user-defined locations and time (lat, lon, datetime field in a .csv)
3. Climate and meteorological data extraction, with user-defined locations and time   
4. Machine learning training models (RF, lightGBM, TENSORFLOW) , category classification or numeric regression
5. Py6S for Rayleigh Correction of level-1 data.
6. [GLORIA](https://www.nature.com/articles/s41597-023-01973-y) dataset for training example
7. ...

## How to use

- use the `.ipynb` files and open in google collab to follow the code step by step
- use the `.py` files of the same name as part of your project. (python environment managemnet, conda...)

## Contributors
- [Yulun Wu ](Yulun.Wu@uottawa.ca)
- [Chui Zeng](chqzeng@gmail.com)

