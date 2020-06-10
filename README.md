# Raster Files in Python

[![Miniconda](https://img.shields.io/badge/miniconda-3-green)](https://docs.conda.io/en/latest/miniconda.html)
[![Python](https://img.shields.io/badge/python-3.8-green)](https://www.python.org/)
[![JupyterLab](https://img.shields.io/badge/jupyter-1.0-green)](https://jupyter.org/)
[![rasterio](https://img.shields.io/badge/rasterio-latest-green)](https://pypi.org/project/rasterio/)
[![rasterstats](https://img.shields.io/badge/rasterstats-latest-green)](https://pypi.org/project/rasterstats/)

Working with raster files in python with `rasterio` and `rasterstats` .

## Create an Conda Virtual Environment

~~~shell
# Create an environment with Miniconda
$ conda create --name raster-files python==3.8

# Activate the environment
$ conda activate raster-files
~~~

## Installing dependencies

~~~shell
# Install requirements
(raster-files) $ python -m pip install -r requirements.txt

# Create a kernel with Miniconda python configuration
(raster-files) $ ipython kernel install --user --name raster-files
~~~

## Running

~~~shell
(raster-files) $ jupyter-notebook
~~~