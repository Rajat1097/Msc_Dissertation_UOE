# Msc_Dissertation_UOE
# Forest disturbance mapping using Radar imagery.
##### Sentinel 1 is a radar satellite. Backscatter value decrease when there is forest canopy loss.
##### The CuSum technique is a statistical-based change detection method utilized for analyzing multi-temporal processes. It exhibits the capability to identify various forms of variations, whether gradual or sudden, that significantly influence the overall trend observed within the time-series data.

------------------------------------------------------------------------------------------------------------------------------------------

### get_disturbancemap_DSC_VH
#### Get a forest disturbance map in the study area using VH polarisation using google earth API in Python. 
-------------------------------------------------------------------------------------------------------------------------
#### get_disturbance_map_comb_vv_VH
#### Get a forest disturbance map in the study area using a combination of VV and VH polarisation using google earth API in Python. 
-------------------------------------------------------------------------------------------------------------------------------------

#### Instruction
#### Run this code using google colab, first have a GEE account, and authorize the project in GEE first otherwise it will not initiate it in Python API. 
#### While uploading the shapefile please keep the projection system as EPSG:4326, and define the year of which you want to see the change. 
#### Final plots will not give output if you don't adjust the coordinates according to your study area.
#### Mount on your own google drive and mention input and output file paths accordingly.
