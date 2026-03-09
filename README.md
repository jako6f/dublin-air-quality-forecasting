# Dublin Air Quality Forecasting

This repository contains the working materials for a Trinity College Dublin MSc group project for the module *Intro to Machine Learning*. The project focuses on forecasting next-day air pollution in Dublin, with particular emphasis on PM2.5, using Google Air View measurements alongside weather data. The repository is intentionally lightweight so the team can collaborate without unnecessary tooling or overhead.

## Research Question

Can we use historical air pollution and weather data to forecast next-day PM2.5 levels in Dublin with a simple, reproducible machine learning workflow?

## Repository Structure

```text
dublin-air-quality-forecasting/
├─ README.md
├─ .gitignore
├─ environment.yml
├─ data/
│  ├─ raw/
│  ├─ external/
│  └─ processed/
├─ notebooks/
│  └─ dublin_air_quality_forecasting.ipynb
├─ reports/
│  └─ figures/
└─ refs/
   └─ brief_and_notes/
```

## Setup

1. Clone the repository using GitHub Desktop or `git clone git@github.com:jako6f/dublin-air-quality-forecasting.git`.
2. Create the conda environment:
   ```bash
   conda env create -f environment.yml
   conda activate dublin-air-quality-forecasting
   ```
3. Launch JupyterLab or Notebook from the repository root.
4. Open `notebooks/dublin_air_quality_forecasting.ipynb`.

## Working Workflow

If using GitHub Desktop:
- Fetch and pull the latest changes before starting work.
- Open the repository locally and make edits.
- Review changed files, write a clear commit message, and push to GitHub.

If using Git:
- Run `git pull` before starting work.
- Make your changes, then commit with a short descriptive message.
- Push your branch or updates to GitHub when your work is ready.

## Project Notes

- All analysis code for this project lives in a single notebook: `notebooks/dublin_air_quality_forecasting.ipynb`.
- Store original datasets in `data/raw/` and do not modify them directly.
- Use `data/external/` for third-party source files and `data/processed/` for cleaned or derived datasets.
- Save charts and exported visuals in `reports/figures/`.

## Team Conventions

- Pull the latest version of the repository before starting work.
- Use clear, professional commit messages.
- Do not overwrite or silently replace each other's work.
- Keep the notebook runnable from top to bottom so collaborators can reproduce the analysis.
