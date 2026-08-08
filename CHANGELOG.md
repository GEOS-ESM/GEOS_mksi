# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

15July2025:
- ATMS channels 1-4 and 16 are turned on when all-sky approach is used for ATMS.

### Added
-09Mar2026: End use of MODIS on Jan 31, 2026; start using VIIRS beyond that.

15Jan2026
- added location of VIIRS NOAA-20 files

27Jan2026
- adjust for AIRS outage in FPP

15Jan2026
- added location of VIIRS NOAA-20 files

09Jan2026:
- sync with actually running FPP (OPS handled)

08Jan2026:
- update location of LLK AERONET files 

15Jul2025:
- add class-location of hi-res RAOB

01July2025:
- Turn off SSMIS F17 July 25

30May2025:
- found that swell cannot handle redundancy in data/time in the database - fix that.
- also found a bug in the start date for Metop-C AVHRR3

22May2025:
- chn 4-6 of AMSUA MetopC should have been turned off after a given date.

- it was also found out on May 22 that EMC is no longer delivering the version of bufr 
  OMI being used in FP; so changes here move the pointer to OMIEFF being used in 
  GEOS-IT (this is a real time version of the data).

21May2025:

- turn chn 15 of ATMS NPP back on

16May2025:

- Revise OMPS-LP for FPP/FP settings

----------

- add Metop-C AVHRR3 from late Jan 2025 onward

### Changed

- add GOES-19 AMVs (subtype 273)
- add transition dates for recent GOES AMVs
- add CrIS-N21 info
- updated CrIS-NPP obs errors
- fix for 272 satwind state hour
- move obs-class rc files to a db inside this
  (notice that handling scripts are still kept 
  in @GMAO_Shared/GMAO_etc
- update with recent satellite outages
- bias correct from 20230101-00z: n18,n19,n20,n21,npp,metop-b/c
- fix bad merge Oct 2024

- Revise sources of OMPS-LP observations (NPP and N21)

### Fixed

- remove redundant MetOp gps entries in convinfo DB active files
### Removed

### Deprecated

