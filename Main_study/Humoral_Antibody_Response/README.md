# Data and R syntax for the published paper "Humoral Antibody Response after Receipt of Inactivated Seasonal Influenza Vaccinations one Year Apart in Children"

This repository contains an R script for processing and reformatting raw data related to the humoral antibody response after receipt of inactivated seasonal influenza vaccinations one year apart in children. The study is based on the paper by Ng S, et al. (PIDJ, 2012).

PubMed link: https://pubmed.ncbi.nlm.nih.gov/22683675/  
PubMed Central full text link: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3422369/  
Publisher full text link:https://journals.lww.com/pidj/fulltext/2012/09000/humoral_antibody_response_after_receipt_of.24.aspx

## Overview

In a randomized controlled trial, we administered seasonal trivalent inactivated influenza vaccine (TIV) or placebo to subjects 6–15 years of age in two consecutive years. Receipt of TIV in year 2 induced seroprotection in most subjects. Among 39 children who received TIV in the second year, receipt of TIV in the first year was associated with lower antibody titer rises in the second year to seasonal influenza A(H1N1) and A(H3N2) strains for which the vaccine strains remained unchanged. Antibody response to a different influenza B strain in the second year was unaffected by receipt of TIV in the first year.

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

- `QMHisolate.csv` contains information related to the weekly counts of laboratory-confirmed influenza virus isolates, which are virus samples collected from patients and identified through laboratory testing.

- `demographic_m.csv` includes demographic information related to individual participants in a study, possibly related to a clinical trial, health survey, or vaccination program.

- `housechar_h.csv` illustrates the household characteristics of the participants.

- `resplex.csv` contains information related to laboratory test results for individual participants in a study, possibly related to a clinical trial, health survey, or vaccination program.

- `serology_m.csv` shows serological test results for individual participants in a study, possibly related to a clinical trial, health survey, or vaccination program.

## Scripts

- `dataframe.r` is used to reformat and merge raw data from two separate studies, "KiddivaxPilotV2" and "KiddivaxMainV1", which are related to the humoral antibody response after receipt of inactivated seasonal influenza vaccinations one year apart in children.

- `Figure_1.r` shows the changes in seasonal influenza A H1N1 virus antibody titers in subjects treated with TIV.

- `Table_1.r` shows the comparison of geometric mean and geometric mean ratio of antibody titers (GMT) before and 1 month after receipt of trivalent inactivated influenza vaccine (TIV) or placebo in year 1 (2008–2009) and year 2 (2009–2010) in 39 children who received TIV in year 2 (2009–2010).

- `Table_2.r` indicates the comparison of geometric mean and geometric mean ratio of antibody titers (GMT) before and one month after receipt of trivalent inactivated influenza vaccine (TIV) or placebo in year 1 (2008–2009) and year 2 (2009–2010) in 25 children who received placebo in year 2 (2009–2010).

- `Table_3.r` shows the factors affecting the geometric in antibody titers ratio post-vaccination to pre-vaccination following receipt of trivalent inactivated influenza vaccine (TIV) in year 2 (2009–10).

## Usage

To use this dataset and analysis code, follow these steps:

1. Clone or download this repository to your local machine.
2. Install R and RStudio or any other R environment if you haven't already.
3. Open the R script in the `code` directory using RStudio or your preferred R environment.
4. Run the script to reproduce the data used in the study and perform further analysis as desired.

Please note that you may need to adjust file paths or make other modifications to the code to suit your specific environment or requirements.

## Citation

If you use any part of this study or its associated data and code, please cite the original publication: Ng S, Fang VJ, Ip DK, Chiu SS, Leung GM, Peiris JS, Cowling BJ. Humoral antibody response after receipt of inactivated seasonal influenza vaccinations one year apart in children. Pediatr Infect Dis J. 2012 Sep;31(9):964-9. doi: 10.1097/INF.0b013e318263280e. PMID: 22683675; PMCID: PMC3422369.
