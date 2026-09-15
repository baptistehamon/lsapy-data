# lsapy-data
Data repository for [lsapy](https://github.com/baptistehamon/lsapy) tutorials.

## Data Information

### Soil and topographic data
The soil data are extracted from the [_New Zealand Gridded Land Information Dataset_](https://doi.org/10.5281/zenodo.16249350) and include the following variables:
- `drainage`: drainage class
- `ph`: soil pH
- `potential_rooting_depth`: potential rooting depth (m)
- `profile_total_available_water`: profile total available water (mm)
- `salinity`: soil salinity (g 100g-1)
- `slope`: slope (degrees)
- `top_soil_gravel_content`: top soil gravel content (%)

### Climate data
The climate data correspond to (agro)climate indicators derived from the [_New Zealand Climate Projections Dataset_](https://climatedata.environment.govt.nz/) and include the following variables:
- `prcptot`: annual total precipitation (mm)
- `tgmean_0915-1115`: mean daily temperature between Sep 15 and Nov 15 (°C)
- `tnmean_0815-1015`: mean daily minimum temperature between Aug 15 and Oct 15 (°C)
- `txmean_0101-0215`: mean daily maximum temperature between Jan 1 and Feb 15 (°C)
- `year-with-hotweek_1201-0228`: Number of years with at least one hot week (3 days over 35C in a 7-day period) between Dec 1 and Feb 28 (over 10 years)