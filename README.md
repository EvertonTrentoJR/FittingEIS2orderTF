# FittingEIS2orderTF
A Second-Order Transfer Function Approach for Fitting Electrical Impedance Spectroscopy Data

This is a code for curve-fitting algorithm for electrical impedance spectroscopy (EIS) based on second-order transfer function modeling. 
The objective is to represent the frequency-dependent behavior of a sample's impedance through a reduced parametric model, capturing both magnitude and phase responses. 
The methodology begins with data acquisition using a Keysight E4980A LCR impedance analyzer, which collects complex impedance spectra over a defined frequency range.
The measured data, consisting of magnitude and phase components, is then used as input for a fitting algorithm that minimizes the error between experimental measurements and the theoretical response of a second-order transfer function.
Optimization is performed using numerical minimization techniques to estimate the transfer function coefficients that best fit the spectral data. This approach aims to simplify the characterization of materials and systems by extracting a compact mathematical model from empirical impedance data. 
Initial validations are conducted using synthetic datasets to assess the robustness, accuracy, and convergence of the proposed fitting method prior to application on experimental measurements.

<img width="256" height="382" alt="image" src="https://github.com/user-attachments/assets/327d36e7-ba06-4a7b-8d92-9bdc0bf369ef" />

This is the final test for the Signals&System discipline of the CPGEI-UTFPR program. 
