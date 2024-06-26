# CER_treatment_manuscript
## Cle Elum Ridge (CER) Forest Treatment Manuscript GitHub Repo
Author: Cassie Lumbrazo
Date: June 2024

This repo contains cleaned up scripts from other analysis repos, `CER_raster_analysis` and `RAPID_raster_analysis` to prepare the final analysis scripts for manuscript publication. 

### Repo Contents 
`1_create_netcdf.ipynb`: bring all the raw tif files together into a simple stacked netcdf 

`2_export_netcdf_varibales_as_tifs.ipynb`: export the cleaned up netcdfs from notebook 1

`3_update_netcdf_all_varibales.ipynb`: create an "all variables" netcdf which contains all the variables needed for future notebooks

`4_domain_plots.ipynb`: raster domain plots for manuscript figures 

`5_cdf.ipynb`: Cumulative Distribition Functions (CDF)s for all the treatment areas

`6_svd.ipynb`: Standardized Depth Value (SDV) calculations to compare snow depth before and after the forest treatments 

`7_canopy_cover.ipynb`: first notebook calculating simple percentage of canopy cover over the treatment areas

`8_canopy_cover_aspect.ipynb`: building on notebook 7 to do this by aspect (side of the ridge)

`9_canopy_cover_type.ipynb`: exploring the type of canopy cover, such as understory shrubs and overstory canopy cover 

`example_notebook.ipynb`: starter notebook to create a new one from
