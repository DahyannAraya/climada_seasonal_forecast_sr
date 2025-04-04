<img src="images/Logos.png" alt="Project Logos" width="70%"/>

# **Copernicus Seasonal Forecast Module** 

<img src="images/repo_qr.png" alt="Repository QR Code" width="150"/>

This repository contains two **Jupyter Notebooks** that showcases the functionalities of the new **seasonal forecast module** of [CLIMADA](https://climada.ethz.ch/). The module facilitates the management of **seasonal forecast data** from the [Copernicus Climate Data Store](https://cds.climate.copernicus.eu) (CDS) as part of the [U-CLIMADAPT project](https://www.copernicus-user-uptake.eu/user-uptake/details/responding-to-the-impact-of-climate-change-u-climadapt-488). 
This module provides comprehensive tools for downloading, processing, and computing climate indices, as well as generating hazard objects based on seasonal forecast datasets, particularly [Seasonal forecast daily and subdaily data on single levels](https://cds.climate.copernicus.eu/datasets/seasonal-original-single-levels?tab=overview). 
Designed for seamless integration with the [CLIMADA](https://climada.ethz.ch/) (CLIMate ADAptation) platform, this module supports climate risk assessment and facilitates the development of effective adaptation strategies.


## **Features**
- 📥 **Download** seasonal forecast data from CDS.
- 🔄 **Process** raw seasonal forecast datasets.
- 📊 **Compute climate indices** for analysis.
- 🌍 **Generate hazard objects** for climate risk assessment.
- 📈 **Impact calculation** using CLIMADA’s tools to:
  - Estimate population affected by heat index.
  - Map spatial impact patterns.
  - Analyze forecast impacts across ensemble members.
- 🛠️ **Integration with [CLIMADA](https://climada.ethz.ch/)** (CLIMate ADAptation) for climate impact modeling.

## **Requirements**
Before running the notebook locally, ensure you have the following dependencies installed:

- `climada`
- `climada_petals`
- `cdsapi` [Install and register cdsapi via this link](https://cds.climate.copernicus.eu/how-to-api#install-the-cds-api-client)
- `numpy`
- `pandas`
- `matplotlib`

## **Usage**

This repository provides Jupyter Notebooks to work with **CLIMADA** and the **Copernicus seasonal forecast module**.

There are two notebooks available:

- **`Modul_climada_copernicus_seasonal_forecast_workshop.ipynb`**: This is the first notebook to run. It demonstrates how to install and use the `copernicus_interface` module to download, process, and convert seasonal forecast data into a CLIMADA hazard object.
- **`DEMO_Modul_climada_copernicus_seasonal_forecast_workshop.ipynb`**: This is the second notebook. It provides a full example application of the seasonal forecast hazard data in an end-to-end climate impact assessment pipeline.

### Notebooks

| Notebook | Open in Colab | GitHub Link |
|----------|----------------|-------------|
| `Modul_climada_copernicus_seasonal_forecast_workshop.ipynb` | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" height="20">](https://colab.research.google.com/github/DahyannAraya/climada_copernicus_seasonal_forecast_workshop/blob/main/Modul_climada_copernicus_seasonal_forecast_workshop.ipynb) | [View on GitHub](https://github.com/DahyannAraya/climada_copernicus_seasonal_forecast_workshop/blob/main/Modul_climada_copernicus_seasonal_forecast_workshop.ipynb) |
| `DEMO_Modul_climada_copernicus_seasonal_forecast_workshop.ipynb` | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" height="20">](https://colab.research.google.com/github/DahyannAraya/climada_copernicus_seasonal_forecast_workshop/blob/main/DEMO_Modul_climada_copernicus_seasonal_forecast_workshop.ipynb) | [View on GitHub](https://github.com/DahyannAraya/climada_copernicus_seasonal_forecast_workshop/blob/main/DEMO_Modul_climada_copernicus_seasonal_forecast_workshop.ipynb) |

---

### Run in Colab

1. Click on **Open in Colab** for the notebook of interest.
2. Make sure you follow all the setup cells in the notebook to install **CLIMADA** and its dependencies.

---

### Run Locally

If you plan to run this notebook locally, you must first install **CLIMADA** and all required dependencies on your system.  
👉 For detailed instructions, follow the official CLIMADA installation guide:  
**[CLIMADA Installation Guide](https://climada-python.readthedocs.io/en/stable/guide/install.html)**

After installing CLIMADA, you should also install the **seasonal forecast module** by following the instructions in the document below:  
👉 [Copernicus Forecast Module Installation Instructions (PDF)](https://drive.google.com/file/d/1NpAslBYLbhUb3W55D43qIWu0zJPCPoAJ/view?usp=sharing)

Alternatively, you can install the module manually by cloning the repository:

```bash
git clone https://github.com/DahyannAraya/climada_copernicus_seasonal_forecast_workshop.git
cd climada_copernicus_seasonal_forecast_workshop
```

## **References**
- [Copernicus Seasonal Forecast Module](https://github.com/CLIMADA-project/climada_petals/tree/feature/copernicus_forecast)
- [Seasonal forecast daily and subdaily data on single levels](https://cds.climate.copernicus.eu/datasets/seasonal-original-single-levels?tab=overview)
- [Copernicus Climate Data Store](https://cds.climate.copernicus.eu)
- [CLIMADA Documentation](https://climada.ethz.ch/)
- [U-CLIMADAPT Project](https://www.copernicus-user-uptake.eu/user-uptake/details/responding-to-the-impact-of-climate-change-u-climadapt-488)
