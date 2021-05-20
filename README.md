# autoDMD
 LabView codes to display images on Texas Instruments DLP7000 DMD
 
 ## Programing the DMD for Automated operation
The DMD we used is TI DLP7000.

|Part Number | Description | Developer |
| --- | --- | --- |
|DLP7000 | The DMD device | Texas Instruments (TI) |
|DLPC410 | The FPGA hardware to run the DMD | Texas Instruments (TI) |
|DLPR210 | The EEPROM hardware to run the DMD | Texas Instruments (TI) |
|DLPA200 | The DMD Driver to run the DMD | Texas Instruments (TI) |
|D4100 | The complete controller board to run the DMD | Digital Light Innovations (DLi) | 
|ALP4 | The software interface (API) to run the controller board | ViALUX | 

This DMD was bought from DLi as a complete set 'D4100 Discovery kit' (DMD + controller board). To run the DLP4100 chipsets we use the ALP4 Application Programing Interface provided by ViAlUX. In addition to a ready to use software application (ALP4.1 controller suite with intuitive GUI), ViALUX also provides a library of functions (also called ALP4) to write your own custom software. This library is provided as a Dynamic Link Library (DLL).

## Contents
This repo contains the source code, and the main VI *ovenCtrl_Na.vi*.
- *../src/* contains the VI and sub VIs.
- *../DMD.lvproj* is the labView project file.
- *../SingleFrame.vi* is the main VI to be run.

## Getting Started
- Clone this repository. 
```git clone https://github.com/sbanik1/autoDMD <lcl_dir>```
- Open *../DMD.lvproj* and run the code *SingleFrame.vi*
