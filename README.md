# Quantum-Inspired Feature Engineering

A research proposal exploring whether simulated quantum feature maps can improve cross-sectional equity return models relative to classical feature transformations.

**Status:** this repository currently contains the proposal only. It does not yet contain datasets, implementation code, notebooks, backtests, or measured results.

## Research question

Do quantum-inspired representations add predictive value after controlling for data leakage, model capacity, transaction costs, and the choice of classical baseline?

## Proposed approach

1. Define a reproducible equity universe, data provenance, and point-in-time factor inputs.
2. Build classical baselines before introducing quantum-inspired transformations.
3. Simulate feature maps with Qiskit and compare them with conventional kernels and nonlinear transformations.
4. Train and evaluate models using time-based splits and a held-out test period.
5. Compare predictive metrics and portfolio results after explicit turnover and cost assumptions.

## Planned repository layout

These directories are planned; they are not present yet.

| Directory | Intended contents |
| --- | --- |
| `data/` | Data documentation and permitted datasets |
| `src/` | Feature transformations, training, and evaluation |
| `notebooks/` | Exploratory experiments |
| `reports/` | Reproducible results and limitations |

## Candidate tools

Python, Polars, Apache Arrow, scikit-learn, XGBoost, and Qiskit. Dependencies and supported versions will be recorded alongside the implementation.

## Next milestones

- [ ] Document the dataset, universe, target, and evaluation protocol.
- [ ] Implement and validate a classical baseline.
- [ ] Add one simulated quantum feature-map experiment.
- [ ] Publish reproducible comparisons, including negative results.

No performance advantage or live trading readiness is claimed at this stage.
