# Identity Conformity in Taiwan and South Korea: Why Citizens in Divided Societies Are Pressured to Overstate National Pride**

## Project Overview
This repository accompanies the working paper **“Identity Conformity and Concealment in Taiwan and South Korea: Why Citizens in Divided Societies Are Pressured to Overstate National Pride.”** 

The project investigates how social and political pressures shape the public expression of national identity in two divided democratic contexts. Using list experiments embedded in public opinion surveys, the study examines how dominant identity norms induce conformity across different subgroups.

## Research Questions

1. Do Taiwanese and South Koreans overstate national pride because of social conformity pressures?  
2. Are conformity pressures strongest among identity‐contested subpopulations?  
3. Which national context displays tighter enforcement of dominant identity norms?

## Key Findings

1. National pride is systematically inflated** when measured with direct questions.  
2. Conformity pressures are subgroup‐specific**—dual identifiers in Taiwan and North Korean migrants in South Korea exhibit the largest gaps.  
3. South Korea’s identity regime enforces stronger conformity** than Taiwan’s more pluralistic environment.

## Authors

| Name | Institution |
|------|-------------|
| **Steven Denney** | Leiden University |
| **H. Christoph Steinhardt** | University of Vienna |
| **Lisa Bhowmick** | Leiden University |

**Funding:** Academy of Korean Studies (Grant **AKS-2023-R-018**)

## Data
| Sample | N | Recruitment | Fieldwork Window | Key Quotas |
|--------|---|-------------|------------------|------------|
| Taiwan (native) | 2,050 | Qualtrics panel | Jan–Jun 2024 | Age, sex, region |
| South Korea (native) | 2,006 | Qualtrics panel | Jan–Jun 2024 | Age, sex, region |
| South Korea (North Korean migrants) | 316 | NGO *Woorion* | Sep–Oct 2023 | ≥ 12 yrs in DPRK |

All surveys received institutional ethics approval (University of Vienna, #00654 & #00997).

## Methods
* **List experiments** (item count technique) estimate hidden endorsement of national pride.
* Direct pride items use identity‐strength scales for subgroup classification.
* Estimation: `ictreg` maximum likelihood models (indirect) + logistic models (direct) with covariate adjustment (age, sex, education, ideology).
* Robustness checks include list experiments on support for Taiwan independence and South Korea’s National Security Act.

## Replication Materials

This repository accompanies the pre-publication version of the paper and currently does **not** include any data or analysis files. Upon publication, the following materials will be provided in full:

- **Complete analysis script**: a single Quarto file (`findings.qmd`) that includes all code used to clean data, estimate models, and generate tables and figures.
- **De-identified microdata** for the Taiwan and South Korea (native-born) samples.
- **Anonymized microdata** for the North Korean migrant sample (subject to ethical review and data-sharing restrictions).
- **Codebook** describing all variables, recoding decisions, subgroup classifications, and list experiment treatments.
- **Output files** including model objects (`.rds`), figures (`.pdf`), and tabular outputs (`.csv`), corresponding to manuscript and supplementary results.

> **Note:** Until the publication of the final manuscript, these materials will remain private. If you are an interested researcher seeking access, please contact the corresponding author directly.

## Contact

For questions about the project, replication files, or access to restricted data, please contact:

**Steven Denney**  
Assistant Professor, Leiden University  
s.c.denney@hum.leidenuniv.nl  

