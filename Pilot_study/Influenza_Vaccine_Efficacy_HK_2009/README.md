# Data and R syntax for the published paper "Transmissibility of seasonal and pandemic influenza in a cohort of households in Hong Kong in 2009"

This repository contains the scripts used in the Kiddivax Pilot study of the pediatric vaccine trial research project. These scripts are designed for various tasks related to the study, including data analysis, visualization, and processing. 


PubMed link: https://pubmed.ncbi.nlm.nih.gov/21878814/  
PubMed Central full text link: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3206962/  
Epidemiology link: https://journals.lww.com/epidem/fulltext/2011/11000/transmissibility_of_seasonal_and_pandemic.5.aspx

## Overview

In this study, we aime to investigate the transmission dynamics of seasonal and pandemic influenza in households in Hong Kong during the 2009 influenza pandemic. We analyzed the final outbreak size distributions of pandemic A(H1N1), seasonal A(H1N1), and A(H3N2) infections identified in paired sera collected from members of 117 Hong Kong households in April and in August-October 2009. The result showed that pandemic and seasonal influenza A viruses had similar age-specific transmissibility in a cohort of initially uninfected households, after adjustment for baseline immunity.

## Scripts

The repository has the following file structure:

- `MCMC_function.r` produces the MCMC function used in the study.
  
- `Table_1.r` shows the risk of influenza virus infection by individual characteristics in 425 adults and children.
  
- `Table_2.r` indicates the subtype-specific estimates of community probabilities of infection and SAPs for children and adults.

- `Figure_1to3.r` presents the community probility of infection of children and adults.
  
- `eTable_2.r` shows sample sizes and proportions infected in subgroup analyses excluding individuals with higher baseline seasonal A antibody titers. 
  
- `eTable_3.r` presents the estimates of the Community Probability of Infection and the Secondary Attack Proportion (SAP) for children and adults who did not receive seasonal vaccination.  

- `eTable_4.r` shows the estimates of the Community Probability of Infection and the Secondary Attack Proportion (SAP) for children and adults for pH1N1 excluding all individuals who had been infected with either seasonal A(H1N1) or A(H3N2).
  
- `eTable_5.r` shows the estimates of the Community Probability of Infection and the Secondary Attack Proportion (SAP) for children and adults allowing
individuals to be infected with more than one strain.

## Usage

To use this dataset and analysis code, follow these steps:

1. Clone or download this repository to your local machine.
2. Install R and RStudio or any other R environment if you haven't already.
3. Open the R script in the `code` directory using RStudio or your preferred R environment.
4. Run the script to reproduce the data used in the study and perform further analysis as desired.

Please note that you may need to adjust file paths or make other modifications to the code to suit your specific environment or requirements.

## Citation

If you use any part of this study or its associated data and code, please cite the original publication: Klick B, Nishiura H, Ng S, Fang VJ, Leung GM, Peiris JS, Cowling BJ. Transmissibility of seasonal and pandemic influenza in a cohort of households in Hong Kong in 2009. Epidemiology. 2011 Nov;22(6):793-6. doi: 10.1097/EDE.0b013e3182302e8e. PMID: 21878814; PMCID: PMC3206962.

