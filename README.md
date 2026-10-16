# AtmosEleC - Publication Figures & Analysis

Python scripts to generate publication figures, Lerwick Observatory historical time series (1927–1956), and citizen science classification analyses for the AtmosEleC project.

---

## Overview

This repository contains the visualization and analytical scripts used in the study:

> **"Digitization of Historical Atmospheric Electricity Records from Lerwick Observatory (1927–1956) using Citizen Science"**  
> *Authors:* Hripsime Mkrtchyan [et al.]  
> *Data Processing Pipeline:* [https://github.com/hripsime-mkrtchyan/AtmosEleC](https://github.com/hripsime-mkrtchyan/AtmosEleC)

These scripts load the processed database assembled from the AtmosEleC Zooniverse project classifications and generate the publication-ready figures presented in the manuscript.

---

## Script Descriptions

* **`figures_for_paper.py`**: Generates the primary manuscript figures, summary comparisons, and distribution plots reported in the study.
* **`graphes_for_1927-1956.py`**: Constructs historical time-series plots and visualizations of atmospheric potential gradient and electrical parameters recorded at Lerwick Observatory between 1927 and 1956.
* **`user_classification.py`**: Analyzes citizen scientist engagement and volunteer classification patterns.

---

## How to Run

Ensure Python 3 is installed along with standard dependencies (`pandas`, `numpy`, `matplotlib`):

```bash
# 1. Generate core manuscript figures
python figures_for_paper.py

# 2. Generate historical Lerwick Observatory (1927–1956) time series
python graphes_for_1927-1956.py

# 3. Generate volunteer classification and consensus analysis
python user_classification.py
