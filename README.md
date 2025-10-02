# Melbourne Foot-Traffic → Marketing & Analytics

An end-to-end, reproducible project that turns City of Melbourne pedestrian counts + weather + ABS demographics into a compact **marketing dashboard and playbook** for running a CBD pop-up (e.g., a coffee cart).

<img alt="Dashboard overview" src="web/dashboard_overview.png" width="900">

## What this ships
- A clean, notebook-driven data pipeline (Python, geo-friendly environment)
- A Looker Studio dashboard (traffic × time × weather)
- A small marketing kit: content calendar, UTM builder, lightweight landing page
- A short compliance checklist (APPs, Spam Act, AANA)

## Quickstart
```bash
# Option A (recommended for geo stack)
conda env create -f environment.yml
conda activate melb_foot_traffic

# Option B (venv + pip)
python -m venv .venv && source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
