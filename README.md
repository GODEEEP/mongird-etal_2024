
# mongird-etal_2024_tbd

**How do natural resource availability, technology competition, siting costs, siting policy constraints, transmission constraints, and equity goals interact to determine feasible infrastructure expansion pathways to achieve decarbonization?**


\* corresponding author: kendall.mongird@pnnl.gov

![Projected Power Plant Sitings under Decarbonization](https://github.com/GODEEEP/mongird-etal_2024_tbd/blob/main/figures/layer_maps/map_clean_grid_west_analysis_combined_environment.png)
## Abstract


## Journal reference


## Code reference

## Data references
### Input data
|       Dataset       |               Repository Link                |               DOI                |
|:-------------------:|:--------------------------------------------:|:--------------------------------:|
|   CERF Output       |  |  |
|  GRIDCERF Layers    | | |

### Output data
The post-processed files (resulting from the analysis scripts itemized below) are stored in the /data directory in this meta-repository.

|       Dataset       |                                Repository Link                                |                   DOI                   |
|:-------------------:|:-----------------------------------------------------------------------------:|:---------------------------------------:|
| Post-Processed Data |  |  |


## Contributing modeling software
|  Model   | Version |         Repository Link          | DOI |
|:--------:|:-------:|:--------------------------------:|:---:|
| CERF |  v2.3.2   | https://github.com/IMMM-SFA/cerf | https://doi.org/10.5281/zenodo.7735212 |
| GCAM-USA |  v6.0   | https://github.com/JGCRI/gcam-core | https://doi.org/10.5281/zenodo.8010145 |
| reV |  0.7.1   | https://github.com/NREL/reV | https://doi.org/10.5281/zenodo.8247528 |
|   TELL   |  v1.1   | https://github.com/IMMM-SFA/tell | https://doi.org/10.5281/zenodo.8264217 |
|   GridView   |  v10.3.7   | N/A | N/A|


## Reproduce my analysis
Clone this repository to get access to the notebooks used to conduct the analysis. You'll also need 
to download the input files from the accompanying data repository (). Once you have the input datasets downloaded you can use the following 
notebooks to rerun the analysis and produce the post-processed data. 

|                Script Name                 |                                Description                                 |
|:------------------------------------------:|:--------------------------------------------------------------------------:|
|        calculate_intersections.ipynb              | Calculates how much land from new power plant sitings in each scenario intersects with DACs, Important Farmland, and areas in close proximity to Natural Areas |
|        calculate_suitable_area_scenarios.ipynb    | Calculates how much suitable land is available for solar and wind siting given different combinations of exclusions |


## Reproduce my figures
Use the following notebooks to reproduce the main and supplementary figures used in this publication.

| Figure Numbers |                Script Name                 |                                  Description                                   | 
|:--------------:|:------------------------------------------:|:------------------------------------------------------------------------------:|
| |        plot_infrastructure_maps.ipynb           | Plots power plant sitings under each scenario |
| |        plot_infrastructure_barplots.ipynb       | Calculates the total amount of land used by each technology in each state under each scenario |
| |        plot_raster_intersection_maps.ipynb      | Plots new and retired power plant sitings in each scenario on top of DACs, Important Farmland, and areas in close proximity to Natural Areas |                                                    
| |        plot_raster_intersection_heatmaps.ipynb  | Visualizes how much land from new power plant sitings in each scenario intersects with DACs, Important Farmland, and areas in close proximity to Natural Areas |
| |        plot_siting_suitability_barcharts.ipynb  | Visualizes the comparison of available land for solar and wind siting by exclusion combinations |
