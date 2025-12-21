# Financial Literacy and Policy Optionality in Massachusetts

### Data and Replication Materials
This repository contains anonymized survey data and analysis code supporting the paper: "“I’m Cooked”: Financial Literacy, Policy Optionality, and Educational Inequity in Massachusetts High Schools".

The associated paper examines the effectiveness of optional financial literacy education policies in Massachusetts, combining national and state-level policy analysis with an original, school-based case study survey.

## Repository Contents

### 1. financial_literacy_responses.csv

Anonymized student survey responses collected at a Massachusetts public high school (Arlington High School).

Includes:
- Respondent ID (synthetic, non-identifiable)
- Financial literacy assessment scores (out of 12)
- Grade level
- Self-reported exposure to financial education
- Self-reported confidence and perceived importance measures

No personally identifiable information (PII) is included.

### 2. data_analysis.Rmd

Reproducible R Markdown file used to generate all descriptive statistics, figures, and summary tables reported in the paper.

Includes:
- Data cleaning and preprocessing
- Descriptive statistics
- Visualization of score distributions, confidence vs. importance, and access to financial education
- Designed to run end-to-end using the provided CSV file.

### 3. Data Collection Notes

The survey was administered via Google Forms in June 2025. Participation was voluntary and anonymous. Furthermore, the study was conducted for policy research purposes and does not involve experimental intervention.

Due to the involvement of minors, only anonymized and aggregated data are shared publicly.

## Reproducibility

To reproduce the analysis:
1) Download or clone this repository.
2) Open data_analysis.Rmd in RStudio.
3) Ensure the following packages are installed:
- tidyverse
- ggplot2
- dplyr
- readr
- knitr

4) Knit the R Markdown file to generate figures and summary statistics.

All results in the paper are derived directly from the scripts contained in this repository.

## Limitations

The dataset reflects a single-district case study and is not intended to be statewide-representative. Findings should be interpreted as illustrative of structural patterns rather than causal estimates. In addition, self-reported confidence measures may be subject to response bias.

These limitations are discussed in detail in the paper.

## Contact

For questions regarding the data, analysis, or policy implications, please contact the author via zhangyaxin74@gmail.com. 
