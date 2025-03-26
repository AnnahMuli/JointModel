# JointModel
This repository consists of software implementation of the methods presented in the manuscript in R.

Title: "Modelling the effect of Longitudinal Markers on Left-Truncated Time-to-Event Outcomes in Twin Studies"

Authors: Muli, A., Rodríguez-Girondo, M., and Houwing-Duistermaat, J.
Code was written by Muli, A.


The code was written in R with the following software versions:
R version 4.2.1 (2022-06-23)
Platform: x86_64-w64-mingw32/x64 (64-bit)


This folder contains the following files:

1. A collection of documented R scripts that contain all required functions to perform the four methods presented in the manuscript.

    - `LOCF.R`
    A R script with the functions and steps required to apply the Last observation carried forward (LOCF) approach
    
    -  `ORC.R`
    A R script with the functions and steps required to apply the Ordinary Regression Calibration (ORC) approach

    - `RRC.R`
    A R script with the functions and steps required to apply the Risk set Regression Calibration (RRC) approach
    
    - `JM.R`
    A R script with the functions and steps required to apply the two-stage joint modeling (JM) approach

2. An example simulated dataset following the required format to run performed the four methods introduced in 1. 

   The dataset is presented in long format (start stop) and contains the following variables:
    
   - `Start`: age at covariate measurement
   - `Stop` : age at event
   - `status`: non-censoring indicator
   - `A0`: age at entry in the study


