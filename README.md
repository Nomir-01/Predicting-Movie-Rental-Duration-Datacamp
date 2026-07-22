# Predicting Movie Rental Duration

A regression project that predicts how long a customer will rent a movie. The notebook prepares the rental data, compares linear and tree-based approaches, tunes model parameters, and selects the model with the lowest test error.

## Workflow

1. Explore and clean the rental dataset.
2. Create training and test datasets.
3. Establish linear and regularized regression baselines.
4. Train decision-tree and random-forest regressors.
5. Tune model parameters with grid search.
6. Compare models using mean squared error.

## Tools

- Python
- pandas and NumPy
- scikit-learn
- Jupyter Notebook

## Repository contents

- `notebook.ipynb` — feature preparation, model training, tuning, and evaluation
- `rental_info.csv` — movie rental data
- `dvd_image.jpg` — project cover image
- `requirements.txt` — Python dependencies

## Run locally

```bash
python -m venv .venv
python -m pip install -r requirements.txt
jupyter lab notebook.ipynb
```

## Project context

This is a personal learning project completed as guided DataCamp coursework. It demonstrates regression baselines, tree-based models, hyperparameter search, and test-set comparison using a consistent error metric.
