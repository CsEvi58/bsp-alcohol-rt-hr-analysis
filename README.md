# bsp-alcohol-rt-hr-analysis
Final project repository for the BSP 2025 alcohol, reaction time and heart-rate analysis. Contains complete analysis code, raw datas.

**BSP_Project_team_pek.ipynb**

The complete analysis script, including:
  - Parsing raw SART `.txt` files  
  - Reaction-time feature computation  
  - Parsing Garmin `.tcx` heart-rate data  
  - Heart-rate and HRV-like (RMSSD-like) feature extraction  
  - Merging datasets into a unified summary table  
  - Statistical analysis (Shapiro–Wilk, Friedman, Wilcoxon)  
  - BMI integration  
  - Alcohol dose (ml/kg) integration and dose–response analysis  
  - Visualisation functions (boxplots, histograms, spaghetti plots)

**Project.zip**

Contains the raw behavioural files (`raw_sart/*.txt`), raw heart-rate time series (`raw_tcx/*.tcx`) and an xlsx file with the anonim participants' age, height, weight and alcohol dose data.  
The code creates a folder from the .zip file, the structure is explained below: 
project_data/  
|-- raw_sart/  
|-- raw_tcx/  
└-- participants.xlsx # Age, height, weight, BMI, alcohol dose   

**BSP_Project_team_pek.pdf**

The PDF contains a brief written summary of the project, including the research motivation, dataset description, preprocessing steps, statistical methods (Shapiro–Wilk, Friedman, Wilcoxon), visualisations, dose–response exploration, and interpretation of the main findings.
