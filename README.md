# Charge-Parity Asymmetry Study

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Physics: LHCb](https://img.shields.io/badge/Physics-LHCb_Open_Data-blue)](https://opendata.cern.ch)

## Overview
This repository documents a personal research project investigating charge-parity (CP) asymmetries in particle decays. The goal is to bridge the gap between theoretical Sakharov conditions for baryogenesis and experimental measurements using the LHCb detector framework.

The project covers:
* **Theory:** CKM matrix complex phases and meson mixing.
* **Software:** Data processing with C++ and CERN ROOT.
* **Analysis:** Statistical fitting and Machine Learning (XGBoost) for signal & background separation.

## Repository Structure
* `/theory/`: Theoretical framework and research into HEP.
* `/cpp/`: C++ source files for histogramming and ROOT macros.
* `/py/`: Python files for data analysis (uproot, pandas, scikit-learn).
* `/paper/`: LaTeX source files and figures for the final report.


## Theory Overview
Still in progress...


## Installation & Setup
To run the analysis locally, you need the CERN ROOT framework and a Python 3 environment.

### Prerequisites
1. **ROOT:** [Installation Guide](https://root.cern/install/)
2. **Python Stack:**
   ```bash
   pip install uproot awkward pandas matplotlib scikit-learn xgboost shap
