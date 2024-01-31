# R syntax for the published paper "Estimation of the association between antibody titers and protection against confirmed influenza virus infection in children"

This repository contains the source code for the research paper titled "Estimation of the association between antibody titers and protection against confirmed influenza virus infection in children" by Ng et al published in the Journal of Infectious Diseases in 2013. 

PubMed link: https://pubmed.ncbi.nlm.nih.gov/23908481/   
PubMed Central full text link: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3778972/   
Publisher full text link: https://academic.oup.com/jid/article/208/8/1320/2193380  

## Overview

In this study, we aimed to determine the relationship between hemagglutination inhibition antibody (HAI) titers and protection against influenza virus infection in children. We found that higher HAI titers were significantly associated with greater protection against confirmed influenza virus infection, estimating that an HAI titer of 1:110 provided a 50% reduction in risk and an HAI titer of 1:330 provided an 80% reduction in risk.

## Scripts

In the code folder we provide the R files as follows:
  
- `Figure_1.r` generates timeline of the study, influenza activity in the community was based on a proxy measure and postvaccination, midstudy, and poststudy HAI titers against influenza A(H1N1)pdm09 and B(Victoria lineage) virus in children.
  
- `Figure_2.r` generates the estimated protection against infection among study participants, based on HAI titers at 1 to 9 months following receipt of trivalent inactivated influenza vaccine (TIV).
  
- `source_1.r` contains source code for a specific functionality of calculating a rescale factor obtained from the proxy for influenza A and B and performs various data wrangling operations and statistical calculations to estimate the association between antibody titers and protection against confirmed influenza virus infection in children.
  
- `source_2.r` reads data files, performs data cleaning and processing, and fits several Generalized Estimating Equation (GEE) models to the data. The models estimate the association between antibody titers and protection against influenza virus infection, and the effect of vaccination on antibody titers and protection. In additions, the script also calculates sample sizes for each group in the study.
  
- `source_3.r` generates a statistical model that evaluates the correlation between HAI titer and subsequent protection against confirmed influenza virus infection in children. It reads in data and uses Cox model to take into account the background risk of infection, waning HAI antibodies, and beta*titer(t0). It also creates a smoothed proxy for background risk and merges PCR type and date. Finally, the code creates a dataframe for the best waning parameter value and uses Coxph to find the correlation between post-vaccination and proxy.
  
- `source_4.r` predicts the post-vaccination titers of influenza B virus for each participant in a study.
  
- `source_5.r` performs data analysis on serology data for different interventions (TIV and placebo) and different viruses (pH1 and B.Brisbane).
  
- `source_6.r` investigates the impact of influenza vaccines on serology titers over time, specifically comparing the effectiveness of TIV and placebo interventions for different influenza strains.

- `Appendix_Figure_1.r` shows post-vaccination, mid-study and post-study HAI titers against influenza A(H1N1)pdm09 and B (Victoria-lineage) virus. 
  
- `Appendix_Table_1.r` indicates the baseline characteristics of 773 children who were randomized to receive TIV or placebo and for whom post-vaccination HAI antibody titers were available. 
  
- `Appendix_Table_2.r` shows the estimated waning rate of HAI titers among children who were randomized to receive TIV or placebo. 
  
## Usage

To use this dataset and analysis code, follow these steps:

1. Clone or download this repository to your local machine.
2. Install R and RStudio or any other R environment if you haven't already.
3. Open the R script in the `code` directory using RStudio or your preferred R environment.
4. Run the script to reproduce the data used in the study and perform further analysis as desired.

Please note that you may need to adjust file paths or make other modifications to the code to suit your specific environment or requirements.

## Citation

If you use any part of this study or its associated data and code, please cite the original publication: Sophia Ng, Vicky J. Fang, Dennis K. M. Ip, Kwok-Hung Chan, Gabriel M. Leung, J. S. Malik Peiris, Benjamin J. Cowling, Estimation of the Association Between Antibody Titers and Protection Against Confirmed Influenza Virus Infection in Children, The Journal of Infectious Diseases, Volume 208, Issue 8, 15 October 2013, Pages 1320–1324, https://doi.org/10.1093/infdis/jit372.
