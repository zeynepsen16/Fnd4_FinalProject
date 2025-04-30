# Fnd4_FinalProject
# Fear Conditioning Data Analysis

This project inestigates the effects of ketamine on different phases of fear conditioning in adult male Wistar rats.

---

##  Scientific Question

How does ketamine effect freezing behavior in fear conditioning when applied before the acquisition, retrieval and extinction phases?

---

##  Repository Structure

- `FC_data.xlsx` — Raw behavioral data (5 sheets for each phase)
- `Foundations4FinalProject.ipynb` — Analysis script
- `README.md` — This file

---

## Analysis Pipeline

1. Load and reshape raw data from Excel
2. Convert data into tall format
3. Visualize raw and group-level trends with error bars
4. Fit linear models (OLS) and perform ANOVA
5. One way ANOVA and post-hoc tests for retrieval phase (Tukey's HSD)

---

## Data Description

The excel file contains 5 sheets corresponding to different phases of fear conditioning,:

acq — Acquisition - 5 cues

ret — Retrieval - single cue

ext1 — Extinction Day 1 - 15 cues

ext2 — Extinction Day 2 - 15 cues

renewal — Renewal - 3 cues

Each sheet has groups and cues column. Cues are represented as freezing percentage during the cue.

---
## Dependencies

- Python
- pandas
- matplotlib
- seaborn
- statsmodels

---

## How to Run

1. Clone this repository
2. Install the required packages
3. `FC_data.xlsx` should be in the working directory
4. Run `Foundations4FinalProject.ipynb`



