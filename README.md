# Welcome to WEkEO4Atmosphere

**wekeo4atmosphere** is a repository of Python based tools to introduce you to atmospheric data on the [WEkEO DIAS (Data Information
and Access System)](https://wekeo.eu/) and its JupyterHub. With the help of cases studies about the monitoring of wildfires and air quality, Copernicus atmosphere data from the Copernicus Programme are introduced. Practical examples showcase how to access, load, browse and visualise data.

The content provided is based on [Jupyter Notebooks](https://jupyter.org/), which allow a high-level of interactive learning, as code, text description and visualisation 
is combined in one place.

## Copernicus Data
The notebooks feature the following Copernicus datasets for atmospheric applications

* **Satellite-based datasets**:
  * [Copernicus Sentinel-5P TROPOMI](https://www.wekeo.eu/data?view=dataset&dataset=EO%3AESA%3ADAT%3ASENTINEL-5P%3ATROPOMI)
    * Level 2 Carbon Monoxide product
    * Level 2 Nitrogen Dioxide product
  * [Copernicus Sentinel-3 OLCI Level-1B Full Resolution](https://www.wekeo.eu/data?view=dataset&dataset=EO%3AEUM%3ADAT%3ASENTINEL-3%3AOL_1_EFR___)


* **Model-based datasets**:
  * [CAMS global reanalysis (EAC4)](https://www.wekeo.eu/data?view=dataset&dataset=EO%3AECMWF%3ADAT%3ACAMS_GLOBAL_REANALYSIS_EAC4)
  * [CAMS European air quality forecasts](https://www.wekeo.eu/data?view=dataset&dataset=EO%3AECMWF%3ADAT%3ACAMS_EUROPE_AIR_QUALITY_FORECASTS)


## Repository overview
This repository is organised in two atmospheric case studies on (i) fire monitoring and (ii) air quality. For each case study a set of Copernicus data is introduced that is suitable for fire or air quality applications and available via WEkEO. Each dataset is introduced via two notebooks: the first notebooks show how to retrieve the respective dataset from WEkEO (*retrieve* notebooks) and the second notebook offers a practical example on how to load, browse and visualise the dataset (*explore* notebooks).
The following notebook are available:
* Case study **fire monitoring** (folder `./fire/`):
  * [10 - Sentinel-5P Level 2 Carbon Monoxide - Retrieve](./fire/10_Sentinel5P_L2_CO_retrieve.ipynb)
  * [11 - Sentinel-5P Level 2 Carbon Monoxide - Explore](./fire/11_Sentinel5P_L2_CO_explore.ipynb)
  * [20 - Sentinel-3 OLCI Level 1B - Retrieve](./fire/20_Sentinel3_OLCI_L1_retrieve.ipynb)
  * [21 - Sentinel-3 OLCI Level 1B - Explore](./fire/21_Sentinel3_OLCI_L1_explore.ipynb)
  * [30 - CAMS global reanalysis EAC4 - Retrieve](./fire/30_CAMS_EAC4_retrieve.ipynb)
  * [31 - CAMS global reanalysis EAC4 - Explore](./fire/31_CAMS_EAC4_explore.ipynb)

<br>

* Case study **air quality** (folder `./air_quality/`):
  * [10 - Sentinel-5P Level 2 Nitrogen Dioxide - Retrieve](./air_quality/10_Sentinel5P_L2_NO2_retrieve.ipynb)
  * [11 - Sentinel-5P Level 2 Nitrogen Dioxide - Explore](./air_quality/11_Sentinel5P_L2_NO2_explore.ipynb)
  * [20 - CAMS European air quality forecast - Nitrogen Dioxide - Retrieve](./air_quality/20_CAMS_European_air_quality_forecast_NO2_retrieve.ipynb)
  * [21 - CAMS European air quality forecast - Nitrogen Dioxide - Explore](./air_quality/21_CAMS_European_air_quality_forecast_NO2_explore.ipynb)

## How to use this material

If you are on GitHub/Lab you can visit www.wekeo.eu, register for an account and enter the JupyterHub - then follow the instructions below. 

If you are currently on the WEkEO JupyterLab you're already in the right place and can start. To clone this repository in to the WEkEO JupyterHub environment open a terminal in the WEkEO JupyterHub and type:
  > `cd work`<br>
  > `git clone https://github.com/wekeo/wekeo4atmosphere.git`<br> 
 
This will create a clone of this repository in the work directory on your WEkEO JupyterHub instance. You can use the same command to clone any external repository you like.
You can also use this code on your own computer/JupyterHub server, however you will not have the fast access provided by the Harmonized Data Access as part of the WEkEO infrastructure.


### Recommended Python set up

The content in this repository has been tested with Python version 3.8.15. We highly recommend that users working on their own systems install the appropriate Anaconda distribution for their operating system. Here is a link to the [Anaconda distribution of Python 3.8](https://www.anaconda.com/products/individual).

### Python environment

Python allows users to create specific environments that suit their applications. This tutorial requires a number of specific Python packages and their respective versions. You can see the full list in the [environment.yml](./environment.yml) file. WEkEO's JupyterHub environment has already all required packages installed. You might need to install them for your local installation.

