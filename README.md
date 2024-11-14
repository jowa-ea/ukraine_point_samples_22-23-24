## ukraine_point_samples_22-23-24

This repository contains publicly available annotated sample points for seasons 2022, 2023 and 2024.

# Metadata
Each shapefiles contains annotated points for seasons 2022, 2023 and 2024 and has 10 attributes:

**lat** (float) latitude of the point \n
**lon** (float) longitude of the point \n
**Occupation** (int) Whether a points falls within government controlled territories (0) or temporarily occupied territoiries (1)
**Occ_str** (str) Whether a points falls within government controlled territories (gov_cont) or temporarily occupied territoiries (temp_occ)
**Occ_date** (str) Date of the occupation line used, source: https://www.understandingwar.org/
**Stratum** (int) Map stratum value of the point
**Stratum_st** (str) Full text stratum value (ex. stratum 3 corresponds to Rapeseed)
**Class** (int) Annotated value of the point
**Class_st** (str) Full text class value (ex. class 3 corresponds to Rapeseed)
**Year** (int) Year of mapping and annotation
