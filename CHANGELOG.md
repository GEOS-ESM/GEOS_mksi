# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

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

