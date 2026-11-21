# Grocery Inventory Clustering

## Repository layout

- `data/food.csv` - raw dataset
- `notebooks/grocery_inventory_analysis.ipynb` - automated analysis
- `outputs/` - generated figures and tables (created when the notebook runs)
- `requirements.txt` - Python dependencies

## Setup in VS Code

1. Install the Microsoft Python and Jupyter extensions.
2. Open the repository folder in VS Code.
3. In a terminal, create an environment: `python -m venv .venv`
4. Activate it and install dependencies: `python -m pip install -r requirements.txt`
5. Open the notebook and select the `.venv` Python kernel in the upper-right corner.
6. Use **Run All**.

The notebook searches for `food.csv` beside the notebook, in `data/`, or one folder above.
