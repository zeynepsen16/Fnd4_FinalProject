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

1. Load the raw data from Excel
2. Convert data into tall format and make cues at strings
3. Visualize raw and group-level trends with error bars
4. Fit linear, logarithmic, and exponential models to the dataset and compare their performance using Akaike Information Criterion (AIC) and perform ANOVA. (except retrieval)
5. One way ANOVA and post-hoc tests for retrieval phase (Tukey's HSD) (for retrieval)

---

## Data Description

The excel file contains 5 sheets corresponding to different phases of fear conditioning,:

acq — Acquisition - 5 cues

ret — Retrieval - single cue

ext1 — Extinction Day 1 - 15 cues

ext2 — Extinction Day 2 - 15 cues

renewal — Renewal - 3 cues

ext1_ITI - Extinction Day 1 with the time between cues (ITIs)

ext2_ITI - Extinction Day 2 with the time between cues (ITIs)

Each sheet has groups and cues column. Cues are represented as freezing percentage during the cue.

 PS: Please acknowledge that in here the ITI is used wrong. In the literature the ITI (Inter-Trial Interval) is defined as the time between from ONSET of one cue to ONSET of the next cue. While in here it is used as from OFFSET of one cue to ONSET of the next one.

---
## Dependencies

- Python
- pandas
- matplotlib
- seaborn
- statsmodels
- numpy

---

## How to Run

1. Clone this repository
2. Install the required packages
3. `FC_data.xlsx` should be in the working directory
4. Run `Foundations4FinalProject.ipynb`



