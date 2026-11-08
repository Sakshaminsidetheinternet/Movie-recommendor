# Movie Recommender

A Python-based movie recommendation project using the TMDB 5000 Movies and Credits datasets.

## Overview

This repository contains a notebook-style/data-processing starting point for building a movie recommendation workflow. The current Python script loads the movie and credits datasets and merges them by title as an initial preparation step.

## Data

- `tmdb_5000_movies.csv` — movie metadata.
- `tmdb_5000_credits.csv` — cast and crew metadata.

The datasets are expected to be present in the repository root when the script is run. Check the dataset source and its licence/terms before redistribution.

## Technology

- Python
- NumPy
- pandas
- CSV-based movie metadata

## Run locally

```bash
git clone https://github.com/Sakshaminsidetheinternet/Movie-recommendor.git
cd Movie-recommendor
python -m venv .venv
# Linux / macOS
source .venv/bin/activate
# Windows PowerShell
# .venv\Scripts\Activate.ps1
pip install numpy pandas
python main.py
```

## Current implementation status

The checked-in `main.py` currently reads and merges the two CSV datasets and begins selecting metadata columns. A complete recommendation function, user interface, hosted demo and recommendation evaluation were not visible in the inspected script. This README intentionally describes it as a data-processing starting point rather than claiming a finished recommender system.

## Demo and screenshots

No live demo or screenshots are currently available in the repository. Once recommendation output is implemented, add an example using a few sample movie titles and a screenshot of the results.

## Author

**Saksham Gupta** — [GitHub](https://github.com/Sakshaminsidetheinternet)
