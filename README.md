# EneCalibration
Energy calibration tool for beam diagnosis

This is the ROOT application for beam diagnosis.  Taking data from CAEN digitizer (PHA firmware) or ROOT file.  Fitting peaks and calculation ch -> energy conversion factor.  
The energy spectum is fitted with Gaussian.  The results are outputed into text file and uploaded to data base (MongoDB).  

Required libraries
* ROOT
* CAEN
* MongoDB (optional?)
