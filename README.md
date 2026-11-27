# Data Cleaning Bootcamp

**Guided data science coursework & practical notebooks** · Python · NumPy · pandas · Matplotlib · Seaborn

This repository collects the foundational exercises I practiced while learning Python for data science. It focuses on programming, numerical computing, tabular data manipulation and visualization.

**Scope and ownership:** These are guided learning exercises, not independently designed projects.

## Topics

| Area | Contents |
| --- | --- |
| [Python](python/) | Control flow, functions, exceptions, map, filter and lambda expressions |
| [NumPy](numpy/) | Arrays, indexing, numerical operations and practice exercises |
| [pandas](pandas/) | DataFrames, filtering, aggregation, joins and tabular data manipulation |
| [Data visualization](data_visualization/) | Matplotlib and Seaborn exercises |

## Related studies

The overlapping EDA and cleaning notebooks have been consolidated into their dedicated repositories:

- [Exploratory Data Analysis](https://github.com/sremresimsek/exploratory-data-analysis) — MPG and Wine Quality
- [Feature Engineering & Cleaning](https://github.com/sremresimsek/feature-engineering-and-cleaning) — Cafe Sales and Titanic
- [Data Preprocessing](https://github.com/sremresimsek/data_preprocessing) — missing values, outliers and transformations

## Getting started

1. Create and activate a Python virtual environment.
2. Install dependencies: `python -m pip install -r requirements.txt`.
3. Open Jupyter: `python -m jupyter notebook`.
4. Run each notebook from its own directory so relative dataset paths resolve correctly.

## Data and reproducibility

The notebooks were run locally during the cleanup using Python 3.12. Dependency versions are not locked, so results may vary in other environments. See [DATA_SOURCES.md](DATA_SOURCES.md) for dataset provenance and privacy limitations.
