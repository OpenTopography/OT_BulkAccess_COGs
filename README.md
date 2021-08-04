[![NSF-1948997](https://img.shields.io/badge/NSF-1948997-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1948997) 
[![NSF-1948994](https://img.shields.io/badge/NSF-1948994-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1948994)
[![NSF-1948857](https://img.shields.io/badge/NSF-1948857-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1948857)

# OpenTopography Jupyter Notebook Examples

This repo contains some example jupyter notebooks for working with [OpenTopography data](https://opentopography.org/) and [APIs](https://opentopography.org/developers#API).

* [OT_01_BulkAccessCOGs.ipynb](https://github.com/OpenTopography/Jupyter/blob/main/OT_01_BulkAccessCOGs.ipynb) - OpenTopography has recently converted its entire global dataset collection to COGs. This notebook example highlights the power of Cloud Optimized GeoTIFFs (COGs) and how they can be used to reduce download filesizes as well as increase data access speeds.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OpenTopography/Jupyter/main?filepath=OT_01_BulkAccessCOGs.ipynb)

* [OT_02_RayShader.ipynb](https://github.com/OpenTopography/Jupyter/blob/main/OT_02_RayShader.ipynb) - This is an R Markdown Notebook created by OpenTopography profiling the [RayShader](https://cran.r-project.org/web/packages/rayshader/rayshader.pdf) package. This package utilizes a combination of raytracing and multiple hill shading methods to produce 2D and 3D data visualizations and maps.

* [OT_03_VoxeltoSTL.ipynb](https://github.com/OpenTopography/Jupyter/blob/main/OT_03_VoxeltoSTL.ipynb) - This notebook uses a Voxel subsampling method for point cloud data thinning. After the point cloud has been thinned, triangulation is computed to create a mesh which can be exported as a STL file and opened in a variety of 3D modeling software.

Email: info@opentopography.org with any questions or comments
