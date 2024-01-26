# Data and R syntax for the published paper "Increased Risk of Noninfluenza Respiratory Virus Infections Associated With Receipt of Inactivated Influenza Vaccine"

This repository contains the scripts related to the respiratory analysis in the Kiddivax Pilot study of the pediatric vaccine trial research project. These scripts are specific to the analysis and processing of data related to respiratory outcomes in the context of the CID (Community-Associated Infections and Disease) module of the study.

PubMed link: https://pubmed.ncbi.nlm.nih.gov/22423139/  
PubMed Central full text link: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3404712/    
Publisher full text link: https://academic.oup.com/cid/article/54/12/1778/455098?login=true  

## Overview

In this study, we aim to investigate whether the inactivated influenza vaccine (IIV) is associated with an increased risk of non-influenza respiratory viral infections (NIRV) in children. We analyzed data from a randomized controlled trial that involved 115 children aged 6-15 months who received either IIV or a control vaccine. The results showed that children who received IIV had a significantly higher risk of developing NIRV compared to those who received the control vaccine. 

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
