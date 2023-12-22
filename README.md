# Global Forest Datasets Analysis
Code accompanying global forest cover paper
Citation: 
Code author: Sarah Castle (saraheb3@illinois.edu), University of Illinois Urbana-Champaign

## Purpose:
Google Earth Engine code accompanying our paper comparing global forest cover and forest cover change datasets. Code provided allows users the replicate our analyses in Google Earth Engine. 

## Data availability:
All datasets used in this study were derived from published sources cited in the Methods section. The following datasets are available through the Google Earth Engine (GEE) Data Catalog (Accessed: 15 December 2023): 
1.	Copernicus Global Land Cover (https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_Landcover_100m_Proba-V-C3_Global)
2.	ESA WorldCover (https://developers.google.com/earth-engine/datasets/catalog/ESA_WorldCover_v100 and https://developers.google.com/earth-engine/datasets/catalog/ESA_WorldCover_v200)
3.	JAXA Forest/Non- Forest (https://developers.google.com/earth-engine/datasets/catalog/JAXA_ALOS_PALSAR_YEARLY_FNF4)
4.	MODIS Land Cover Type (https://developers.google.com/earth-engine/datasets/catalog/MODIS_061_MCD12Q1)
5.	Hansen Global Forest Change (https://developers.google.com/earth-engine/datasets/catalog/UMD_hansen_global_forest_change_2022_v1_10)
6.	WorldPop for administrative boundaries and gridded population density data (https://developers.google.com/earth-engine/datasets/catalog/WorldPop_GP_100m_pop). 
7.	RESOLVE Ecoregions 2017 for biome limits (https://developers.google.com/earth-engine/datasets/catalog/RESOLVE_ECOREGIONS_2017)
ESA Copernicus Climate Change Service Land Cover was available for download from https://cds.climate.copernicus.eu/cdsapp#!/dataset/satellite-land-cover (Accessed: 15 December 2023). ESRI Land Cover was available on GEE using the code available from https://gee-community-catalog.org/projects/S2TSLULC/ (Accessed: 15 December 2023). GLAD Global Land Cover and Land Use Change was available on GEE using the code available from https://glad.umd.edu/dataset/GLCLUC2020 (Accessed: 15 December 2023). Vancutsem Tropical Moist Forest Cover Change was available on GEE using the code available from https://forobs.jrc.ec.europa.eu/TMF (Accessed: 15 December 2023). 
Spawn et al.’s aboveground and belowground biomass carbon density data is available to download from https://daac.ornl.gov/VEGETATION/guides/Global_Maps_C_Density_2010.html (Accessed: 15 December 2023). The species habitat ranges were obtained for the IUCN Red List database (available for download from: https://www.iucnredlist.org with valid request; Accessed: 15 December 2023). Gridded relative wealth index data from Chi et al. (2022) were downloaded from https://data.humdata.org/dataset/relative-wealth-index (Accessed: 15 December 2023).

## Google Earth Engine Assets to import
Rural-urban extents asset used in forest-proximate people in poverty analysis: https://code.earthengine.google.com/?asset=users/saraheb3/ruralPop_IND_GEEasset_2017
See data availability for data downloads that user needs to import into Google Earth Engine.

## Use:
All code is written in JavaScript for Google Earth Engine.
