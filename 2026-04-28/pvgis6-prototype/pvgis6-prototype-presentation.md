# Thank You PyData Lausanne

- Great atmosphere
- Feeling like @ home

# Context

## Photovoltaics & EU Policy

- 55% GHG reduction by 2030
_requires at least 3x increased installed PV capacity_
- Energy relevant Directives

## PVGIS ?

**P**hoto**v**oltaic  
**G**eographic *al*  
**I**nformation  
**S**ystem  

- Example @ https://re.jrc.ec.europa.eu/pvg_tools/en/

# PVGIS <= _5_

- What can I do with PVGIS 5 ?

![PVGIS 5, a public service for everyone](images/pvgis5_public_service_for_everyone.jpg)

- Impact

![PVGIS 5, Impact](images/pvgis5_impact.jpg)

- Thomas **Huld**

  ![Thomas Huld](images/Thomas_Huld.jpg)

## Challenges

- **Old-style** software project
- 100% bus factor

# PVGIS 6

## What is PVGIS _6_ ?

## Development

- Show a _Gource_ animation
- Architecture
- Pair Programming : *****

## Data Processing 

One off processing:


- Collect > Rechunk > Zarr stores

![Data Processing](images/pvgis6_one_off_preprocessing_and_main_processing_in_1_second.jpg)

Every location (==pixel) processing :

\> Parallel request of multiple time series for @ x,y  
&nbsp; \> [any] **Xarray** [-supported format]  
&nbsp; &nbsp; \> Array Backend [ **NumPy** | Dask | .. ]  
&nbsp; &nbsp; &nbsp; \> Analysis of Photovoltaic performance  
&nbsp; &nbsp; &nbsp; &nbsp; \> **Output** [JSON, CSV, Command Line]

### Timing of reading time series

![Data one off pre-processing](images/timing_reading_chunked_data_from_a_zarr_store.jpg)

## Architecture

- Modular
- As possible self-contained
- Show the code...

## For whom is PVGIS 6 ?

| User group \ Component     | Web Application | Web API | CLI  | Core API | Algorithms |
|----------------------------|-----------------|---------|------|----------|------------|
| Citizens & Prosumers       | +++             | +       |      |          |            |
| Professionals & Installers | ++/+            | ++      | /+   |          | /+         |
| Researchers                | ++              | ++/+    | ++/+ | +/+      | +++        |
| Developers & Power Users   |                 | ++/+    | +++  | +++      | +++        |


## Programming

- Do we have time to go through some `.py` modules ?

## Examples

## Web API

![PVGIS 6 Prototype FastAPI-based Web-API](images/pvgis6_prototype_fastapi_web_api.png)

## Solar positioning

![Solar positioning](images/pvgis6_solar_positioning.jpg)

## Photovoltaic power

![Photovoltaic power](images/pvgis6_photovoltaic_power.jpg)

## Photovoltaic performance

![Photovoltaic performance](images/pvgis6_photovoltaic_performance.jpg)

##  Direct inclined irradiance 

![Direct inclined irradiance](images/pvgis6_direct_inclined_irradiance_from_sarah3.jpg)

## Solar radiation time series

![Solar radiation time series](images/pvgis6_prototype_reading_from_sis_time_series.jpg)

## Typical Meteorological Year

![Typical Meteorological Year Direct Normal Irradiance](images/pvgis6_typical_meteorological_year_direct_normal_irradiance.png)
![Typical Meteorological Year Global Horizontal Irradiance](images/pvgis6_typical_meteorological_year_global_horizontal_irradiance.png)
![Typical Meteorological Year x](images/pvgis6_typical_meteorological_year_min_dry_bulb_temperature.png)
![Typical Meteorological Year x](images/pvgis6_typical_meteorological_year_mean_dry_bulb_temperature.png)
![Typical Meteorological Year x](images/pvgis6_typical_meteorological_year_max_dry_bulb_temperature.png)
![Typical Meteorological Year x](images/pvgis6_typical_meteorological_year_mean_relative_humidity.png)
![Typical Meteorological Year x](images/pvgis6_typical_meteorological_year_mean_wind_speed.png)

# Acknowledgements

![Acknowledgements](images/acknowledgments.jpg)

# Supporing material

## Analysis of Photovoltaic Performance

![Analysis of PV performance](images/analysis_of_pv_performance.jpg)

## Spectal Factor Methods 

![Spectal Factor Methods](images/spectral_factor_methods.jpg)

## Optimal Orientation and/or Tilt

![Optimal Orientation and/or Tilt](images/optimal_orientation_and_or_tilt.jpg)

## PVGIS 6 Features & Highlights

![PVGIS 6 Features & Highlights](images/pvgis6_features_and_highlights.jpg)

## PVGIS 6 vs 5

### Functionality comparison

![PVGIS 6 vs 5 Functionalities](images/pvgis6_vs_pvgis5_functionality_comparison.jpg)

### Programmatic comparison

![PVGIS 6 vs 5 Functionalities](images/pvgis6_vs_pvgis5_programmatic_comparison.jpg)
