# Fnd4_FinalProject
# Fear Conditioning Data Analysis

This project analyzes freezing behavior in rodents across different phases of fear learning (Acquisition, Retrieval, Extinction1, Extinction2, Renewal) under different ketamine treatment conditions.

---

## 🧪 Scientific Question

How does ketamine affect the acquisition, retrieval, extinction, and renewal of conditioned fear in rodents?

---

## 📁 Repository Structure

- `FC_data.xlsx` — Raw behavioral data (5 sheets for each phase)
- `final_project_analysis.py` — Main analysis script
- `README.md` — This file

---

## 🧠 Analysis Pipeline

```text
Raw Excel data (.xlsx)
     ↓
Convert to tall (long) format using `pandas.melt()`
     ↓
Raw data visualization (line plots or bar plots)
     ↓
Linear model fitting (OLS)
     ↓
ANOVA and post-hoc testing (statsmodels + Tukey HSD)
     ↓
Publication-ready figures
