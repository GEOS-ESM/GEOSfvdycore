# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Fixed

### Added

### Changed

### Removed

### Deprecated

## [1.5.0] - 2022-03-21

- Updates to `components.yaml` to bring inline (or exceed) GEOSgcm v10.22.1

  - ESMA_env v3.10.0 → v3.13.0
  - ESMA_cmake v3.8.0 → v3.12.0
  - GMAO_Shared v1.5.0 → v1.5.3
  - FVdycoreCubed_GridComp v1.5.0 → v1.6.0
  - MAPL v2.14.1 → v2.19.0

- Update CircleCI to use orbs

## [1.4.0] - 2021-12-21

### Changed

- Updates to `components.yaml` to bring inline (or exceed) GEOSgcm v10.20.0

  - ESMA_env v3.4.0 → v3.10.0
  - ESMA_cmake v3.6.2 → v3.8.0
  - GMAO_Shared v1.4.10 → v1.5.0
  - FVdycoreCubed_GridComp v1.2.17 → v1.5.0
  - fvdycore geos/v1.1.7 → geos/v1.3.0
  - MAPL v2.8.6 → v2.14.1

- Update CircleCI to use Intel 2021.3
- Update `CODEOWNERS`

### Fixed

- Fixed CMake to be like GEOSgcm

### Added

- Added EditorConfig support.
- Added changelog enforcer
- Added `CHANGELOG.md`

## [1.3.0] - 2021-10-08

### Changed

* This release moves the GEOSfvdycore repo to be in line with GEOSgcm v10.19.4. Updates include:

  * ESMA_env v3.3.1 → v3.4.0
  * ESMA_cmake v3.5.4 → v3.6.2
  * GMAO_Shared v1.4.6 → v1.4.10
  * FVdycoreCubed_GridComp v1.2.16 → v1.2.17
  * MAPL v2.8.4 → v2.8.6

## [1.2.10] - 2021-08-27

### Changed

* Update components to be in line with GEOSgcm (or newer):

  * ESMA_env v3.3.0 → v3.3.1
  * ESMA_cmake v3.5.2 → v3.5.4
  * GMAO_Shared v1.4.5 → v1.4.6
  * FVdycoreCubed_GridComp v1.2.15 → v1.2.16

## [1.2.9] - 2021-07-19

### Changed

* Update components to be in line with GEOSgcm:

  * ESMA_cmake v3.5.0 → v3.5.2
  * GMAO_Shared v1.4.3 → v1.4.5
  * fvdycore geos/v1.1.6 → geos/v1.1.7

## [1.2.8] - 2021-07-07

### Changed

* Update components to be in line with GEOSgcm v10.19.2:

  * ESMA_env v3.2.1 → v3.3.0
  * ESMA_cmake v3.4.2 → v3.5.0
  * GMAO_Shared v1.4.1 → v1.4.3

## [1.2.7] - 2021-05-25

### Changed

* This updates GEOSfvdycore to be inline with GEOS v10.19.1. Updates include:

  * ESMA_env v3.2.1
  * ESMA_cmake v3.4.2
  * GMAO_Shared v1.4.1
  * MAPL v2.7.0
  * FMS geos/2019.01.02+noaff.7
  * FVdycoreCubed_GridComp v1.2.15


## [1.2.6] - 2021-04-14

### Changed
* Update to `components.yaml` to match GEOSgcm `main` as of 2021-Apr-14:
  * ESMA_env v6.2.0
  * ESMA_cmake v3.3.9
  * GMAO_Shared v1.3.10
  * FVdycoreCubed_GridComp v1.2.12
  * fvdycore geos/v1.1.6

## [1.2.5] - 2021-04-02

### Changed

* Update to use MAPL 2.6.4, FVdycoreCubed_GridComp 1.2.11, and fvdycore v1.1.5

## [1.2.4] - 2021-03-25

### Changed

* This release brings GEOSfvdycore's sub repos in line with GEOSgcm v10.17.4

## [1.2.3] - 2021-03-09

### Changed

* Update `components.yaml` to match GEOSgcm v10.17.3

## [1.2.2] - 2020-12-17

### Changed

* This PR advances many components to match GEOSgcm

## [1.2.1] - 2020-12-02

### Changed

* Updates the `fv3.j` script to allow for GEOS shared object libraries.

## [1.2.0] - 2020-11-30

### Changed

* This release updates the GEOSfvdycore fixture sub-repos to match GEOSgcm v10.17.0:

  * Intel 19.1.3 (ESMA_cmake v3.1.1)
  * MAPL 2.4.0

  and more.


## [1.1.2] - 2020-10-30

### Changed

* Add to `components.yaml` to allow `mepo` to see the fixture.

## [1.1.1] - 2020-10-28

### Changed

* Update `components.yaml` to match GEOSgcm:

  * ESMA_env v3.0.1
  * GMAO_Shared v1.3.2
  * MAPL v2.3.4

## [1.1.0] - 2020-10-06

### Changed

* This version of GEOSfvdycore has equivalent subrepos to GEOSgcm 10.16.0.

### Removed

* Removes support on SLES 11

## [1.0.6] - 2020-09-15

### Changed

* Update subcomponents:
  * GMAO_Shared to v1.1.9
  * FVdycoreCubed_GridComp to v1.2.5

## [1.0.5] - 2020-09-10

### Fixed

* Fix `fv3.j` and `fv3_setup` to correctly handle IOSERVER.

## [1.0.4] - 2020-08-20

### Changed

* Updates to CircleCI

### Fixed

* Fix to `fv3_setup`

## [1.0.3] - 2020-08-20

### Changed

- Update `components.yaml` to:
  - ESMA_cmake v3.1.3
  - GMAO_Shared v1.1.8
  - FMS geos/2019.01.02+noaff.1
  - FVdycoreCubed_GridComp v1.2.2

### Added

- Add a CircleCI test for building fixture

### Removed

- Remove Github Actions build test

## [1.0.2] - 2020-08-11

### Changed

* Move GEOSfvdycore to use [FVdycoreCubed_GridComp v1.2.1](https://github.com/GEOS-ESM/FVdycoreCubed_GridComp/releases/tag/v1.2.1) which is a zero-diff update that affects the `fv3.j` script used to run the FV3 Standalone.

## [1.0.1] - 2020-08-04

### Changed

* Updates to bring GEOSfvdycore in line with GEOSgcm

## [1.0.0] - 2020-07-22

### Added

* This is the initial release of GEOSfvdycore which allows one to run the GEOS FV3 Standalone.
