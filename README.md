# E2EL datasets
Here is documentation of free and openly accessible modeling and validation datasets that are relevant to the E2EL effort. This list is not expected to be comprehensive.

## Cloud model data with electrification and lightning

| Name | Location | Grid spacing | Reference | Data archive |
| ---- | -------- | ------------ | --------- | ------------ |
| KTaL simulations | West Texas | 125 m | [Brothers et al. (2018, JAS)](https://doi.org/10.1175/JAS-D-18-0007.1) | https://doi.org/10.5281/zenodo.17915983 |

## Field Campaigns

| Name | Data Archive | Location/Year | LMA | ☇ Other Radio | ☇ Satellite | Radar(s) | In Situ | Aircraft | Other |
| ---- | ------------ | ------------- | --- | ------------- | ----------- | -------- | ------- | -------- | ----- | 
| [STEPS](https://www.eol.ucar.edu/field_projects/steps) | [NCAR EOL](https://data.eol.ucar.edu/dataset/list?project=179&children=project) | Colorado, Kansas; 2000 | X | | | CHILL, SPOL (both S-band) | EFM balloons, aircraft | T-28 | Environmental Soundings| 
| [DC3](https://www.eol.ucar.edu/field_projects/dc3) | [NCAR EOL](http://data.eol.ucar.edu/master_list/?project=DC3) | Colorado, Oklahoma, Texas, Alabama; 2012 | X | | | Yes, mobile | EFM balloons in Oklahoma | NASA DC-8, NCAR HIAPER G-V |  |
| [HyMeX](https://mistrals.sedoo.fr/catalogue/?checkBoxCriteria=%7B%22projects%22%3A%5B%22HyMeX.HyMeX%22%5D%7D) | [MISTRALS](https://doi.org/10.6096/MISTRALS-HYMEX.LIGHTNING.LMA) | Mediterranean, 2012 | X | | | X | | Falcon | Environmental Soundings |
| [GOES-R PLT](https://www.earthdata.nasa.gov/data/projects/goes-r-plt/collection) | [NASA Earthdata](http://dx.doi.org/10.5067/GOESRPLT/DATA101) | Colorado, Alabama, Oklahoma, Texas, Ontario; 2017 | X | X | X | Airborne and Ground | | NASA ER-2 | Optical, Electric Field, Field Change, Gamma Ray |
| [RELAMPAGO](https://www.eol.ucar.edu/field_projects/relampago) | [NCAR EOL](https://data.eol.ucar.edu/master_lists/generated/relampago/) | Argentina, 2018-2019 | X | LF | X | X | Microphysics | ARM G-1 | Environmental Soundings, Electric Field, Field Change |
| [IMPACTS](https://www.earthdata.nasa.gov/data/projects/impacts/collection) | [NASA Earthdata](http://dx.doi.org/10.5067/IMPACTS/DATA101) | Central & Eastern USA, 2020-2023 | | | X | Airborne and Ground | Microphysics | NASA ER-2 & P-3 | Electric Field |
| [TRACER / ESCAPE](https://armgov.svcs.arm.gov/research/campaigns/amf2021tracer) | [NCAR EOL](https://data.eol.ucar.edu/master_lists/generated/escape/) | Texas, 2021-2022 | X | | X | X | Microphysics | Convair, LearJet, G-V | Environmental Soundings |
| [Project LEE](https://www.eol.ucar.edu/field_projects/lee) | [NCAR EOL](https://data.eol.ucar.edu/master_lists/generated/lee/) | Lake Ontario, 2022-2023 | X | | X | X | Electric Field | | Environmental Soundings | 
| [PERiLS](https://www.nssl.noaa.gov/projects/perils/) | [NCAR EOL](https://data.eol.ucar.edu/master_lists/generated/perils_2022/) | Southeast USA, 2023 | X | | X | X | X | | Environmental Soundings, Profilers, Surface Networks|
| [ALOFT](https://www.earthdata.nasa.gov/data/projects/aloft/collection) | [NASA Earthdata](https://dx.doi.org/10.5067/ALOFT/DATA101) | Mexico, Central America, Florida; 2023 | X | LF, VLF | X | EXRAD, CRS | | NASA ER-2 | Optical, Electric Field, Field Change, Gamma Ray, Passive Microwave |
| [Misc NASA Campaigns](https://lightning.nsstc.nasa.gov/lightning-campaigns.html) | [NASA Earthdata](https://search.earthdata.nasa.gov/search?q=lightning) | Various, 1990-Present | X | X | X | X | X | X | Electric Field, etc. |
| [Misc NSF Campaigns](https://data.eol.ucar.edu/dataset/) | [NCAR EOL](https://data.eol.ucar.edu/dataset/list?gcmdScienceKeyword=376&children=gcmdScienceKeyword) | Various, 1990-Present | X | X | X | X | X | X | Electric Field, etc. |

## Long-Duration Deployments

| Name | Data Archive | Location | Sensor(s) | Time Frame |
| ---- | ------------ | -------- | --------- | -------- |
| North Alabama LMA | [NASA Earthdata](https://dx.doi.org/10.5067/NALMA/DATA101)| North Alabama | Lightning Mapping Array | 2001-Present |
| Washington, DC LMA | [NASA Earthdata](https://dx.doi.org/10.5067/DCLMA/DATA101) | Washington, DC | Lightning Mapping Array | 2020-Present |
| Wallops LMA | [NASA Earthdata](https://dx.doi.org/10.5067/WFFLMA/DATA101) | NASA Wallops, VA | Lightning Mapping Array | 2020-Present |
| WALDO Database | [WALDO](https://waldo.world/) | Various (Global) | LF, VLF, ELF | 1982, 1987, 2000-Present |
| WWLLN Thunder Hour Climatology | [NASA Earthdata](https://dx.doi.org/10.5067/WWLLN/DATA101) | Global | VLF | 2013-Present |

## Satellite Datasets

| Name | Data Archive | Orbit | Sensor Type | Resolution | Time Frame |
| ---- | ------------ | ----- | ----------- | ---------- | ---------- |
| OTD Level 2 | [NASA Earthdata](https://dx.doi.org/10.5067/LIS/OTD/DATA101) | LEO | Optical (777 nm) | 2 ms, 8 km | 1995-2000 |
| TRMM LIS Level 2 | [NASA Earthdata](https://dx.doi.org/10.5067/LIS/LIS/DATA501) | LEO | Optical (777 nm) | 2 ms, 4 km | 1998-2015 |
| ISS LIS Level 2 | [NASA Earthdata](https://dx.doi.org/10.5067/LIS/ISSLIS/DATA114) | LEO | Optical (777 nm) | 2 ms, 4 km | 2017-2023 |
| LIS-OTD Flash Climatology | [NASA Earthdata](https://dx.doi.org//10.5067/LIS/LISCLIMO/DATA101) | LEO | Optical (777 nm) | Monthly, 0.1° | 1995-2015, 2017-2023 |
| LIS Thunder Hour Climatology | [NASA Earthdata](https://dx.doi.org/10.5067/COMBLIS/ATH/DATA101) | LEO | Optical (777 nm) | Annual, 0.05° | 1998-2015, 2017-2023 |
| ISUAL | [NASA CDAWeb](https://cdaweb.gsfc.nasa.gov/pub/data/formosat-rocsat/formosat-2/isual/) | LEO | Imager (623-750 nm), Spectrometer (220, 318, 337, 391, 687, 779 nm) | 0.1-30 ms, 0.04° | 2004-2016 |
| ASIM | [DTU](https://asdc.space.dtu.dk/) | LEO | Optical (180-230, 337, 777 nm), Gamma Ray (15 keV-400 MeV) | 12 fps (imager), 100 kHz (photometer) | 2018-Present |
| GLM Level 2 | [NOAA CLASS](https://www.aev.class.noaa.gov/) | GEO | Optical (777 nm) | 2 ms, 8 km | 2017-Present |
| GLM Level 3 Gridded | [NASA Earthdata](https://dx.doi.org/10.5067/GLM/GRID/DATA101) | GEO | Optical (777 nm) | 1 min, 2 km | 2017-Present |
| GLM Thunder Hour Climatology | [NASA Earthdata](https://dx.doi.org/10.5067/GLM/DATA301) | GEO | Optical (777 nm) | Monthly, 0.05° | 2019-Present |
| MTG-LI | [EUMETSAT](https://user.eumetsat.int/catalogue) | GEO | Optical (777 nm) | 1 ms, 4.5 km | 2023-Present |



