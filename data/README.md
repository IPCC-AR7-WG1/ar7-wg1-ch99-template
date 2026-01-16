# Chapter-level Data Folder

This folder is used **only** when multiple figures share the same dataset or preprocessing workflow. In such cases, the canonical metadata are stored here to **avoid duplication**.

Please create a subfolder for each multi-figure case using the following naming convention:

**figsXX_YY_HH_KK_etc**

- XX: chapter number
- YY, HH, KK, etc: figure numbers

If a figure uses its own independent dataset or preprocessing, all data relevant information should be documented within each figure’s folder instead.

The `data/` folder contains **shared data access instructions and provenance metadata** used in this project. This folder does **not store large datasets**, but provides structured metadata and access information to ensure reproducibility and proper attribution.
