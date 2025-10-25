## HW 4 Scott Thomas Andersen -- ATMS 523

In this assignment I collect data from copernicus following the specification from the first question. The ERA 5 monthly averaged data from 1979 to 2024. The data is detrended and standardized before performing the empirical orthogonal function analysis. I then calculate the principal components and visualize the first 5 as well as exsamine the percent variance explained by the first 10 EOFs. I reconstruct the data and examine the correlation coefficient with the standardized SST. Finally I calculatethe pearson correlation coefficient of the principal component lengths of the first eigen vector to the total column water vapor across the land. 


Citations

EOF python package is available here: http://doi.org/10.5334/jors.122, and requests the citation be made to:
Dawson, A. (2016) ‘eofs: A Library for EOF Analysis of Meteorological, Oceanographic, and Climate Data’, ~Journal of Open Research Software~, 4(1), p. e14. Available at: https://doi.org/10.5334/jors.122.

Hersbach, H., Bell, B., Berrisford, P., Biavati, G., Horányi, A., Muñoz Sabater, J., Nicolas, J., Peubey, C., Radu, R., Rozum, I., Schepers, D., Simmons, A., Soci, C., Dee, D., Thépaut, J-N. (2023): ERA5 monthly averaged data on single levels from 1940 to present. Copernicus Climate Change Service (C3S) Climate Data Store (CDS), DOI: 10.24381/cds.f17050d7 (Accessed on 20-10-2025)
