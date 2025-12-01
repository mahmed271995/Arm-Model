# Arm Model

This repository contains the MATLAB codes used to reproduce the results for the following publications:  
Ahmed, M.H.; N’Guessan, J.-E.; Das, R.; Leineweber, M.; Goyal, S. Simplified Cost Functions Meet Advanced Muscle Models to Streamline Muscle Force Estimation. BioMed 2024, 4, 350–365. https://doi.org/10.3390/biomed4030028

Organization is as follows:
1. Code: Has the arm mode code used to generate all the data plots corresponding to `Figures 2-6` in the manuscript
2. Data: Has the code and data for section `3.3 Model Validation` of the manuscript to reproduce the plots corresponding to `Figures 7-8`

## Prerequisites
Before running the code, ensure you have the following MATLAB toolboxes installed:  
* Symbolic Math Toolbox
* Optimization Toolbox

## Instructions for running code

### 1. Clone the Repository
You can download the repository by either cloning it using Git or downloading the ZIP file

**Clone via Git**:
```
git clone https://github.com/mahmed271995/Arm-Model
```

### 2. Run the Arm Model Simulation (Figures 2-6)
* Navigate to the `Code` folder
* Open the file `Arm_Model.mlx` on MATLAB and click **Run** to execute the simulation
  - This will solve the system of equations, generate all required variables, and produce the plots corresponding to `Figures 2-6` in the manuscript

### 3. Run the Data Analysis and Model Validation (Figures 7-8)
* Navigate to the `Data` folder
* Open the file `Data_Code.mlx` on MATLAB and click **Run** to execute the simulation
  - This will import all the `.csv` files and produce the plots corresponding to `Figures 7-8` in the manuscript

## Citation

If you use this code in your research, please cite the following paper:

**Ahmed, M.H.; N’Guessan, J.-E.; Das, R.; Leineweber, M.; Goyal, S.**  
*Simplified Cost Functions Meet Advanced Muscle Models to Streamline Muscle Force Estimation.*  
**BioMed 2024, 4, 350–365.**  
[DOI: 10.3390/biomed4030028](https://doi.org/10.3390/biomed4030028)
