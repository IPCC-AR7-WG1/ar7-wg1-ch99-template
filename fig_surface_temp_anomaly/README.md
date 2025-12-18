FIGURE TITLE
====================================
[![DOI](https://zenodo.org/badge/DOI/YOUR_ZENODO_DOI.svg)](https://doi.org/YOUR_ZENODO_DOI)
![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![GitHub release](https://img.shields.io/github/v/release/YOUR_ORG/YOUR_REPO?logo=github)

Figure X.X  From the IPCC Working Group I Contribution to the Seventh Assessment Report: Chapter X

![Figure caption](<REPLACE_WITH_YOUR_IMAGE_PATH>)

Example: 

Figure 3.4  From the IPCC Working Group I Contribution to the Sixth Assessment Report: Chapter 3
![Figure caption](/figure/ar6_wg1_chap3_figure3_4_surface_temp_anomaly.png?raw=true)

## Contents

- [Contents](#contents)
- [Description](#description)
- [Installation](#installation)
- [Expected image path](#expected-image-path)
- [How to cite](#how-to-cite) 
  - [Figure Citation](#figure-citation)
  - [Repository Citation](#repository-citation)
- [Disclaimer](#disclaimer)


## Description

Write a clear, concise, and self-contained description of the figure:

- What does the figure show?

- What datasets/models are used?

- What time period does it cover?

- Any important features or highlights?


## Installation

example:

1. Clone the repository

```bash
git clone https://github.com/YOUR_ORG/YOUR_REPO.git
cd YOUR_REPO
```

2. Create the environment

```bash
conda env create -f environment.yml
```
This will create a new conda environment with the name defined in the environment.yml file (e.g., ipcc-fig-env).

3. Activate the environment

```bash
conda activate ipcc-fig-env
```

4. Run the figure generation pipeline

......


## Expected image path

Provide the expected output file paths from the tool's run:

- Include multiple paths if the figure has multiple sub-panels.

example:
- recipe_ipccwg1ar6ch3_atmosphere_YYYYMMDD_HHMMSS/plots/fig_3_4_cmip5/fig-3-4/gsat_Global_CMIP5_historical-rcp45_anom_1850-2020.eps
- recipe_ipccwg1ar6ch3_atmosphere_YYYYMMDD_HHMMSS/plots/fig_3_4_cmip6/fig-3-4/gsat_Global_CMIP6_historical-ssp245_anom_1850-2020.eps
- recipe_ipccwg1ar6ch3_atmosphere_YYYYMMDD_HHMMSS/plots/fig_3_4_collect/collect/gsat_Global_multimodel_anom_1850-2020.eps


## How to cite

If you use this repository or any of its contents in your work, please cite it appropriately.

### Repository Citation
This repository includes a `CITATION.cff` file for citation. You can generate a citation in your preferred format using:

```bash
cffconvert --format bibtex
```

### Figure Citation
If you use Figure <figure number eg 3.4> from the IPCC report included in this repository, please cite it as:

Provide a full citation of the IPCC report chapter containing the figure, according to the IPCC editorial citation rules.


## Disclaimer
Please note that figures in this repository may differ from those in the published version due to the editorial process. The repository contains the latest available versions prior to publication.


# 🟡Checklist Before Finalizing (delete when you complete the README.md)

- Updated title and badges

- Correct figure number and chapter

- Real image path and preview

- Descriptive summary in the Description section

- Image output paths match the real output

- At least one scientific source listed

- Figure and repository citation are accurate
