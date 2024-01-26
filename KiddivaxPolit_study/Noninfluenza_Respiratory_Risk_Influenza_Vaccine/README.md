# Data and R syntax for the published paper "Increased Risk of Noninfluenza Respiratory Virus Infections Associated With Receipt of Inactivated Influenza Vaccine"

This repository contains the scripts related to the respiratory analysis in the Kiddivax Pilot study of the pediatric vaccine trial research project. These scripts are specific to the analysis and processing of data related to respiratory outcomes in the context of the CID (Community-Associated Infections and Disease) module of the study.

PubMed link: https://pubmed.ncbi.nlm.nih.gov/22423139/  
PubMed Central full text link: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3404712/    
Publisher full text link: https://academic.oup.com/cid/article/54/12/1778/455098?login=true  

## Overview

The KiddivaxPilot_CID_respiratory_scripts repository contains the scripts used for analyzing and processing data specifically related to the respiratory outcomes in the Kiddivax Pilot study of the pediatric vaccine trial research project. These scripts perform various tasks such as data cleaning, statistical analysis, and generating tables and figures specifically focused on respiratory data.

## Data

The data folder consists of raw and processed datasets used in our study. This includes:

- `ARR.csv` includes information about the presence of various symptoms such as fever, chills, tiredness, headache, cough, muscle pain, swelling, redness, bruising, and injection site pain, collected at four different time points (d1 to d4) during the study. 

- `QMHisolate.csv` contains weekly records of different types of influenza infections, as well as the total number of non-influenza respiratory virus infections. 

- `demographic.csv` contains demographic and other background information for participants in a study, possibly related to a clinical trial, health survey, or vaccination program.

- `housechar_h.csv` illustrates the household characteristics of the participants.
  
- `chronic_condition.csv` contains information about the presence of chronic conditions among the participants.

- `randomcode_h.csv` includes the assignment of interventions to households.

- `housechar.csv` illustrates the household characteristics of the participants.

- `resplex.csv` contains information related to laboratory test results for individual participants in a study, possibly related to a clinical trial, health survey, or vaccination program.

- `serology.csv` contains information related to the serological test results of participants in the study,

- `swab.csv` contains information related to the nasal or throat swab test results of participants.

- `symptom_d.csv` includes information related to the daily self-reported symptoms of participants.


## Scripts

- `dataframe.r` reformats the raw data of the study.

- `Figure_1.r` illustrates the timing of influenza and other respiratory virus detections.

- `Table_1.r` shows the characteristics of participants and duration of follow-up.

- `Table_2.r` indicates the incidence rates of acute upper respiratory tract infection among 115 participants aged 6–15 years who received trivalent inactivated influenza vaccine or placebo.

- `Table_3.r` shows incidence rates of respiratory virus detection by reverse-transcription polymerase chain reaction and multiplex assay.


## Usage

To use this dataset and analysis code, follow these steps:

1. Clone or download this repository to your local machine.
2. Install R and RStudio or any other R environment if you haven't already.
3. Open the R script in the `code` directory using RStudio or your preferred R environment.
4. Run the script to reproduce the data used in the study and perform further analysis as desired.

Please note that you may need to adjust file paths or make other modifications to the code to suit your specific environment or requirements.

## Citation

If you use any part of this study or its associated data and code, please cite the original publication: Benjamin J. Cowling, Vicky J. Fang, Hiroshi Nishiura, Kwok-Hung Chan, Sophia Ng, Dennis K. M. Ip, Susan S. Chiu, Gabriel M. Leung, J. S. Malik Peiris, Increased Risk of Noninfluenza Respiratory Virus Infections Associated With Receipt of Inactivated Influenza Vaccine, Clinical Infectious Diseases, Volume 54, Issue 12, 15 June 2012, Pages 1778–1783, https://doi.org/10.1093/cid/cis307.
