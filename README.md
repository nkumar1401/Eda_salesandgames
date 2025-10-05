# 🕹️ Video Game & Global Sales Analytics Pipeline

## Overview
End-to-end automated pipeline for cleaning, transforming, and loading video game and global sales data using Python, pandas, and MySQL in an enterprise-compliant workflow. Suitable for analytics, BI, and reporting tooling.

---

## Solution Features
- Automated import and cleaning of game/sales CSVs
- Industry-level handling of missing values, invalid dates, and numeric coercion
- Composite key enforcement at DB level for full data integrity
- Modular ETL scripts, ready for team handoff and CI/CD
- Analytics-ready tables for BI/dashboarding platforms

---

## Project Structure
raw data/
eda_salesandgames.ipynb
.env.example # Template for DB secrets
README.md # This file
requirements.txt # Dependency list


---

## Setup Instructions
1. Clone the repo
2. Copy `.env.example` to `.env` and configure as:


- All insertions are error-handled and logged for traceability

---
##Quick Start: Project Installation
step 1- git clone <your_repo_url>
cd <project_folder>

step 2-
python -m venv venv
# On Mac/Linux:
source venv/bin/activate
# On Windows:
venv\Scripts\activate

step3- Install all required Python packages
pip install -r requirements.txt



## Best Practices
- No secrets in repo—use `.env` for credentials
- Modular, documented scripts for collaborative extensibility
- Data constraints and ETL rules match BI/business requirements

---

## Authors
Nirmal Kumar  
Python Developer, Data Analytics, Pune MH

---

## License
MIT License
