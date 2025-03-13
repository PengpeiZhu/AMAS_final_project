# AMAS_final_project

### This is the final project for Advanced Method in Applied Statistics 2025.


![image](https://github.com/user-attachments/assets/19e45433-2720-4b0e-84cb-ae185fbf9f09)

## Description: 

#### This project aims to generate fake spectral emission line data consisting of 4 components, and fit the data with six different competing models, from simple to more complex models. We compute the fitting's AICc, BIC and DIC values, compare and discuss which information criteria are the best in different scenarios and why.

## Outline:

### 1. Data Generation (Jiazhe)

#### Generate 3 sets of data: 
##### 1. Base data with 4 Gaussian components, evenly separated (i.e., fix position), leave the amplitude and width of the Gaussian free. Also add Gaussian noise and uniform noise.
##### 2. Base data + more noise.
##### 3. Base data + replacing some of the Gaussian with Trapezoid distribution. This data should be the one that does not have a corresponding "true" model from the model pool.
#### NOTE: We save the exact parameters for the gaussian functions used to generate the data. The data are generated with fixed position, but we leave the amplitude and width free within a range. The data also provide a central wavelength of the line.

### 2. Model Fitting (Yifei)

#### Fit the 3 sets of data each with 6 different models. Each model should consist of an N number that is evenly distributed (from the central wavelength, we use the same setup as the data) Gaussians, from 1 Gaussian to 6 Gaussians. 
#### We fit each model using the least square method, with fix position and free amplitude and width (within the ranges as defined by the data) and compute the AICc, BIC and DIC values. 

### 3. Comparing (Pengpei)

#### We compare the contribution of AICc, BIC, and DIC values, discuss which of the criteria work the best to select the best model in the three scenarios. 
 
