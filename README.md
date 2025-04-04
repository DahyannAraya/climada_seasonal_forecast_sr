<img src="images/Logos.png" alt="Project Logos" width="70%"/>

# **Copernicus Seasonal Forecast Module** 

<img src="images/repo_qr.png" alt="Repository QR Code" width="150"/>


This repository contains the core **single Python script** of the new **seasonal forecast module** of [CLIMADA](https://climada.ethz.ch/), developed as part of the [U-CLIMADAPT project](https://www.copernicus-user-uptake.eu/user-uptake/details/responding-to-the-impact-of-climate-change-u-climadapt-488). The module facilitates the management of **seasonal forecast data** from the [Copernicus Climate Data Store](https://cds.climate.copernicus.eu), particularly the [Seasonal forecast daily and subdaily data on single levels](https://cds.climate.copernicus.eu/datasets/seasonal-original-single-levels?tab=overview).

This implementation provides a modular pipeline for downloading, processing, and analyzing seasonal forecast data, computing climate indices (e.g., Heatwave Days, Tropical Nights), and generating CLIMADA-compatible `Hazard` objects for impact modeling. It is designed for seamless integration with the CLIMADA Petals extension and supports impact-base forescasting.

The core class `SeasonalForecast` manages the entire data pipeline — from raw data download to hazard creation — and includes utilities for file checking, plotting forecast skill metrics, and structured output path generation according to CLIMADA conventions.

Note: This seasonal forecast module is currently under development and not yet part of the official CLIMADA Petals release. It is scheduled for integration in the 2025 CLIMADA release. The code provided here represents early development work within the U-CLIMADAPT project and is available through the CLIMADA open-source development codebase.

👉 Here is the code, you acces to they code via :

| Access Method           | Description                                                  |
|--------------------------|--------------------------------------------------------------|
| View as PDF            | View the main script in a printable PDF format               |
| View Python Script     | Open the `.py` source code directly in the GitHub repository |
| CLIMADA Repository     | Link to the official CLIMADA or CLIMADA Petals repository    |



# **Extra Material** 

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
