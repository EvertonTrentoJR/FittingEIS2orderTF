# FittingEIS2orderTF
**A Second-Order Transfer Function Approach for Fitting Electrical Impedance Spectroscopy Data**  

This repository contains the final test project for the **Signals & Systems** discipline of the **CPGEI-UTFPR program**.  
The notebook and resources included here demonstrate the concepts covered in the course through practical implementation and experimentation.  

# 0. Table of Contents
1. [Methodology](#methodology)
    1. [Block Diagram](#block_diagram)
2. [Dataset](#dataset)
    1. [Dataset organization](#dataset_organization)
3. [Getting_started](#getting_started)
4. [Dependecies](#dependencies)

# 1. Methodology <a name="methodology"></a>

This is a code for curve-fitting algorithm for electrical impedance spectroscopy (EIS) based on second-order transfer function modeling. 
The objective is to represent the frequency-dependent behavior of a sample's impedance through a reduced parametric model, capturing both magnitude and phase responses. 
The methodology begins with data acquisition using a Keysight E4980A LCR impedance analyzer, which collects complex impedance spectra over a defined frequency range.
The measured data, consisting of magnitude and phase components, is then used as input for a fitting algorithm that minimizes the error between experimental measurements and the theoretical response of a second-order transfer function.
Optimization is performed using numerical minimization techniques to estimate the transfer function coefficients that best fit the spectral data. This approach aims to simplify the characterization of materials and systems by extracting a compact mathematical model from empirical impedance data. 
Initial validations are conducted using synthetic datasets to assess the robustness, accuracy, and convergence of the proposed fitting method prior to application on experimental measurements.

## 1.1. Block Diagram <a name="block_diagram"></a>

<img width="256" height="382" alt="image" src="https://github.com/user-attachments/assets/327d36e7-ba06-4a7b-8d92-9bdc0bf369ef" />

# 2. Dataset <a name="dataset"></a>
The dataset is divided into two major batches of data: **synthetic** and **experimental**.

## 2.1. Dataset Organization <a name="dataset_organization"></a>

- **Synthetic data**: Defines first- or second-order transfer functions and generates the corresponding spectra.  
- **Experimental data**: Collected using an LCR impedance bridge during the process of **ice melting into water**.  


# 3. Getting_started <a name="getting_started"></a>
We provide a Google Colab notebook (.ipynb) to make it easy to get up and running.
- Open the notebook in Google Colab
Click the link to the notebook or upload it to your own Colab environment.
- Copy the code
Review the code cells and copy them into your own working environment if needed.
- Download the data
Follow the instructions in the notebook to download the dataset required for running the project.
- Run the code
Execute the notebook cells in order. Once the data is available, the scripts should run without extra setup.


# 4. Dependecies <a name="dependencies"></a>
The following libraries was apoplied for this work:
```
matplotlib # for data visualization
numpy # for general numerical processing 
scipy # for signal processing algorithms and fitting methods
```
