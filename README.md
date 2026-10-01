# Numerical Appendix

This is a self-contained Jupyter notebook that reproduces the numerical results in the paper. Section numbering in the notebook mirrors the section numbering in the paper:

- §0 — Setup (parameters, primitives, helper functions)
- §4.1.1 — First-best
- §4.1.2 — Principal controls spending, effort unobservable
- §4.1.3 — Agent controls spending, both effort and spending unobservable
- §A.1 — Agent controls spending, spending observable and effort unobservable (appendix only)
- §4.2 — Dynamic first-best
- §4.4 — Agent controls spending
- §4.5 — Principal controls spending, agent exerts unobservable effort
- §4.6 — Discussion checks (what the agent would pick under the principal's contract; effort distortion at the same b₁)
- §5.1 — Social planner benchmark
- §6.1 — Robustness in n: the value of money
- §6.2 — Discounting

## Reproducing the results

Clone the repository, install the dependencies, and run the notebook:

```bash
git clone https://github.com/sahmed95/fixed-budget-mh.git
cd fixed-budget-mh
pip install -r requirements.txt
jupyter notebook Fixed_Budget_Appendix.ipynb
```

Alternatively, run end-to-end from the command line:

```bash
jupyter nbconvert --to notebook --execute Fixed_Budget_Appendix.ipynb
```

## Dependencies

Python 3.9 or later, with NumPy, SciPy, pandas, Matplotlib, and Seaborn. Versions are pinned loosely in `requirements.txt`.
