# Source Code Folder README

The `src/` folder contains **shared, reusable code** used across multiple figures and analyses in this project. This includes:

- Base functions
- Reusable data processing or analysis routines
- Plotting helpers and visualization utilities

Code in `src/` is intended to be **imported or called from figure-level scripts** (e.g., `figXX_YY/`) rather than duplicated in each figure folder. Maintaining canonical shared code in `src/` ensures consistency, avoids duplication, and simplifies maintenance.