# Week 7 starter

Practice repository for **Week 7: Regression Discontinuity**.
Full instructions: <https://yoonismo.github.io/causal-computing/week7.html>

## What is in here

| File | Purpose |
|---|---|
| `week7.ipynb` | The code from the Week 7 page, in the same order |
| `requirements.txt` | The packages the automatic check installs |
| `.github/workflows/ci.yml` | The automatic check: runs the notebook on GitHub's computer after every push |

## Before you start

Week 7 also uses `rdrobust` (RD estimation) and `rddensity` (the density test). Activate the course environment and install the packages (this works from any folder, and the ones you already have are skipped):

```bash
source ~/ECON481/.venv/bin/activate      # macOS
~\ECON481\.venv\Scripts\activate          # Windows (PowerShell)
uv pip install pandas causaldata statsmodels matplotlib linearmodels rdrobust rddensity
```

Run only the `activate` line for your system. `rddensity` also installs `lpdensity`, which Lab 9 uses.

The election data come with the `causaldata` package. The scholarship data in Lab 8 are downloaded from GitHub when you run that cell, so you need an internet connection for Lab 8.

## Steps

1. Click **Use this template** → **Create a new repository**, then clone your copy to your computer, as in Week 1 Lab 3.
2. Run `week7.ipynb` in order along with the Week 7 page, and answer the questions in it.
3. Clear all outputs, then `git add`, `git commit` and `git push`. The **Actions** tab should turn green.
