# Quantitative Evaluation of Baseflow Separation Methods Using an Integrated Hydrologic Model: A Case Study in a Snow-Dominated Watershed

**Citation**: Othman, Jihad, "Quantitative Evaluation of Baseflow Separation Methods Using an Integrated Hydrologic Model: A Case Study in a Snow-Dominated Watershed" (2024). [Master's Thesis](https://digitalcommons.usu.edu/gradreports2023/60/)

This repository contains the workflow for estimating baseflow in a snow-dominated watershed using an integrated hydrologic model and baseflow separation methods. It includes tools for visualizing results and performing post-processing data analysis. The project explores multiple conceptual baseflow separation methods.

## Repository Structure

```bash
├── data       
│   ├── model_input           # Input data for hydrologic modeling to run the ATS model
│
├── notebooks                 # Jupyter Notebooks for separating baseflow and generating statistics, maps, and figures
└── figures                   # Visual outputs (graphs, charts) from the modeling and analysis
```


## Project Overview

The project is divided into two parts:

### Hydrologic Model Simulation:
The first part involves running the integrated hydrologic model to quantitatively estimate streamflow and groundwater discharge. For the complete workflow, model input preparation and ATS model run, refer to the following link: [ATS Workflow](https://github.com/pinshuai/ats-workflow). After creating the input file, run the ATS model to estimate streamflow and other hydrological variables. The ATS model input file (XML file) is provided in `data/model_input`

### Baseflow Separation:
The second part uses the streamflow data obtained from the model. With the notebooks provided in the repository's `notebooks` folder, you can perform baseflow separation using numerical and conceptual methods. The notebooks will also generate all the figures and statistics required for analysis and reporting.


