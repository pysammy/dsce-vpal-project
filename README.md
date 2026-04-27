# Data Science for Computational Experiences – Online Learning Project

This repository contains my work for the UCSC *Data Science for Computational Experiences* course (Spring 2026). The project focuses on understanding early usage patterns that predict whether learners return to and complete an online course.

The main dataset I use is the **Online Learning & Course Consumption** dataset from Kaggle, which summarizes how 500 learners interact with different online learning platforms and courses. Each row corresponds to a single learner and includes variables such as experience level, course type, platform, hours spent per week, course duration, completion status, completion percentage, dropout reason, and satisfaction score.

## Repository structure

The repo is organized to keep analysis and raw data clearly separated:

- `data/` – location for raw data files (for example, the Online Learning & Course Consumption CSV). I treat this as a local storage folder and do not commit large raw files to GitHub.
- `data/data_documentation/` – notes and codebooks describing the dataset and variables.
- `ds1c_documentation/` – analysis notebooks exported from Google Colab (starting with `01_initial_exploration.ipynb` for Assignment 2).
- `.gitignore` – configuration to keep large raw data, notebook checkpoints, and other temporary files out of version control.
- `assignment3/` – Colab notebook for Assignment 3 (VPAL preprocessing pipeline using PersonalityScoresVpal2.csv). 
- `assignment4/` - Colab notebook for Assignment 4

This structure mirrors the project organization discussed in class and is meant to make it easy for someone else to understand where the data lives and how the analysis is laid out.

## Environment and tools

I run the analysis in Python 3 using a Google Colab notebook. The main libraries I rely on are:

- `pandas` and `numpy` for loading and transforming the data
- `matplotlib` and `seaborn` for basic visualizations and exploratory plots

The workflow is:

1. Store the dataset in Google Drive.
2. Mount Drive in Colab and load the CSV into a pandas DataFrame.
3. Perform cleaning, exploration, and modeling in Colab.
4. Periodically download the notebook and save it to the `ds1c_documentation/` folder in this repository.

Anyone who wants to reproduce the analysis can follow the same steps in their own Colab environment, using the same dataset and notebook files in this repo.
