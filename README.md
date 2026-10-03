# Numerical Methods and Optimisation Foundations

AIMS course materials and completed exercises in numerical computing, linear algebra, interpolation and iterative methods.

## Main assignment

[Assignment_Week_Numerical_Optimization.ipynb](Assignment_Week_Numerical_Optimization.ipynb) covers:

- Numerical differentiation and Newton root finding.
- Singular matrices and ill-conditioning.
- Polynomial fitting and residual analysis.
- Lagrange interpolation and cubic splines.
- Weighted Jacobi iteration and residual comparisons across relaxation parameters.

The repository also contains introductory Python and NumPy course notebooks, exercises and provided solutions.

## Environment and data

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter notebook
```

The seismic interpolation exercise reads `shot.txt`, which is absent from the repository. The assignment text refers to `data/shot.txt`, while the code reads `shot.txt` from the working directory. Recover the original file and reconcile these paths before running that exercise.

Some introductory notebooks deliberately demonstrate Python errors. A fresh-kernel verification of the completed numerical assignment remains to be recorded.

## Attribution

The course notebooks credit **Dr Yae GABA, Dr Aurelle TCHAGNA and Mr Dominique LEKO**. This repository contains training materials and exercise work in Thierry Kuate Mabap's academic portfolio. It should be read with the original instructional attributions.

For a separate applied optimisation project, see [African airline route planning](https://github.com/Thierrykuatemabap/Optimal_Airline_Route_Planning_final_project).
