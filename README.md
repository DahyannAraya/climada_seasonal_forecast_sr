<img src="images/Logos.png" alt="Project Logos" width="70%"/>

# **Code Sample - Copernicus Seasonal Forecast Module** 

This repository contains the **core implementation script** of the **seasonal forecast module** of [CLIMADA](https://climada.ethz.ch/), developed as part of the [U-CLIMADAPT project](https://www.copernicus-user-uptake.eu/user-uptake/details/responding-to-the-impact-of-climate-change-u-climadapt-488). The module facilitates the management of **seasonal forecast data** from the [Copernicus Climate Data Store](https://cds.climate.copernicus.eu), particularly the [Seasonal forecast daily and subdaily data on single levels](https://cds.climate.copernicus.eu/datasets/seasonal-original-single-levels?tab=overview).

I think this code is a strong example of my recent work. It presents the core class `SeasonalForecast`, which manages the entire data pipeline — from downloading, processing, and analyzing seasonal forecast data to computing climate indices (e.g., Heatwave Days, Tropical Nights) and generating CLIMADA-compatible `Hazard` objects for impact modeling. The module is designed for seamless integration with the CLIMADA Petals extension and supports impact-based forecasting.

Note: This seasonal forecast module is currently under development and not yet part of the official CLIMADA Petals release. It is scheduled for integration in the mid 2025 CLIMADA release. 

👉 You can access the **code** in the following formats:

| Access Method           | Description                                                  |
|--------------------------|--------------------------------------------------------------|
| [View as PDF](https://github.com/DahyannAraya/climada_seasonal_forecast_sr/blob/main/create_seasonal_forecast_hazard.pdf)            | View the main script in a printable PDF format               |
| [View Python Script](https://github.com/DahyannAraya/climada_seasonal_forecast_sr/blob/main/create_seasonal_forecast_hazard.py)     | Open the `.py` source code directly in the GitHub repository |
| [CLIMADA Repository](https://github.com/CLIMADA-project/climada_petals/blob/feature/copernicus_forecast/climada_petals/hazard/copernicus_interface/create_seasonal_forecast_hazard.py)     | Link python script on CLIMADA Petals repository    |



# **Extra Material** 
For and demostration of its aplication visit

<img src="images/repo_qr.png" alt="Repository QR Code" width="150"/>
