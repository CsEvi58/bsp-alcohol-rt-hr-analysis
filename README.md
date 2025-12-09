# bsp-alcohol-rt-hr-analysis
Final project repository for the BSP 2025 alcohol, reaction time and heart-rate analysis. Contains complete analysis code, raw data not included for privacy reasons.

**bsp_project_team_pek.py**

The complete analysis script, including:
  - Parsing raw SART `.txt` files  
  - Reaction-time feature computation  
  - Parsing Garmin `.tcx` heart-rate data  
  - Heart-rate and HRV-like feature extraction  
  - Merging datasets into a unified summary table  
  - Statistical analysis (Shapiro–Wilk, Friedman, Wilcoxon)  
  - BMI integration  
  - Alcohol dose (ml/kg) integration and dose–response analysis  
  - Visualisation functions (boxplots, histograms, spaghetti plots)

Raw behavioural files (`raw_sart/*.txt`), heart-rate time series (`raw_tcx/*.tcx`), and participant metadata are **not uploaded** due to data protection considerations.

The uploaded folder's structure explained:  
project_data/  
|-- raw_sart/  
|-- raw_tcx/  
└-- participants.xlsx # Age, height, weight, BMI, alcohol dose   
