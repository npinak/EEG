# General Information

- Code of the EEG analysis projects that I've done. Please take a look. 
- Click on the "Python" or "MATLAB" folder to look at the projects. 

# Python

**The-Power-Spectrum_(Part-1) Folder:**
- Power spectrum data analysis on EEG data.
- Includes these steps:
  1. Visual inspection
  2. Mean, variance, and standard deviation
  3. The autocovariance
  4. Power spectral density
  5. Decibel scaling
  6. The spectrogram

**The_Power_Spectrum_(Part_2) Folder:**
 - I am still working on this analysis.

**The-Event-Related-Potential Folder:**

- ERP analysis using python
- Contains: Background, Data Analysis, Plotting the ERP, Confidence Intervals (Central Limit Theorem), Confidence Intervals (Bootstrapping)


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

