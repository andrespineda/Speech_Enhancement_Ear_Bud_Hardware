# Changelog

## [Unreleased]

### Fixed

-   Corrected PDM GPIO50/51 lines that were inverted in V2

### Added

-   Added a MM8030-261RJ3 RF Probe connector to be able to test and tune antenna matching circuit.
-   Added Apollo4 60 Ohm matching circuit.
-   Added IOM1_SCL/SDA lines to initialize and control SSM6515 DAC.

### Changed

-   Replaced DAC with SSM6515BCBZRL7, which is smaller and more efficient
-   Replaced dual LDO with single voltage 1V8:  TLV70718PDQNR.
-   Moved 6pF tuning caps to underside of board and left them as DNP. Only needed for tuning.

### Removed

-   Deletions
