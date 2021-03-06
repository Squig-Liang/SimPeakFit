# SimPeakFit

A short and simple code for fitting Gaussian, Lorentzians or Voigts to spectroscopy data. The code is based on [**Non-Linear Least-Squares Minimization and Curve-Fitting for Python.**](https://lmfit.github.io/lmfit-py/ "LMFIT webpage")

<img src="https://github.com/Squig-Liang/SimPeakFit/blob/master/sample.png" alt="An Example Fit" width="600"/>

Essential Requirements: **lmfit**. 
>pip install lmfit

Input data layout(for the case of Raman spectroscopy) have wavenumbers as column headers and a single row corresponding to one spectrum.

**Current build** includes:
- Polynomial Baseline Subtraction
- Multiple Peak Fits
- Plotting of Fitted Envelope and Individual Components

The notebook file runs the fitting code and the .csv file is a test dataset based on Raman spectroscopy.

Recent update
28 August 2020: Added progress bar during curve fitting process.
