# SimPeakFit

A short and simple code for fitting Gaussian, Lorentzians or Voigts to spectroscopy data. The code is based on [**Non-Linear Least-Squares Minimization and Curve-Fitting for Python.**](https://lmfit.github.io/lmfit-py/ "LMFIT webpage")

Basic requirements: **lmfit**. Install: >pip install lmfit

Input data layout(for the case of Raman spectroscopy) have wavenumbers as column headers and a single row corresponding to one spectrum.

**Current build** includes:
- Polynomial Baseline Subtraction
- Multiple Peak Fits
- Plotting of Fitted Envelope and Individual Components
