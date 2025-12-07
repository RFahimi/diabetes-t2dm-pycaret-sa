# T2DM Prediction, Focused on South Africa with PyCaret

This repository contains:

- `Untitled2.ipynb`: Jupyter notebook with full preprocessing, modelling, and evaluation.
- `df_t2dm.csv`: Dataset used in the notebook.
- `diabetes_model_sa.pkl`: Final Random Forest model trained using PyCaret.

## How to run

1. Create a conda environment with Python 3.10
2. Install PyCaret: `pip install pycaret[full]`
3. Open the notebook in JupyterLab or Jupyter Notebook and run all cells.


### To recreate the environment:

```bash
conda env create -f pycaret_diabetes_env.yml
conda activate pycaret310
