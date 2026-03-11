[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/FdVrU54p)
# m1-l1-git-workflows-alialquraan


---

## Team Members 
Ali Alquraan ,Ibrahim almomani,omar , sara ,Mohannad,mousa.

> 

## Project Overview

This project establishes a reproducible environment for a three-person team to analyze hospital admission records. It uses a virtual environment and a standardized requirements.txt to ensure the setup can be launched in under two minutes.

---

## Data Sources 

This project utilizes historical hospital admission records including patient demographics, diagnosis codes, and length of stay.

Note: Data is not tracked in this repository. See the setup instructions below for how to obtain and place the data files before running any analysis.

---

## Setup Instructions

git clone [<repo-url>](https://github.com/LevelUp-Applied-AI/m1-l1-git-workflows-alialquraan.git)

cd m1-l1-git-workflows-alialquraan

python -m venv .venv

---

## Project Structure 

m1-l1-git-workflows-alialquraan
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

Branch Naming: Use descriptive prefixes for branches:

feature/ for new features.

setup/ for environment or configuration changes.

fix/ for bug fixes.

integration/ for merging different parts of the project.

Pull Requests (PR): All changes must be submitted via a PR. Ensure your code passes test_environment.py before submitting.

Commit Messages: Keep messages concise and descriptive

---

*Starter file for Lab 1 — lab-1-git-workflows | aispire-14005*