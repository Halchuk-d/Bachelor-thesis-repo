# Bachelor-thesis-repo
This repo contains Python code and Gretl scripts used in all analyses. Access to data is reqiured to perform calculations
## Research reproduction manual

 ### WBES analysis
1. Data extraction with python
   
   Unpack folders "datasets" and "datasets_incomplete" from the ZIP file and load them to local Google Drive
   
   Open WBES_analysis_final_extended.ipynb and WBES_analysis_for_incomplete_extended.ipynb in Google Colab and follow the instructions in the comments
   
3. Mann-Whitney U-test replication
   
   Download WBES_data.xlsx from the zip file
   
   Open Mann_Whitney_U_test.ipynb in Google Colab and follow the instructions in the comments
   

### Regression Modelling

   Download all the files from the folder regression_modelling and assign the files to one folder
   
   Download logitreg_data.xlsx from the ZIP file and assign to the folder where scripts are located
   
   Open Logit_regression.inp and follow the instructions in the comments
   
   To draw the graph of the main Model 5 outcome simply run plot_CD_slopes.inp
   
## Data
This research uses microdata from the World Bank Enterprise Surveys and intra-firm data from Moody's Orbis database

The raw datasets are not included in this repository because access to and dissemination of the data are subject to the Data Access Protocol and personal data and confidentiality requirements.

Researchers wishing to reproduce the analysis should obtain the data directly from said databases and comply with the applicable terms of access.

**Data source:** World Bank Enterprise Surveys

**Source:** https://www.enterprisesurveys.org/en/data

**Data source:** Moody’s Corporation. Orbis 

**Source:** https://www.bvdinfo.com/
