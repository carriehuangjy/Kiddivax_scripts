# Data and R syntax for the published paper "The effect of age and recent influenza vaccination history on the immunogenicity and efficacy of 2009-10 seasonal trivalent inactivated influenza vaccination in children"

This repository contains an R script for processing and reformatting raw data related to the effect of age and recent influenza vaccination history on the immunogenicity and efficacy of 2009-10 seasonal trivalent inactivated influenza vaccination in children. The study is based on the paper by Ng S, et al. (PLoS ONE 2013).

PubMed link: https://pubmed.ncbi.nlm.nih.gov/23554974/  
PubMed Central full text link: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3595209/  
Publisher full text link: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0059077

## Overview

We aim to process and reformat raw data related to a study examining the effect of age and recent influenza vaccination history on the immunogenicity and efficacy of the 2009-10 seasonal trivalent inactivated influenza vaccination in children. 

## Data

The data folder consists of raw and processed datasets used in our study which can be linked by the unique household ID ("hhID") and the unique participant ID within the household ("member"):

- `ARR.csv` includes information about the presence of various symptoms such as fever, chills, tiredness, headache, cough, muscle pain, swelling, redness, bruising, and injection site pain, collected at four different time points (d1 to d4) during the study. 

- `chronic_condition.csv` contains information about the presence of chronic conditions among the participants.

- `demographic.csv` contains demographic and other background information for participants in a study, possibly related to a clinical trial, health survey, or vaccination program. 

- `housechar.csv` illustrates the household characteristics of the participants.

- `qmdata_w_pH1.csv` contains information related to the presence of Influenza A (H1N1) and other influenza types among the participants.

- `randomcode.csv` includes the assignment of interventions to households.

- `serology.csv` contains information related to the serological test results of participants in the study.

- `swab.csv` contains information related to the nasal or throat swab test results of participants.

- `symptom_d.csv` includes information related to the daily self-reported symptoms of participants.

## Scripts

- `dataframe.r` reformats the raw data for the study.

- `Figure_1.r` shows individual antibody titers before and one month after receipt of trivalent inactivated influenza vaccine (TIV) in 2009–2010 among 6–8 y (Y, represented by blue circles) and 9–17 y children (O, represented by grey circles) with regard to their vaccination history for the 2007–2008 and 2008–2009 seasons.

- `Figure_S2.r` shows the individual antibody titers before and one month after receipt of placebo in 2009–2010 among 6–8 y (Y, represented by blue circles) and 9–17 y children (O, represented by grey circles) with regard to their vaccination history for the 2007–2008 and 2008–2009 seasons.

- `Table_2.r` indicates characteristics of 479 subjects randomized to receive trivalent inactivated influenza vaccine (TIV) in 2009–10 with regard to their vaccination history in 2007–08 and 2008–09.

- `Table_3.r` presents factors affecting risk of RT-PCR confirmed influenza B infection and vaccine efficacy (VE) of trivalent inactivated influenza vaccine (TIV) in 2009–10.

- `Table_S1.r` shows comparison of antibody titers before and 1 month after receipt of 2009–10 trivalent inactivated influenza vaccine (TIV) in children 6–8 years of age with regard to their vaccination history.

- `Table_S2.r` presents comparison of antibody titers before and 1 month after receipt of 2009–10 trivalent inactivated influenza vaccine (TIV) in children 9–17 years of age with regard to their vaccination history.

- `Table_S3.r` shows the comparison of antibody titers before and 1 month after receipt of placebo in children 6–8 years of age with regard to their vaccination history.

- `Table_S4.r` shows the comparison of antibody titers before and 1 month after receipt of placebo in children 9–17 years of age with regard to their vaccination history.

## Usage

To use this dataset and analysis code, follow these steps:

1. Clone or download this repository to your local machine.
2. Install R and RStudio or any other R environment if you haven't already.
3. Open the R script in the `code` directory using RStudio or your preferred R environment.
4. Run the script to reproduce the data used in the study and perform further analysis as desired.

Please note that you may need to adjust file paths or make other modifications to the code to suit your specific environment or requirements.

## Citation

If you use any part of this study or its associated data and code, please cite the original publication: Ng, S., Ip, D. K., Fang, V. J., Chan, K. H., Chiu, S. S., Leung, G. M., ... & Cowling, B. J. (2013). The effect of age and recent influenza vaccination history on the immunogenicity and efficacy of 2009–10 seasonal trivalent inactivated influenza vaccination in children. PloS one, 8(3), e59077.

