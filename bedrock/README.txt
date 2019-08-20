README FILE FOR BEDROCK ANALYSIS IN ROSSI ET AL. (IN REVIEW)
Version 1.0
08.20.2019
--------------------------------------------------------------------------------------------------------------------
Please cite associated manuscript:
Rossi, M.W., Anderson, R.S., Anderson, S.P., and Tucker, G.E. (in review) Orographic controls on sub-daily rainfall
statistics and flood frequency in the Colorado Front Range, USA. Geophysical Research Letters.
-------------------------------------------------------------------------------------------------------------------- 

I. OVERVIEW
Bedrock analysis is based on bedrock mapping by M.W. Rossi for eight patches in the Boulder Creek watershed using
high resolution aerial imagery. At these sites, slope-threshold proxies derived from 1-m lidar topography were 
calibrated against bedrock maps. Calibrated topographic proxies were then used to characterize the fraction of rock
within elevation bins in the Boulder Creek watershed. Source aerial imagery and lidar topography are not archived
here and can be downloaded from their sources. Derived products for calibration patches are archived here.

Aerial Imagery
Air photos are mosaicked nadir images acquired by Pictometry International and purchased by Boulder County. Spatial
resolution is 3 inches and flights were flown over the period of 4/03/2018 to 06/03/2018. Source data is at:
https://www.arcgis.com/home/item.html?id=cbdead308b814738916d1379df8671fa

Lidar Topography
Lidar was acquired by the National Center for Airborne Laser Mapping for the Boulder Creek Critical Zone Observatory
and funded by NSF (EAR-1043051). This work uses the 1-m gridded digital terrain model and derivatives. Flights were
flown over the period of 08/21/2010 to 08/26/2010. Source data is at:
http://opentopo.sdsc.edu/datasetMetadata?otCollectionID=OT.032012.26913.1

II. CONTENTS
This directory contains a .kmz file showing the locations of the eight calibration patches as well as a geodatabase
containing the files needed to relate these maps to 1-m lidar slope-thresholds.

File				Description
--------------------------------------------------------------------------------------------------------------------
calibration_patches.kmz		location of calibration patches to view in Google Earth
calibration_patches.gdb		geodatabase includes vector version of classification maps, derived 1-m raster of
				classification maps, and 1-m raster of slope for each patch
--------------------------------------------------------------------------------------------------------------------

III. PATCH DESCRIPTIONS
Calibration patches for slope-threshold proxies. Detailed analysis and descriptions of patches is found in SI Figs. 
S7 through S10 and Table S3.

Name	Size (m)	Brief Description
------------------------------------------------------------------------------------
P01	200x200 	side-slope along Boulder Creek near outlet to Plains
P02	50x50		within small catchment draining into Fourmile Creek
P03	50x50		within small catchment draining into Gold Run
P04	50x50		within small catchment draining into Boulder Creek
P05	50x50		side-slope along Boulder Creek within knickzone
P06	50x50		near Gordon Creek on high elevation, low relief surface
P07	50x50		side-slope along Blackhawk Gulch
P08	200x200 	near Barker Reservoir on high elevation, low relief surface
------------------------------------------------------------------------------------

IV. CLASSIFICATION DEFINITIONS
For both vector and raster versions of classification maps, images were characterized into four classes. Detailed
descriptions of mapping criteria are found in SI Text S4.

Code	Decription
---------------------------------------------
10	bedrock
20	colluvium
30	green canopy obscuring surface
35	other woody canopy obscuring surface
---------------------------------------------