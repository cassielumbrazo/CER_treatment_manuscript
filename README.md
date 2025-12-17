# CER_treatment_manuscript 
## Cle Elum Ridge (CER) Forest Treatment Manuscript GitHub Repo
Author: Cassie Lumbrazo\
Email: cassielumbrazo@gmail.com
Last updated: Dec 2025

### Summary 
This repo contains all the scripts to reproduce the analysis and final figures in `Lumbrazo et al. (2025)`.\
Scripts named `#_description` in the filename contain the all the previous and present analysis, while the scripts named `figure#_` contain the construction of the final manuscript figures. 

#### Related Resources 
This github repo complements the accepted manuscript:
> Lumbrazo et al. (2025), “Can we maximize snow storage through fire-resilient forest treatments? Insights from experimental forest treatments in the Eastern Cascades, WA, USA,” accepted in Frontiers in Forests and Global Change, Forest Hydrology section (doi:10.3389/ffgc.2025.1707812).

Data repo with files required to run these notebooks:
> Lumbrazo, C., J. Cramblitt, E. R. Howe, S. E. Dickerson-Lange, S. Pestana, K. Dedinsky, M. Stuart, K. Smith, J. D. Lundquist (2025). Cle Elum Ridge Forest Treatment Region Dataset, HydroShare, https://doi.org/10.4211/hs.96f4199c0e4c48e6bc0ea7f9251b16dd


#### Repo Contents 
*Description of the analysis notebook contents*\
This repo contains cleaned up scripts from other analysis repos, `CER_raster_analysis` and `RAPID_raster_analysis` to prepare the final analysis scripts for manuscript publication. 

`1_create_netcdf.ipynb`: bring all the raw tif files together into a simple stacked netcdf\
`2_export_netcdf_varibales_as_tifs.ipynb`: export the cleaned up netcdfs from notebook 1\
`3_update_netcdf_all_varibales.ipynb`: create an "all variables" netcdf which contains all the variables needed for future notebooks\
`4_domain_plots.ipynb`: raster domain plots for manuscript figures\
`5_cdf.ipynb`: Cumulative Distribition Functions (CDF)s for all the treatment areas\
`6_svd.ipynb`: Standardized Depth Value (SDV) calculations to compare snow depth before and after the forest treatments\
`7_canopy_cover.ipynb`: first notebook calculating simple percentage of canopy cover over the treatment areas\
`8_canopy_cover_aspect.ipynb`: building on notebook 7 to do this by aspect (side of the ridge)\
`9_canopy_cover_type.ipynb`: exploring the type of canopy cover, such as understory shrubs and overstory canopy cover\
`10_canopy_cover_type_aspect.ipynb`: further exploring canopy cover type, but adding in aspect by side of the ridge\
`11_delta_dce_categories.ipynb`: create the deltaDCE categories and corresponding CDFs\
`11_delta_dce_catgeories_check.ipynb`: notebook created during review to create extra figures and double check the anaylsis as no mistakes\
`example_notebook.ipynb`: starter notebook to create a new one from

*Description of the figure notebook contents*
`figure2_3_domain.ipynb`: figure 2\
`figure3_all_together.ipynb`: figure 3\
`figure4_deltadce_treatment_maps.ipynb`: figure 4\
... etc. 

