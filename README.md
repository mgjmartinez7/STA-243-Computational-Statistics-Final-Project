# XTrace & XNysTrace: Optimal Stochastic Trace Estimation

Final project for STA 243 (UC Davis, Spring 2026) — a review and 
reproduction of the XTrace and XNysTrace stochastic trace estimators, 
which improve on Girard-Hutchinson and Hutch++ by preserving the 
exchangeability principle via leave-one-out symmetrization.

**Authors:** Aaron Guerra, Matthew Martinez, Tommy Yu, Danny Kuei

## Contents
- [Presentation slides](docs/STA243_Presentation.pdf)
- [Full report](docs/STA_243_Report.pdf)

## Summary
- Reproduces the spectral simulation experiments from the original 
  XTrace/XNysTrace paper (flat, polynomial, exponential, and step 
  eigenvalue spectra)
- Extends the analysis to graph-based trace statistics 
  (tr(M⁴), Estrada index) on simulated ER, SBM, and Barabási–Albert 
  networks
- Includes variance bound derivations and proof summaries for all 
  three estimators (Hutch++, XTrace, XNysTrace)
