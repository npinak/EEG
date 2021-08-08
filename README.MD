# General Information

- Code of the EEG analysis projects that I've done. Please take a look. 
- Click on the "Python" or "MATLAB" folder to look at the projects. 
- Projects inspired by: https://mark-kramer.github.io/Case-Studies-Python/intro.html
- Adding more as I complete them!!!

# Python

**The-Power-Spectrum_(Part-1) Folder:**
- Power spectrum data analysis on EEG data (Part 1).
- Includes these steps:
  1. Visual inspection
  2. Mean, variance, and standard deviation
  3. The autocovariance
  4. Power spectral density
  5. Decibel scaling
  6. The spectrogram

**The_Power_Spectrum_(Part_2) Folder:**

- Power spectrum data analysis on EEG data (Part 2). 
- Includes these steps:
  1. Spectral Analysis: The Rectangular Taper and Zero Padding
  2. Beyond the Rectangular Taper — the Hanning Taper
  3. Beyond the Hanning Taper — the Multitaper Method
  4. Confidence Intervals of the Spectrum
	


**The-Event-Related-Potential Folder:**

- ERP analysis using python
- Contains: 
	1. Background
	2. Data Analysis 
	3. Plotting the ERP 
	4. Confidence Intervals (Central Limit Theorem)
	5. Confidence Intervals (Bootstrapping)

**Analysis-of-Coupled-Rhythms Folder:**
- Analysis to see if 2 ECoG electrode recordings were coupled. 

- Still a work in progress.

# MATLAB

**EEG Signal-Simulation Folder:**
- Used MATLAB to simulate time series data.
  - Created white noise, pink noise (1/f), ongoing stationary/non-stationary sinewaves, transient oscillations with a Gaussian.
  - The purpose of this project was the simulate “realistic” EEG data so that it can be used to validate data analysis methods. 

**EEG Graphing Folder:**
- Used MATLAB to quantify features of an ERP graph.
  - Quantified the magnitude of a peak in an unfiltered ERP graph in a predefined time window.
  - Quantified the “mean-peak” (-10/+10 ms) magnitude in an unfiltered ERP graph in a predefined time window.
  - Applied a low-pass filter and repeated the previous two tasks.  
- Used MATLAB to generate a topographical map that shows peak time latency for each channel during a predefined time window.

