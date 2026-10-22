# Weather & Supermarket Exploratory Data Analysis

This repository contains two Jupyter Notebooks demonstrating exploratory analysis with pandas and visualizations.

## Projects

### 1. Weather Analysis
[Open Weather Analysis notebook](./Weather%20Analysis.ipynb)

The notebook explores an hourly weather dataset, including DataFrame inspection, filtering by weather conditions, value counts, and grouped summaries for temperature, humidity, wind, visibility, and pressure.

**Reproducibility:** the notebook reads from a Windows-local path (`C:\\Users\\areeb\\Downloads\\Project+1+-+Weather+Dataset.csv.csv`). That file is not included in the repository. Replace the path with a configurable path to a dataset you are permitted to share before rerunning.

### 2. Supermarket Analysis
[Open Supermarket Analysis notebook](./Supermarket%20Analysis.ipynb)

The notebook explores supermarket transactions using pandas and visualizations. Its saved output indicates an input table of 1,000 rows and 20 columns; the notebook also examines missing values and fills or infers some fields.

**Reproducibility:** the notebook reads `supermarket_sales.csv`, which is not present in this repository. Add a licensed/anonymized dataset or document how to obtain it before expecting a fresh checkout to run.

## Local setup

```bash
python -m venv .venv
# Activate the virtual environment for your operating system, then:
python -m pip install -r requirements.txt
jupyter notebook
```

The CSV/XLSX inputs noted below are not included, so supply a permitted dataset and update the notebook input path before running all cells.

## Tools visible in the notebooks
- Python and Jupyter Notebook
- pandas and NumPy
- Matplotlib and Seaborn
- Folium (in the supermarket notebook)

## Data-quality notes
- Review missingness and explain each imputation decision rather than filling values automatically.
- Validate types, categories, duplicates, and assumptions before interpreting results.
- Restart the notebook kernel and run all cells in order to confirm outputs.
- Treat saved notebook output as historical until it has been reproduced against the intended data.

## Scope
These are exploratory portfolio notebooks, not production analytics pipelines. No specific business impact is claimed until calculations and conclusions are verified.
