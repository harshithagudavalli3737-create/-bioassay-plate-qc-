# Bioassay Plate-Level QC Analysis System (ELISA & qPCR)

**Author:** Harshitha Gudavalli  
**Degree:** M.S. Biomedical Engineering & Biotechnology  
**Regulatory Standard:** OECD GLP / 21 CFR Part 58  
**Tools:** Python · pandas · SciPy · Matplotlib · openpyxl  

---

## Overview

A GLP-compliant plate QC evaluation pipeline assessing 48 simulated 
ELISA and qPCR plate runs against four GLP acceptance criteria — CV%, 
recovery %, blank OD, and non-specific binding (NSB) — with automated 
pass/fail determination, risk-level assignment, and weekly trend analysis.

---

## What This Project Covers

- CV% evaluation per plate (≤15% acceptance limit)
- Recovery % assessment (80–120% acceptance range)
- Blank OD control evaluation (<0.15 limit)
- Non-specific binding (NSB) control evaluation (<0.20 limit)
- Automated pass/fail determination and risk-level assignment
- Weekly pass rate trend analysis
- Failed plate investigation log
- 3-sheet Excel QC report with risk-coded findings and embedded chart

---

## Regulatory Reference

- OECD GLP Principles
- 21 CFR Part 58 — Good Laboratory Practice
- SOP-QA-BIO-003 Rev. 2

---

## Key Results

- Total plates evaluated: 48
- Overall plate pass rate: 81.2%
- Primary failure driver: Intra-assay CV% (identified via t-test analysis)

---

## How to Run

1. Download `BioassayQC_HGudavalli.ipynb`
2. Go to colab.research.google.com
3. File → Upload notebook → select the file
4. Runtime → Run all
5. Excel report downloads automatically

---

## Dashboard Preview

![Bioassay QC Dashboard](BioassayQC_Dashboard_HGudavalli.png)
