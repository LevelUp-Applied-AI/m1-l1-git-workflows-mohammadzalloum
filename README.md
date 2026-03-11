[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/FdVrU54p)
# [Hospital Admission Records Analysis]

---

## Team member
mohammad
maher
salman
---
## Project Overview
This project prepares the hospital admission data repository so any new teammate can quickly clone and run it without extra help. It solves setup and collaboration issues by adding clear documentation, automated environment setup, and contribution guidelines. The result is a ready-to-use repository with a README, setup.sh, .gitignore, AGENTS.md, and CHANGELOG.md.
---
## Data Sources
Data is not tracked in this repository. See the setup instructions below
for how to obtain and place the data files before running any analysis.
---

## Setup Instructions

TODO: Complete these setup steps after creating your `requirements.txt`:

```bash
python -m venv .venv

# Activate — choose the command for your OS:
# Mac / Linux:      source .venv/bin/activate
# Windows Git Bash: source .venv/Scripts/activate
# Windows CMD:      .venv\Scripts\activate.bat
# Windows PowerShell: .venv\Scripts\Activate.ps1

pip install -r requirements.txt
python test_environment.py    # should print "Environment OK"
```

---

## Contributing

- Branch naming: `setup/`, `feature/`, `fix/`
- Open a PR to `main` for all changes
- Commit messages: imperative mood, ≤ 50 characters

---

## Contributing
project-name/
├── README.md             — Project overview and setup instructions
├── CHANGELOG.md          — Record of notable changes
├── AGENTS.md             — AI contribution policy
├── requirements.txt      — Python dependencies
├── setup.sh              — Automated environment setup script
├── test_environment.py   — Environment validation
├── .gitignore            — Files excluded from version control
├── src/                  — Production source code (importable modules)
├── notebooks/            — Exploratory analysis notebooks
├── data/                 — Data directory (contents not committed to Git)
│   └── raw/              — Original unmodified data files
└── tests/                — Automated tests
---

*Starter file for Lab 1 — lab-1-git-workflows | aispire-14005*