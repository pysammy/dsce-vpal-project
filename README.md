# dsce-vpal-project
Data Science in Computational Media CMPM-230-01


# Data Science for Computational Experiences – VPAL Project

This repository contains my project for the UCSC *Data Science for Computational Experiences* course (Spring 2026). It uses the VPAL dataset introduced in Session 2 to explore relationships between player behavior and personality measures.

## Structure

- `data/` – location for raw data files (VPAL.zip and extracted CSVs). Raw data is not committed to GitHub.
- `data/data_documentation/` – notes and codebooks describing the variables in the VPAL dataset.
- `ds1c_documentation/` – analysis notebooks (exported from Google Colab), including initial data exploration and later stages.
- `.gitignore` – ensures that large raw data files (e.g., VPAL.zip) are not uploaded.

## Environment

Analysis is done in Python 3 using a Google Colab notebook (pandas, numpy, matplotlib, seaborn). The notebook can be downloaded from Colab and saved in `ds1c_documentation/01_initial_exploration.ipynb`.
