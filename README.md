# Identifying Key Metadata Predictors of *Salmonella* AMR Genotypes through Machine Learning

> **MADA Course Project** | [University of Georgia, Department of Poultry Science](https://poultry.caes.uga.edu/)  
> 👤 [Marco Reina](https://github.com/reinaantillon) • 📅 Spring 2026

Manuscript available in docx in main page. \

[Web manuscript available here](https://reinaantillon.github.io/marcoreina-MADA-project/products/manuscript/manuscript-web.html)

---

## Project Overview

This project applies machine learning techniques to identify key metadata predictors associated with antimicrobial resistance (AMR) genotypes in *Salmonella* isolates from poultry sources. Understanding these predictors supports food safety surveillance and targeted intervention strategies in poultry production systems.

### Research Question
1. Which metadata features (e.g., source, geography, year, serotype) best predict AMR genotypes in *Salmonella*?


## Repository Structure
Each qmd file starts with a number that indicates its sequential order. <br>
Please execute the files following that sequence (e.g. "01" first, followed by "02", etc.) \

Main structure \
├── code/ # Analysis scripts and workflows (ordered)\
│ ├── eda-code/ # Exploratory data analysis scripts\
│ │ └── 01_eda \
│ ├── analysis-code/ # Descriptive + modeling analysis \
│ │ └── 02_descriptive-analysis \
│ │ └── 03_model-fitting \
│ │ └── 04_random-forest \
│ │ └── 05_cross-validation \
│ │ └── 06_logistic-regression \
│ \
├── data/ # Project datasets \
│ ├── raw/ # Original data (unaltered) \
│ └── processed/ # Cleaned and analysis-ready datasets \
│ \
├── docs/ # Rendered Quarto website files (auto-generated) \
│ \
├── results/ # Outputs from analysis \
│ ├── figures/ # Plots and visualizations \
│ ├── tables/ # Summary tables \
│ \
├── products/ # Final project deliverables \
│ └── manuscript/ # Manuscript outputs \


# Contributing & Peer Reviews
This project was developed as part of the MADA course with peer feedback: \
- Riley Herber\
- Elle Adams\
- Sarra Aljawad\
