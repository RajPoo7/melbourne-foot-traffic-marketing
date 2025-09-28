# Melbourne Foot‑Traffic → Marketing & Data Analytics (AU‑standard)

Author: **Poojith Raj**  
Last updated: 2025-09-28

An end‑to‑end, portfolio‑ready project that turns **City of Melbourne pedestrian counts + weather + ABS demographics**
into an **AU‑compliant marketing dashboard** and **playbook** for a hypothetical CBD pop‑up (e.g., coffee cart).

## Highlights
- Reproducible data pipeline (Python + notebooks)
- Looker Studio dashboard (traffic × weather × events)
- Marketing ops: content calendar, UTM plan, GTM event tagging
- AU compliance checklist (APPs, Spam Act, AANA)

## Quickstart
```bash
# Option A: Conda (recommended for Geo stack)
conda env create -f environment.yml
conda activate melb_foot_traffic

# Option B: venv + pip (lightweight; geo libs may be harder to install)
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Then open Jupyter and follow the notebooks in order (`01_...` to `05_...`).

## Repo layout
```
data/                  # raw/interim/processed (raw is gitignored)
notebooks/             # 01..05 project notebooks
analytics/looker_studio_datasources/
marketing/             # calendar, UTMs, creative
ops/                   # compliance, SOPs, risk register
web/                   # static landing page + GTM instructions
scripts/               # CLI helpers (download/merge)
tests/                 # basic schema tests
```
