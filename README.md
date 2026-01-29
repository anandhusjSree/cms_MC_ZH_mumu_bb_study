# CMS-style MC Invariant Mass reconstruction

This repository contains an educational analysis implemented in a single
Jupyter notebook using class-based programming to study invariant mass
distributions for:

- Z → μ⁺μ⁻
- H → b b̄

The analysis uses Monte Carlo (MC) simulation and CMS-style plotting tools.

## File structure
- 'mu_and_Jet_check.ipynb': Exploratory notebook used to inspect the ROOT file structure, validate branches, and produce basic kinematic sanity plots (pT, η, φ) for muons and jets.
- `ZH_mumu_bb.ipynb`: Main analysis notebook focusing on the ZH → μ⁺μ⁻ b\bar{b} channel, including event selection and physics analysis.
- `figures/`:  Directory containing output plots generated during exploration and analysis.

## Disclaimer
This work is **unofficial and for educational purposes only**.
It is not affiliated with or endorsed by the CMS Collaboration.

## Tools
* Python
* Uproot
* coffea
* awkward array
* numpy
* hist
* mplhep
* matplotlib
