# Simulation & Sequence Analysis

A reproducible Python/Jupyter analysis exploring **performance streaks** using simulation and observational sequence data.
This repo is packaged as a portfolio-style project (clean structure, reproducible environment, and runnable notebook).

## What’s inside

- `notebooks/02_performance_streaks_analysis.ipynb`: final analysis notebook (run this)
- `data/raw/`: input datasets used by the notebook
- `src/performance_streaks/`: optional module space for refactoring reusable functions

## Quick context

The Case of the Hot Hand  

Introduction

This report analyzes the NBA player data from the 2012–2013 season.  
The goal is to determine whether players truly perform better after previous successful shots or if this perception is due to random variation.  

The analysis proceeds in four parts:

1. Regression Analysis (Models A–D):  
   Examine how player performance metrics such as field goals, rebounds, assists, steals, and points (PTS) explain salary differences.  
2. Conditional Probability Test:  
   Compare the probability of making a shot after a previous hit versus a miss to assess short-term streaks.  
3. Streaks (Runs) Simulation:  


## How to run

```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .\.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

Open and **Run All**:
- `notebooks/performance_streaks_analysis.ipynb`

## Reproducibility notes

- Keep datasets in `data/raw/` with the same filenames as committed.
- If you re-run simulations, consider fixing a random seed in the notebook for consistent outputs.

