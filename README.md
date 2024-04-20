# Board Simulation Files
These are files that can be loaded into the Ultraino software

- [animations.xml.gz](animations.xml.gz) has an uncalibrated board file with some preset animations. This should be used with board when the FPGA is programmed with the calibration.

- [emptyboard.xml.gz](emptyboard.xml.gz) is the default empty board file given by SonicSurface (<https://github.com/upnalab/SonicSurface/blob/main/Simulations/emptyboard.xml.gz>)

- [calibratedboard.xml.gz](calibratedboard.xml.gz) has the board calibration. Note that this should not be used while the FPGA is programmed with the calibration, only one or the other - the software or the FPGA - should have the calibration.

[calibration.txt](calibration.txt) is the raw text for the board's calibration.
