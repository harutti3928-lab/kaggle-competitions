# Kaggle Competitions

## Repository overview

A workspace for Kaggle competition experiments, solutions, and machine learning practice. Each competition has its own notebooks and experiment notes.

## Learning objectives

- Build reproducible baselines and compare them with stronger models.
- Practice validation, error analysis, and experiment tracking.
- Apply classical models to tabular data, CNNs to image classification, Transformers to NLP, and generative models when the task calls for them.

## Repository structure

- `competitions/titanic/` contains the first competition workspace.
- `01_eda.ipynb`, `02_baseline.ipynb`, and `03_models.ipynb` cover exploration, the baseline, and model comparisons.
- `data/` and `submissions/` hold local downloads and predictions.
- `shared/` is for code reused across competitions.

## Competition progress

| Competition | Task | Status | Best validation score | Best Kaggle score |
| --- | --- | --- | --- | --- |
| [Titanic](competitions/titanic/) | Binary classification | Workspace ready | | |

## Development environment

Use Python 3.12 and VS Code with the Python and Jupyter extensions. The starter notebooks contain Markdown only. Add modeling dependencies once an experiment needs them.

## How to get started

Run the following in PowerShell from the repository root.

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install ipykernel
```

Open the repository in VS Code and select the `.venv` kernel. Follow the [Titanic README](competitions/titanic/README.md) to obtain the data and begin with `01_eda.ipynb`.
