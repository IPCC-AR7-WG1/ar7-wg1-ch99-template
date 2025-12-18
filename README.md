Chapter 99
====================================
[![DOI](https://zenodo.org/badge/DOI/YOUR_ZENODO_DOI.svg)](https://doi.org/YOUR_ZENODO_DOI)
![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![GitHub release](https://img.shields.io/github/v/release/YOUR_ORG/YOUR_REPO?logo=github)

## Contents

- [Contents](#contents)
- [Repository Organisation Guidelines](#repository-organisation-guidelines)
  - [Standard Figure Folder Structure](#standard-figure-folder-structure)
  - [General Rules](#general-rules)
- [Folder Naming Conventions](#folder-naming-conventions)
  - [Figure Folder Names](#figure-folder-names)
  - [Naming Rules](#naming-rules)


## Repository Organisation Guidelines

This repository is organized by figure, with one top-level folder per figure.

Each figure folder is fully self-contained and includes the code, metadata, outputs, and citation information needed to reproduce that figure.

### Standard Figure Folder Structure

Each figure directory must follow this structure:

```
figXX_YY/
├── code/ # Scripts or notebooks used to generate the figure
├── data/ # Metadata for input datasets (original data files excluded)
├── figure/ # Generated figure(s)
├── CITATION.cff # Citation information for this figure
└── README.md # Figure description, usage, and citation instructions
```

### General Rules

- **One figure per folder**  
  Do not combine multiple figures in a single directory.

- **Do NOT store large data files**  
  The `data/` folder must contain **metadata only** (e.g. `.yml`, schema files, small samples).  
  Large datasets must be stored in external long-term storage and referenced via links.

- **Reproducibility first**  
  All scripts or notebooks required to generate the figure must be placed in `code/`.

- **Clear attribution**  
  Every figure folder must include a `CITATION.cff` file to ensure proper authorship and citation tracking.


## Folder Naming Conventions

### Figure Folder Names

Use the format: `figXX_YY`

`XX` = two-digit chapter number

`YY` = two-digit figure number within the chapter

Example:

Chapter 1, Figure 3  → `fig01_03`

Chapter 5, Figure 12 → `fig05_12`

Chapter 10, Figure 2 → `fig10_02`

- If the final figure number is not yet known, use a **descriptive temporary name**: fig_XX_<short_descriptive_name> 

Please rename the folder to the final `figXX_YY` format once the figure number is confirmed.

### Naming Rules

- Use lowercase letters
- Use underscores (`_`) instead of spaces or hyphens
- Keep names short, clear, and descriptive
