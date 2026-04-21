# 🏥 Clinical Trial DMC Dashboard

A Streamlit-based interactive dashboard for Data Monitoring Committee (DMC) 
review of clinical trial data using SDTM-standard datasets.

## What It Does

- **Enrollment Tab** — subjects by site, screen failures, race distribution
- **Safety Tab** — adverse events by severity, serious vs non-serious AEs, top 10 AEs
- **Laboratory Tab** — mean lab values, count of abnormal results by test

## Data Inputs (SDTM domains)

| File | Domain | Content |
|---|---|---|
| `dm.csv` | DM | Demographics & disposition |
| `ae.csv` | AE | Adverse events |
| `lb.csv` | LB | Laboratory test results |

## How to Run

```bash
pip install -r requirements.txt
streamlit run demodash.py
```

## Tech Stack

Python · Streamlit · Pandas · Plotly · SDTM (CDISC)

## Author

Prafulla Karki — Principal Statistical Programmer | AI/ML Engineer  
15+ years FDA-regulated clinical trials experience
