# Data and R syntax for the published paper "Protective Efficacy Against Pandemic Influenza of Seasonal Influenza Vaccination in Children in Hong Kong: A Randomized Controlled Trial"

This repository contains an R script for processing and reformatting raw data related to the protective efficacy against pandemic influenza of seasonal influenza vaccination in children in Hong Kong. The study is based on the paper by Cowling BJ, et al. (CID, 2012).

PubMed link: https://pubmed.ncbi.nlm.nih.gov/22670050/  
PubMed Central full text link: https://academic.oup.com/cid/article/55/5/695/352104?login=true  
Publisher full text link: https://academic.oup.com/cid/article/55/5/695/352104

## Overview

In this study, we aim to process and reformat raw data related to a study examining the protective efficacy against pandemic influenza of seasonal influenza vaccination in children in Hong Kong. 

## Data

The data folder consists of raw and processed datasets used in our study which can be linked by the unique household ID ("hhID") and the unique participant ID within the household ("member"):

- `ARR.csv` includes information about the presence of various symptoms such as fever, chills, tiredness, headache, cough, muscle pain, swelling, redness, bruising, and injection site pain, collected at four different time points (d1 to d4) during the study. 

- `chronic_condition.csv` contains information about the presence of chronic conditions among the participants.

- `demographic.csv` contains demographic and other background information for participants in a study, possibly related to a clinical trial, health survey, or vaccination program. 

- `housechar.csv` illustrates the household characteristics of the participants.

- `qmdata_w_pH1.csv` contains information related to the presence of Influenza A (H1N1) and other influenza types among the participants.

- `randomcode.csv` includes the assignment of interventions to households.

- `serology.csv` contains information related to the serological test results of participants in the study,

- `swab.csv` contains information related to the nasal or throat swab test results of participants.

- `symptom_d.csv` includes information related to the daily self-reported symptoms of participants.


## Scripts

- `dataframe.r` is used to reformat raw data.

- `Figure_2.r` shows the timeline of subject recruitment and follow-up in 2009–2010.

- `Table_1.r` shows the baseline characteristics of children who received trivalent inactivated influenza vaccine or placebo and their household contacts.

- `Table_2.r` indicates the immunogenicity of the 2009–2010 seasonal trivalent inactivated influenza vaccine against seasonal and pandemic influenza strains.

- `Table_3.r` presents incidence rates per person-year of infection of laboratory-confirmed influenza by reverse-transcription polymerase chain reaction and serology, acute respiratory illness, and febrile acute respiratory illness among study subjects who received trivalent inactivated influenza vaccine or placebo.

- `Table_S1.r` shows the adverse reactions reported by children who received TIV or placebo.

- `Table_S2.r` shows the signs, symptoms, and syndromes associated with influenza A and B infections confirmed by RT-PCR in study subjects.

- `Table_S3.r` shows the comparisons of estimates of the cumulative incidence of infection among participants during the winter, summer, and overall study periods.

- `Table_S4.r` shows the cumulative incidence of infection of the 2009 pandemic influenza A(H1N1) (pH1N1) among children who received TIV or placebo, stratified by post-vaccination antibody titer against pH1N1.
  

## Usage

To use this dataset and analysis code, follow these steps:

1. Clone or download this repository to your local machine.
2. Install R and RStudio or any other R environment if you haven't already.
3. Open the R script in the `code` directory using RStudio or your preferred R environment.
4. Run the script to reproduce the data used in the study and perform further analysis as desired.

Please note that you may need to adjust file paths or make other modifications to the code to suit your specific environment or requirements.

## Citation

If you use any part of this study or its associated data and code, please cite the original publication: Benjamin J. Cowling, Sophia Ng, Edward S. K. Ma, Vicky J. Fang, Hau Chi So, Winnie Wai, Calvin K. Y. Cheng, Jessica Y. Wong, Kwok-Hung Chan, Dennis K. M. Ip, Susan S. Chiu, J. S. Malik Peiris, Gabriel M. Leung, Protective Efficacy Against Pandemic Influenza of Seasonal Influenza Vaccination in Children in Hong Kong: A Randomized Controlled Trial, Clinical Infectious Diseases, Volume 55, Issue 5, 1 September 2012, Pages 695–702, https://doi.org/10.1093/cid/cis518.
