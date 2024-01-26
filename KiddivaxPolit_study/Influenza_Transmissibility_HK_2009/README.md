# Data and R syntax for the published paper "Protective Efficacy of Seasonal Influenza Vaccination against Seasonal and Pandemic Influenza Virus Infection during 2009 in Hong Kong"

This repository contains the scripts related to the transmission analysis in the Kiddivax Pilot study of the pediatric vaccine trial research project. These scripts are specifically designed for analyzing and processing data related to the transmission dynamics of the disease in the context of the Kiddivax Pilot study. 

PubMed link: https://pubmed.ncbi.nlm.nih.gov/21067351/  
PubMed Central full text link: https://academic.oup.com/cid/article/51/12/1370/316441?login=true  
Publisher full text link: https://academic.oup.com/cid/article/51/12/1370/316441

## Overview

The KiddivaxPilot_Transmission_scripts repository contains the scripts used for analyzing and processing data specifically related to the transmission dynamics in the Kiddivax Pilot study of the pediatric vaccine trial research project. These scripts perform various tasks such as modeling transmission, running simulations, and generating tables and figures related to the transmission analysis.

## Data

The data folder consists of raw and processed datasets used in our study. This includes:

- `ARR.csv` includes information about the presence of various symptoms such as fever, chills, tiredness, headache, cough, muscle pain, swelling, redness, bruising, and injection site pain, collected at four different time points (d1 to d4) during the study. 

- `QMHisolate.csv` contains weekly records of different types of influenza infections, as well as the total number of non-influenza respiratory virus infections. 

- `demographic.csv` contains demographic and other background information for participants in a study, possibly related to a clinical trial, health survey, or vaccination program.

- `housechar_h.csv` illustrates the household characteristics of the participants.
  
- `randomcode_h.csv` includes the assignment of interventions to households.

- `serology.csv` contains information related to the serological test results of participants in the study,

- `swab.csv` contains information related to the nasal or throat swab test results of participants.

- `symptom_d.csv` includes information related to the daily self-reported symptoms of participants.
  
## Scripts

- `dataframe.r` reformats raw data of the study.

- `dataframe_cross.r` adjustes for cross reactivity of the raw data.

- `Figure_1.r` shows the flow of participants through the study.

- `Figure_S1.r` visualizes the proportion of positive isolates for different types of influenza viruses (Pandemic A(H1N1), Seasonal A, and Seasonal B) over time. 

- `Figure_S2.r` creates a plot that displays antibody titers before and after vaccination for two different flu strains (A/H1N1 and A/H3N2) and one strain of influenza B, separated by intervention group (TIV or placebo). 

- `Figure_S3.r` plots Daily Adverse Reaction    

- `Figure_S4.r` plots a graph with antibody titers to pandemic A/H1N1 on the y-axis and different categories of infection on the x-axis. 

- `Table_1.r` shows the baseline characteristics of children who received trivalent influenza vaccine (TIV) or placebo and their household contacts.

- `Table_2.r` presents antibody titers against seasonal A/H1N1, seasonal A/H3N2, and pandemic A/H1N1 virus before and 1 month after receipt of trivalent inactivated vaccine (TIV) or placebo.
  
- `Table_3.r` shows the attack rates of laboratory-confirmed influenza infections and acute respiratory illnesses in children who received trivalent inactivated vaccine (TIV) or placebo and their household contacts.

- `Table_4.r` illustrates the rates of laboratory-confirmed influenza infections and acute respiratory illnesses in study subjects and household contacts, stratified into Winter 2008–2009 and Summer 2009 influenza seasons.

- `Table_5.r` shows the rate of influenza-like illness (ILI) in study subjects who received trivalent inactivated vaccine (TIV) or placebo and had serologically confirmed influenza.

- `Table_6.r` indicates the factors associated with the risk of laboratory-confirmed pandemic influenza.

- `Table_7.r` shows the factors associated with the risk of laboratory-confirmed (by reverse-transcription polymerase chain reaction or serological testing) pandemic influenza, with analysis stratified by vaccines and household contact status.
 
- `Table_8.r` illustrates the factors associated with the risk of laboratory-confirmed pandemic influenza, with prior seasonal influenza infection stratified into laboratory-confirmed influenza A/H1N1 and A/H3N2 infection.

## Usage

To use this dataset and analysis code, follow these steps:

1. Clone or download this repository to your local machine.
2. Install R and RStudio or any other R environment if you haven't already.
3. Open the R script in the `code` directory using RStudio or your preferred R environment.
4. Run the script to reproduce the data used in the study and perform further analysis as desired.

Please note that you may need to adjust file paths or make other modifications to the code to suit your specific environment or requirements.

## Citation

If you use any part of this study or its associated data and code, please cite the original publication: Benjamin J. Cowling, Sophia Ng, Edward S. K. Ma, Calvin K. Y. Cheng, Winnie Wai, Vicky J. Fang, Kwok-Hung Chan, Dennis K. M. Ip, Susan S. Chiu, J. S. Malik Peiris, Gabriel M. Leung, Protective Efficacy of Seasonal Influenza Vaccination against Seasonal and Pandemic Influenza Virus Infection during 2009 in Hong Kong, Clinical Infectious Diseases, Volume 51, Issue 12, 15 December 2010, Pages 1370–1379, https://doi.org/10.1086/657311

