# Nature vs. Nurture in Student Scores

> Exploratory analysis of 30,000 student records and what drives academic performance.

## Overview

- Introduction to Data Science group project (4 members) asking whether family background and environment matter as much as innate traits.

## Data / Scope

- 30,000-row student dataset with Math, Reading and Writing scores and background factors such as parental education.

## Workflow

- Explored the data with correlation heatmaps, violin and box plots, and grouped bar charts.
- Used SciPy hypothesis tests to check whether differences were meaningful rather than noise.
- Compiled findings into an academic research poster.

## Results

- Math, Reading and Writing scores are strongly correlated with each other.
- Parental education visibly shifts the math score distribution, a clear nurture signal.
- Findings presented visually for an academic audience.

## Tech Stack

Python, pandas, seaborn / matplotlib, SciPy, Hypothesis testing

## Repository Structure

```
notebooks/          Exploratory data analysis notebook
data/               Student exam scores dataset (anonymous records)
docs/               Project poster
```

## How to Run

```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
jupyter notebook notebooks/AOL_ITDS_EDA.ipynb
```
Run from the repository root so the data path resolves.

## Team

Introduction to Data Science course project by Ann, Ivana, Nadya and Vania (LA06).

## Notes

- The dataset contains anonymous exam records only (no names).

## Author

Nadya Angelie Lislie, BINUS University (Computer Science and Statistics). [LinkedIn](https://www.linkedin.com/in/nadya-angelie-lislie/) | [GitHub](https://github.com/Nadya-AngelieLislie)

## Continuous Integration

GitHub Actions (`.github/workflows/ci.yml`) runs `ruff` and `pytest` repository-health checks on every push; run them locally with `make lint test`.
