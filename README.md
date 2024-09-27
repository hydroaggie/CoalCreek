# Quantitative Evaluation of Baseflow Separation Methods Using an Integrated Hydrologic Model: A Case Study in a Snow-Dominated Watershed

**Citation**: Othman, Jihad, "Quantitative Evaluation of Baseflow Separation Methods Using an Integrated Hydrologic Model: A Case Study in a Snow-Dominated Watershed" (2024). [Master's Thesis](https://digitalcommons.usu.edu/gradreports2023/60/)

This repository contains the workflow for estimating baseflow in a snow-dominated watershed using an integrated hydrologic model and baseflow separation methods. It includes tools for visualizing results and performing post-processing data analysis. The project explores multiple conceptual baseflow separation methods.

## Repository Structure

```bash
├── data       
│   ├── model_input           # Input data for hydrologic modeling to run the ATS model
│   ├── model_output          # Output data fobtained from running the ATS model 
│
├── notebooks                 # Jupyter Notebooks for separating baseflow and generating statistics, maps, and figures
└── figures                   # Visual outputs (graphs, charts) from the modeling and analysis
```


## Project Overview

The project is divided into two parts:

### Hydrologic Model Simulation:

The first part involves running the integrated hydrologic model to quantitatively estimate streamflow and groundwater discharge. For the complete workflow, model input preparation and ATS model run, refer to the following link: [ATS Workflow](https://github.com/pinshuai/ats-workflow). The ATS model requires the input file located at `data/model_input/model_input_2014_2022.xml`. Once the input file is prepared, run the ATS model, which will generate the output file `data/model_output/water_balance-daily.dat`. 

### Baseflow Separation:
The second part focuses on baseflow separation using the streamflow data from the ATS model output. The notebooks in the `notebooks` folder use the file `data/model_output/water_balance-daily.dat` to perform baseflow separation with subsurface variables and generate figures, plots, and statistics for the report. These notebooks handle the post-processing, including the generation of all statistics and visualizations included in the report.
