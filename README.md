# ERA5 Pacific SST & TCWV EOF Analysis — Xarray & Sci-Kit Learn Teaching Template

This repository contains a Jupyter notebook that demonstrates how to work with ERA5 monthly mean data from NCAR/ECMWF to compute and analyze Sea Surface Temperature (SST) anomalies and total column water vapor (TCWV) over the Pacific Basin. 

- **Variables used:**  
  - `sst` — Sea Surface Temperature (K)  
  - `tcrw` — Total Column Water Vapor (kg/m²)  
- **Spatial domain:** Pacific Basin: 65°N–65°S, 120°E–60°W (converted to 0–360° longitude as needed)  
- **Time period:** January 1979 – December 2024  
- **File format:** NetCDF (`.nc`)

## Learning Objectives

- Load ERA5 monthly mean data using `xarray`  
- Subset the Pacific Basin spatial domain  
- Detrend and deseasonalize SST and TCWV data  
- Compute monthly anomalies and standardize SST  
- Perform EOF analysis using `scikit-learn` PCA  
- Reconstruct SST fields from leading EOFs and compute correlation maps  
- Visualize EOF spatial patterns, variance explained, and correlation maps

## Analyses & Plots

- **Variance Fraction:** Fraction of total variance explained by first 10 EOFs  
- **EOF Maps:** First 5 SST EOFs over the Pacific Basin  
- **SST Reconstruction:** Correlation between reconstructed SST and observed SST  
- **SST-TCWV Coupling:** Pearson correlation between SST EOF1 and monthly TCWV anomalies  

## Attribution

- ERA5 data © ECMWF, distributed via [Copernicus Climate Data Store](https://cds.climate.copernicus.eu/)  
- Respect the dataset license and terms of use  

## References

- Sci-Kit Learn PCA documentation: [https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html)  
- Xarray documentation: [https://xarray.pydata.org/en/stable/](https://xarray.pydata.org/en/stable/)  
- Copernicus ERA5 dataset: [https://cds.climate.copernicus.eu/](https://cds.climate.copernicus.eu/)

- ## License

This repository is licensed under the [MIT License](LICENSE).

