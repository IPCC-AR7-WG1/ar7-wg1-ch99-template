# Environment Folder README

The `env/` folder contains environment specification files and documentation necessary to **recreate the software environment** used in this project. This ensures that analyses and figures can be reproduced reliably across different systems.

Recommended configuration files include, but are not limited to:

- **Python:** `environment.yml`, `requirements.txt`
- **R:** `install.R`, `DESCRIPTION`, `renv.lock`
- **Makefile:** Optional automation for environment setup, package installation, or other routine tasks.
- **Other tools:** Any additional configuration files required for reproducible builds

For an overview of commonly supported configuration files for reproducible builds, see the [repo2docker documentation](https://repo2docker.readthedocs.io/en/latest/configuration/#config-files).