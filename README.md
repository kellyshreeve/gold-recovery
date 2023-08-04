# Predicting Gold Recovery from Ore

<p align="center">
  <img src="https://github.com/kellyshreeve/gold-recovery/blob/main/imgaes/recovery_process.png" 
  alt="Image of gold recovery stages">
</p>

# Project Overview

This repository hosts an Supervised Machine Learning project building a multi-output regression that minimizes symmetric Mean Absolute Error (sMAPE). This data science project was conducted for Zyfra, a company that develops efficiency solutions for heavy industry, with the purpose of finding which model for gold estraction bet minimizes sMAPE and identifying which factors are unprofitable.

# Installation and Setup

## Codes and Resources Used

  - <b>Editor Used</b>: Visual Studio Code
  - <b>Python Version</b>: 3.10.9

## Python Packages Used

  - <b>General Purpose</b>: ```numpy```
  - <b>Data Manipulation</b>: ```pandas```
  - <b>Data Visualization</b>: ```matplotlib```
  - <b>Statistical Analysis</b>: ```statsmodels```
  - <b>Machine Learning</b>: ```sklearn```
    
# Data

## Source Data

There are three data sets containin information on the full set, a training set, and test set:  

*gold_recovery_full.csv*  
*gold_recovery_train.csv*  
*gole_recovery_test.csv* 

Each dataset contains input and output measures for each stage in the gold recovery process. Some inputs are floatbank parameters such as air and water level and other inputs are concentrations of metal and solids in the ore. Outputs measure the concentration of metals and other solids in the concentrate and in the tails.

Feature naming construction:  
[stage]_[parameter_type].[parameter_name]

Observations close to each other in time are often similar.

## Data Acquisition

The data were provided by TripleTen's Data Science bootcamp. As such the full dataset is loaded into the notebook but is proprietary information and cannot be shared online with the project.

## Data Preprocessing

Data were checked for missing values and duplicates. Missing values were imputed with the average of forward and backward fill. There were no duplicates.
 
# Code Structure
```
  ├── LICENSE
  ├── README.md          
  │
  ├── images
  │   └── recovery_process.png    
  │
  └── notebooks  
     └── gold-recovery-analysis.ipynb
 
```

# Results and Evaluation

<p align="center">
  <img src="https://github.com/kellyshreeve/Zuber_Rides_Analysis/blob/main/images/trips-company.png" 
  alt="Bar graph of total trips by company">
</p>

<p align="center">
  <img src="https://github.com/kellyshreeve/Zuber_Rides_Analysis/blob/main/images/drop-offs.png" 
  alt="Bar graph of average drop offs by neighborhood">
</p>

<p align="center">
  <img src="https://github.com/kellyshreeve/Zuber_Rides_Analysis/blob/main/images/hypothesis-test.png" 
  alt="Statistical output of two-indpendent samples t-test comparing average trip length in good vs bad weather">
</p>

# Future Work

# Acknowledgments/References
