# IMOS_Toolbox
A repo for useful IMOS code relating to plankton and satellite data

fIMOS_MatchMODIS.R is a function which does all the heavy lifting. It will download any MODIS data from the IMOS DAP Server

fIMOS_MatchAltimetry.R is a function which downloads Altimtery data from the IMOS DAP server

Example_MatchSat_2_NRS.R is a parent script which can be used to run and test the download of satellite data

TestData* is a test data file (NRS Zooplankton Higher Trophic Levels) as a source of lat/lon/date for the satellite data download.


**NOTE:** If you are on a Windows PC - You will need to install a development version of ncdf4 which allows the use of OpenDAP. Please run ```devtools::install_github('mdsumner/ncdf4')``` to install or see https://github.com/mdsumner/ncdf4 for more information.
