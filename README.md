# On the (In)feasibility of ML Backdoor Detection as an Hypothesis Testing Problem

Jupyter notebooks used in our paper "On the (In)feasibility of ML Backdoor Detection as an Hypothesis Testing Problem"

## Installation
Use 
```bash
poetry install --no-root
poetry run jupyter lab
```
to install the poetry requirements and run Jupyter Lab. This was tested with Python 3.11 and 3.12.

## Example in Section 2.2.1

The Jupyter notebook [impossibility_example.ipynb](impossibility_example.ipynb) can be used to obtain Figures 1 and 2. These are exported to
[impossibility_example.pgf](impossibility_example.pgf) and [impossibility_hist.pgf](impossibility_hist.pgf), respectively. All parameters and the p-value resulting
from the K-S test are written to [impossibility_example_values.tex](impossibility_example_values.tex).

## Lower Bounds in Table 2

The Jupyter notebook [sizes.ipynb](sizes.ipynb) can be used to produce Table 2. The table is exported to [datasets_df.tex](datasets_df.tex), while $\alpha$ and $\beta$
are written to [datasets_df_values.tex](datasets_df_values.tex).

