# PV_Module_Frame

Code and data for "Robust multi-objective optimization of large-scale photovoltaic module frames using uncertainty-aware deep ensembles."

## Files
- `240205_pvmodule_rawdata.csv` — 243 full-factorial FEA results (deflection, weight)
- `260526_PV_module_UDE.ipynb` — uncertainty-aware deep ensemble surrogate
- `SHAP.ipynb` — global interpretability (SHAP)
- `BO_const.ipynb`, `DE_const.ipynb`, `PSO_const.ipynb` — metaheuristic optimization
- `BO_w_5_10_20_50.ipynb` etc. — weight sensitivity analysis
- `BO_Pareto_1.ipynb` — Pareto front analysis
- `requirements.txt` — Python dependencies

## Usage
Run on Python 3.10.10 Install dependencies with `pip install -r requirements.txt`.
