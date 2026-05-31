# Data Science Labs

## Overview

This repository is a central study laboratory for data analysis, statistics, data science, and machine learning. The materials are learning labs and practical exercises, not production-ready professional projects.

Existing notebook content was preserved without modification.

## Structure

```text
notebooks/
├── pandas/
├── numpy/
├── statistics/
├── visualization/
├── machine-learning/
└── deep-learning/
datasets/
└── numpy/
```

## Available Studies

### Pandas

[`notebooks/pandas/tratamento_enem_2019.ipynb`](../../notebooks/pandas/tratamento_enem_2019.ipynb) is a study lab for ENEM 2019 microdata treatment and initial exploration with pandas and NumPy.

The notebook depends on an external `microdados_enem_2019_sp.csv` file that is not versioned in this repository.

### NumPy

[`datasets/numpy/`](../../datasets/numpy/) contains supporting datasets for NumPy studies:

- `apples_ts.csv`
- `bytebank.csv`
- `citrus.csv`

The files were reorganized without content changes.

### Prepared Areas

Directories are available for future labs in statistics, visualization, machine learning, and deep learning.

## Running the Labs

```bash
pip install -r requirements.txt
jupyter notebook
```

Run notebooks from the repository root and check whether a lab requires external datasets.

## Guidelines

- Classify notebooks by their main learning topic.
- Keep notebooks as study records.
- Do not invent results or conclusions.
- Do not commit sensitive datasets, credentials, or local files.
- Document external dependencies required to reproduce a lab.
