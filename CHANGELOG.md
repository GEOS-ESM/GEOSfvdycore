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

## [3.0.0] - 202X-XX-XX

### Changed

- Update components to match GEOSgcm v12

## [2.27.0] - 2025-09-26

### Changed

- Update to `components.yaml` to match or exceed GEOSgcm `main` as of 2025-09-19
  - ESMA_env v5.13.0 → v5.14.0
  - ESMA_cmake v3.64.0 → v3.65.0
  - GEOS_Util v2.1.10 → v2.1.11
  - MAPL v2.59.0 → v2.61.0
  - FVdycoreCubed_GridComp v2.14.1 → v2.15.0

## [2.26.0] - 2025-09-19

### Changed

- Update to `components.yaml` to match or exceed GEOSgcm `main` as of 2025-09-19
  - MAPL v2.59.0 → v2.59.1
- Update CI to use Baselibs 8.19.0

## [2.25.0] - 2025-09-10

### Changed

- Update to `components.yaml` to match or exceed GEOSgcm `main` as of 2025-07-05
  - ESMA_env v4.38.0 → v5.13.0
  - ESMA_cmake v3.62.1 → v3.64.0
  - GMAO_Shared v2.1.3 → v2.1.4
  - GEOS_Util v2.1.9 → v2.1.10
  - MAPL v2.57.0 → v2.59.0
- Update CI to use Baselibs 8.18.0

## [2.24.0] - 2025-07-07

### Changed

- Update to `components.yaml` to match or exceed GEOSgcm `main` as of 2025-07-05
  - ESMA_cmake v3.62.0 → v3.62.1
  - GMAO_Shared v2.1.1 → v2.1.3
  - GEOS_Util v2.1.7 → v2.1.9
  - MAPL v2.55.0 → v2.57.0
  - FVdycoreCubed_GridComp v2.14.0 → v2.14.1

## [2.23.0] - 2025-05-13

### Added

- Added new `BUILD_INFO.rc` file

### Changed

- Update to `components.yaml` to fix f2py issues
  - ESMA_env v4.37.0 → v4.38.0
  - ESMA_cmake v3.61.0 → v3.62.0
  - GMAO_Shared v2.1.0 → v2.1.1

## [2.22.0] - 2025-05-12

### Added

- Add Spack GCC CI build
- Add Github CI build

### Changed

- Update to `components.yaml` to match or exceed GEOSgcm `main` as of 2025-05-12
  - ESMA_env v4.34.1 → v4.37.0
  - ESMA_cmake v3.56.0 → v3.61.0
  - GMAO_Shared v1.9.9 → v2.1.0
  - GEOS_Util v2.1.6 → v2.1.7
  - GMAO_perllib v1.1.0 (added)
  - MAPL v2.52.0 → v2.55.0
  - FVdycoreCubed_GridComp v2.13.0 → v2.14.0

## [2.21.0] - 2025-01-28

### Changed

- Update to `components.yaml` to match or exceed GEOSgcm `main` as of 2025-01-28
  - ESMA_env v4.34.0 → v4.34.1
  - GEOS_Util v2.1.3 → v2.1.6
  - MAPL v2.51.2 → v2.52.0
- Various minor fixes to CMake and CircleCI

## [2.20.0] - 2025-01-16

### Changed

- Update to `components.yaml` to match or exceed GEOSgcm `main` as of 2025-01-16
  - ESMA_env v4.29.1 → v4.34.0
  - ESMA_cmake v3.55.0 → v3.56.0
  - MAPL v2.51.1 → v2.51.2
  - FVdycoreCubed_GridComp v2.12.0 → v2.13.0

## [2.19.1] - 2024-12-18

### Changed

- Update minimum CMake version to 3.24 (needed for f2py/meson support)

## [2.19.0] - 2024-12-18

### Changed

- Update to `components.yaml` to match or exceed GEOSgcm `main` as of 2024-12-18
  - ESMA_env v4.29.0 → v4.29.1
  - ESMA_cmake v3.51.0 → v3.55.0
  - ecbuild geos/v1.2.0 → geos/v1.3.0
  - MAPL v2.48.0 → v2.51.1
  - GMAO_Shared v1.9.8 → v1.9.9
  - GEOS_Util v2.1.2 → v2.1.3
  - fvdycore geos/v2.9.0 → geos/v2.9.1

## [2.18.0] - 2024-09-30

### Changed

- Update to `components.yaml` to match or exceed GEOSgcm `main` as of 2024-09-30
  - MAPL v2.47.1 → v2.48.0

## [2.17.0] - 2024-09-25

### Changed

- Update to `components.yaml` to match or exceed GEOSgcm `main` as of 2024-09-25
  - ESMA_cmake v3.48.0 → v3.51.0
  - FVdycoreCubed_GridComp v2.11.1 → v2.12.0
- Update CircleCI to use v4 orb

## [2.16.0] - 2024-08-12

### Changed

- Update to `components.yaml` to match or exceed GEOSgcm `main` as of 2024-08-12
  - ESMA_cmake v3.45.1 → v3.48.0
  - GMAO_Shared v1.9.7 → v1.9.8
  - GEOS_Util v2.0.8 → v2.1.2
  - MAPL v2.46.0 → v2.47.1
  - FMS geos/2019.01.02+noaff.8 → geos/2019.01.02+noaff.10
  - fvdycore geos/v2.8.2 → geos/v2.9.0

## [2.15.0] - 2024-05-03

### Changed

- Update to `components.yaml` to match or exceed GEOSgcm `main` as of 2024-04-29
  - ESMA_env v4.25.1 → v4.29.0
    - Update to Baselibs 7.24.0
  - ESMA_cmake v3.41.0 → v3.45.1
    - Add quiet flag to NAG
    - Limit tests to ESSENTIAL
    - Set BUILT_ON_SLES15 to FALSE if not
    - Change to FindESMF.cmake and other updates
  - GEOS_Util v2.0.5 → v2.0.8
    - Various plots and remap updates
  - MAPL v2.44.0 → v2.46.0
    - Many, many, many changes (see https://github.com/GEOS-ESM/MAPL/compare/v2.44.0...v2.45.0)
    - Support for spack build
  - FVdycoreCubed_GridComp v2.11.0 → v2.11.1
    - Fix variable use before set
  - fvdycore geos/v2.8.1 → geos/v2.8.2
    - Fix uninitialized variables

## [2.14.0] - 2024-02-21

### Changed

- Update to `components.yaml` to match GEOSgcm `main` as of 2024-02-21
  - ESMA_cmake v3.38.0 → v3.41.0
    - Use `ESMF::ESMF` as the target for ESMF
    - Update `FindESMF.cmake`
    - Add `DetermineMPIStack.cmake` to detect MPI stack at CMake time
  - MAPL v2.43.0 → v2.44.0
    - Various improvements to History "Samplers" that sample model data at geolocations of simulated instruments. These include support for both trajectories (time dependent lat/lon) and swaths (time-dependent scans)
    - Added memory utility, MAPL_MemReport that can be used in any code linking MAPL
    - Added capability in the MAPL ESMF regridding wrapper to apply a destination mask if the destination grid contains a mask
    - Updates for using MAPL with GEOS in a hybrid MPI+OpenMP paradigm
    - Various fixes for NVHPC work
    - This version of MAPL now **_requires_** ESMF 8.6.0 as MAPL now uses functionality only supported in that version. Moreover, all references to ESMF as a CMake target are now done as `ESMF::ESMF`. This is supported in Baselibs build with ESMA_cmake v3.40.0 (**_required_** for Baselibs builds) and for non-Baselibs builds (i.e., spack) via a newer `FindESMF.cmake` file (currently from ESMF `develop` and will be in ESMF 8.6.1+).
  = GMAO_Shared v1.9.6 → v1.9.7
    - Updates for WMMA
  - FVdycoreCubed_GridComp v2.10.0 → v2.11.0
    - Updates to `fv3_setup` to use CMake detection of MPI stack (requires ESMA_cmake v3.41.0)
- Pulled over other CMake changes from GEOSgcm (mainly developer related)

## [2.13.0] - 2024-01-26

### Changed

- Update to `components.yaml` to match GEOSgcm `main` as of 2024-01-26
  - ESMA_env v4.24.0 → v4.25.1
    - Update to Baselibs 7.17.1, fix xgboost build
    - Moves to use gcc 11 as the Intel backing C compiler
  - ESMA_cmake v3.36.0 → v3.38.0
    - Fixes for ifx and NAG
    - Add Hygon support, add FindESMF.cmake
  - MAPL v2.42.4 → v2.43.0
    - Updates for ongoing work with trajectory and station sampling
    - Examples on how to use the Automatic Code Generator
    - Fixes for use of the MAPL Python code with Python 3
    - Fixes for GCC 13 which is still NOT SUPPORTED but this allows for further testing
    - Fix to allow ExtData2G to be built as static library
  - FVdycoreCubed_GridComp v2.9.0 → v2.10.0
    - Updates for NWP and HWT Runs (non-zero-diff)

## [2.12.0] - 2023-12-19

### Changed

- Update to `components.yaml` to match GEOSgcm `main` as of 2023-12-19
  - ESMA_env v4.22.0 → v4.24.0
    - Update to Baselibs 7.17.0
  - GEOS_Util v2.0.4 → v2.0.5
    - Fix in remap_restarts.py for regridding from MERRA2 at non-72 level resolutions
  - MAPL v2.42.0 → v2.42.4
    - Various minor fixes found by NAG compiler
  - fvdycore geos/v2.8.0 → geos/v2.8.1
    - Fix when running with stretched grid

## [2.11.0] - 2023-12-01

### Changed

- Update to `components.yaml` to match GEOSgcm v11.4.0
  - ESMA_env v4.20.6 → v4.22.0
    - Update to Baselibs 7.15.1
  - GEOS_Util v2.0.3 → v2.0.4
    - Update to remap_restarts.py, cleanup
  - fvdycore geos/v2.7.0 → geos/v2.8.0
    - Fix for C180+ layout reproducibility
- Updated CI to use circleci-tools v2 orb

## [2.10.0] - 2023-11-09

### Changed

- Update to `components.yaml` to match (or exceed) GEOSgcm `main` as of 2023-11-09
  - ESMA_env v4.20.4 → v4.20.6
    - More fixes for build.csh
  - ESMA_cmake v3.35.0 → v3.36.0
    - Fixes for Intel icx and on macOS Rosetta
  - GMAO_Shared v1.9.5 → v1.9.6
    - Fixes for regrid.pl on SLES15
  - MAPL v2.41.1 → v2.42.0
    - Various workarounds for building MAPL with MPICH
    - Added a new benchmark to simulate writing a cubed-sphere file using various tunable strategies
    - Introduced workaround for Intel 2021.10 bug in generic layer.
    - Updated write_by_oserver logic so that the decision to write by the oserver is based on whether the output server client is passed in
    - Fixed incorrect History print during runtime
  - fvdycore geos/v2.6.0 → geos/v2.7.0
    - Add new algorithm for computing coordinates (disabled by default)
  - FVdycoreCubed_GridComp v2.8.0 → v2.9.0
    - Add namelist entry for new algorithm for computing coordinates (disabled by default)

## [2.9.0] - 2023-10-25

### Changed

- Update to `components.yaml` for SLES15 support at NCCS (matches or exceeds GEOSgcm v11.3.1)
  - ESMA_env v4.19.0 → v4.20.4
    - Updates for SCU17 Support at NCCS
  - ESMA_cmake v3.34.0 → v3.35.0
    - Updates for SCU17 Support at NCCS
  - GMAO_Shared v1.9.4 → v1.9.5
    - Updates for SCU17 Support at NCCS
  - MAPL v2.41.0 → v2.41.1
    - Fix missing status check
  - FVdycoreCubed_GridComp v2.7.0 → v2.8.0
    - Updates for SCU17 Support at NCCS

## [2.8.0] - 2023-10-03

### Changed

- Update to `components.yaml` (matches or exceeds GEOSgcm v11.3.0)
  - ESMA_cmake v3.31.1 → v3.34.0
    - Support for GEOS under Rosetta2
    - Updates for NAG
  - GMAO_Shared v1.9.1 → v1.9.4
    - CI updates
    - Updates for util progs
    - Add PlanetIQ
  - GEOS_Util v2.0.2 → v2.0.3
    - Plot updates
  - MAPL v2.40.3 → v2.41.0
    - Updates for ongoing trajectory sampling work
    - Updates and improvements to documentation
    - Changes to `MAPL_Resource.F90` to allow NVIDIA compilers to build this file
    - Adding a new benchmark suite
    - Cleaning up much of the code to reduce compiler warnings and remarks at compile time:
      - Converted all uses of `mpif.h` to `use mpi`
      - Converted all uses of `character*` to `character(len=)`
      - Removed many unused variables
      - Added many `_UNUSED_DUMMY()` calls
      - Converted statement functions to internal functions
  - FVdycoreCubed_GridComp v2.6.0 → v2.7.0
    - Updates from HWT Experiments (zero-diff)
  - fvdycore geos/v2.4.1 → geos/v2.6.0
    - Updates from HWT Experiments (zero-diff)
    - Update to mapz (non-zero-diff)

## [2.7.0] - 2023-08-10

### Changed

- Update to `components.yaml` (matches or exceeds GEOSgcm v11.1.1)
  - ESMA_env v4.17.0 → v4.19.0
    - Update to Baselibs 7.14.0
      - ESMF 8.5.0
      - GFE v1.11.0
  - ESMA_cmake v3.29.0 → v3.31.1
    - Add `QUIET_DEBUG` option
    - Suppress some common Intel warnings
    - Fixes for NAG
  - GEOS_Util v2.0.0 → v2.0.2
    - Plot updates
    - Fixes for remapping catchment restarts
  - MAPL v2.39.3 → v2.40.3
    - Update to use ESMF Hconfig (which means ESMF 8.5.0 is *required*; this is from ESMA_env v4.19.0)
    - Update required GFE library versions
      - gFTL 1.10.0
      - gFTL-shared 1.6.1
      - fArgParse 1.5.0 (if -DBUILD_WITH_FARGPARSE=YES, default=YES)
      - pFlogger 1.9.5 (if -DBUILD_WITH_PFLOGGER=YES, default=YES)
    - `ExtDataDriver.x` can now handle tile grids
    - Various bug fixes for NAG
  - FVdycoreCubed_GridComp v2.5.0 → v2.6.0
    - More cleanup for Singularity use
- Update CircleCI

## [2.6.0] - 2023-06-16

### Changed

- Update to `components.yaml`
  - FVdycoreCubed_GridComp v2.4.4 → v2.5.0
    - Changes to make singularity runs simpler
    - Clean up use of global memory in interp_restarts.x
    - Separate init and finalize in geos-gtfv3
  - MAPL v2.39.1 → v2.39.3
    - Minor fixes

## [2.5.0] - 2023-06-08

### Changed

- Update to `components.yaml`
  - ESMA_env v4.9.3 → v4.17.0 (Baselibs 7.13.0)
  - GMAO_Shared v1.9.0 → v1.9.1 (match GEOSgcm)
- Update CI to Baselibs 7.13.0

## [2.4.3] - 2023-06-08

### Fixed

- Update fvdycore geos/v2.4.0 → geos/v2.4.1
  - Fixes bug with adiabatic/FV3 Standalone runs
- Update FVdycoreCubed_GridComp v2.4.3 → v2.4.4
  - Removes `FV3_CONFIG: MONOTONIC` from `fv3.j` as that is not needed with the fix from fvdycore geos/v2.4.1

## [2.4.2] - 2023-06-05

### Changed

- Update FVdycoreCubed_GridComp v2.4.2 → v2.4.3
  - Adds a new `--site` flag to `fv3_setup` for use with containers

## [2.4.1] - 2023-06-02

### Fixed

- Update FVdycoreCubed_GridComp v2.4.1 → v2.4.2
  - This fixes stability issues (see #79)

## [2.4.0] - 2023-06-01

### Changed

- Update to `components.yaml` to match GEOSgcm v11.0.3
  - ESMA_env v4.9.1 → v4.9.3
  - ESMA_cmake v3.28.0 → v3.29.0
  - MAPL v2.38.1 → v2.39.1
  - FVdycoreCubed_GridComp v2.3.0 → v2.4.1
  - GEOS_Util v1.1.1 → v2.0.0
  - NOTE: FVdycoreCubed_GridComp is v2.4.0 with the GCM, but v2.4.1 has fixes for the FV3 standalone

## [2.3.0] - 2023-05-10

### Changed

- Update to `components.yaml`
  - MAPL v2.37.0 → v2.38.1
  - FVdycoreCubed_GridComp v2.2.2 → v2.3.0
  - fvdycore geos/v2.3.0 → geos/v2.4.0
  - GMAO_Shared v1.8.0 → v1.9.0
- Update CI to test both R4 and R8 FV precision

## [2.2.0] - 2023-04-03

### Changed

- Update to `components.yaml`
  - MAPL v2.36.0 → v2.37.0
  - FVdycoreCubed_GridComp v2.2.0 → v2.2.2
  - fvdycore geos/v2.2.0 → geos/v2.3.0

## [2.1.0] - 2023-03-29

### Changed

- Update to `components.yaml`
  - MAPL v2.35.3 → v2.36.0
  - FVdycoreCubed_GridComp v2.1.0 → v2.2.0
  - fvdycore geos/v2.1.0 → geos/v2.2.0

## [2.0.0] - 2023-03-23

### Changed

- Update to `components.yaml`
  - ESMA_env v4.8.0 → v4.9.1
  - ESMA_cmake v3.24.0 → v3.28.0
  - GMAO_Shared v1.7.0 → v1.8.0
  - MAPL v2.34.1 → v2.35.3
  - FVdycoreCubed_GridComp v1.12.1 → v2.1.0
  - fvdycore geos/v1.5.0 → geos/v2.1.0

### Added

- Added GEOS_Util v1.1.0 to `components.yaml`

## [1.14.0] - 2023-02-09

### Changed

- Update to `components.yaml`
  - ESMA_cmake v3.21.0 → v3.24.0
  - GMAO_Shared v1.6.3 → v1.7.0
  - MAPL v2.33.0 → v2.34.1
- Update GitHub Actions
  - Add action to create PRs to MAPL3 branch on push to main

## [1.13.0] - 2022-12-20

### Changed

- Update to `components.yaml`

  - ESMA_env v4.4.0 → v4.8.0 (Baselibs 7.7.0)
  - ESMA_cmake v3.18.0 → v3.21.0
  - ecbuild geos/v1.2.0 → geos/v1.3.0
  - GMAO_Shared v1.6.1 → v1.6.3
  - MAPL v2.27.1 → v2.33.0

- Moved to use GitHub Actions for label enforcement

- Update Baselibs to 7.7.0 in CI

## [1.12.1] - 2022-10-18

### Fixed

- Fix bad container name in `.circleci/config.yml`

## [1.12.0] - 2022-10-18

### Added

- Added `Dockerfile` and CircleCI workflow to build and push container to both Docker Hub and GitHub Container Registry on
  GEOSfvdycore releases. Uses a GitHub Action to trigger CircleCI pipeline on releases.
- Added Dependabot support

### Changed

- Updated some GitHub Actions versions

## [1.11.0] - 2022-10-11

### Changed

- Update to `components.yaml`

  - GMAO_Shared v1.5.7 → v1.6.1
  - MAPL v2.23.1 → v2.27.1
  - FVdycoreCubed_Gridcomp v1.11.0 → v1.12.1
  - fvdycore geos/v1.4.0 → geos/v1.5.0

## [1.10.0] - 2022-09-01

### Changed

- Update to `components.yaml`

  - ESMA_env v4.3.0 → v4.4.0 (Intel 2022.1)
  - FVdycoreCubed_Gridcomp v1.10.0 → v1.11.0

## [1.9.0] - 2022-08-25

### Changed

- Update to `components.yaml`

  - ESMA_env v4.2.0 → v4.3.0 (Intel 2022.1)
  - ESMA_cmake v3.17.0 → v3.18.0

## [1.8.1] - 2022-08-22

### Fixed

- Fix handling of `FV_PRECISION` in CMake

## [1.8.0] - 2022-08-05

### Changed

- Updates to `components.yaml` to match current GEOSgcm

  - GMAO_Shared v1.5.5 → v1.5.7
  - MAPL v2.23.0 → v2.23.1

- Update FVdycoreCubed_Gridcomp to v1.10.0 for AWS fixes

## [1.7.0] - 2022-07-14

### Changed

- Updates to `components.yaml` to use Baselibs 7.5.0

  - ESMA_env v3.15.0 → v4.2.0
  - MAPL v2.21.3 → v2.23.0
  - FVdycoreCubed_GridComp v1.8.0 → v1.9.0

## [1.6.0] - 2022-06-21

### Changed

- Updates to `components.yaml` to bring inline (or exceed) GEOSgcm v10.22.3

  - ESMA_env v3.13.0 → v3.15.0
  - ESMA_cmake v3.12.0 → v3.17.0
  - GMAO_Shared v1.5.3 → v1.5.5
  - MAPL v2.19.0 → v2.21.3
  - FVdycoreCubed_GridComp v1.6.0 → v1.8.0
  - fvdycore geos/v1.3.0 → geos/v1.4.0

- Update CircleCI to use orb v1
- Turn on FV3 runs in CI

## [1.5.0] - 2022-03-21

### Changed

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
