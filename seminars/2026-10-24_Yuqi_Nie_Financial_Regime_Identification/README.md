# Financial Regime Identification and Regime-Aware Factor Allocation

**FinHorizons Seminar 02**

- **Speaker:** Yuqi Nie, Princeton University
- **Date:** Saturday 24 October 2026, 17:00 BST (09:00 PT), online on Zoom
- **Recording:** [YouTube](https://www.youtube.com/watch?v=JQj_lxEm-sk)
- **Slides:** [PDF](./Yuqi_Nie_Financial_Regime_Identification_and_Regime_Aware_Factor_Allocation.pdf) (deck title: *Financial Regime Analysis: From Statistical Jump Models to Deep Generative Models*)

## Abstract

Market regimes shape both risk and return, yet identifying them reliably from financial time series remains difficult: classical statistical methods are interpretable but rigid, while deep generative models are expressive but hard to trust. This talk presents a generalized Mixture-VAE framework that brings structured probabilistic priors into the latent space of a variational autoencoder and enforces temporal regularity through a rigorously derived state loss. It establishes a theoretical connection between the penalty terms of statistical jump models and the regularization in the Mixture-VAE, and shows on synthetic and intraday S&P 500 data that the approach outperforms existing regime identification methods. The talk then turns to what regimes are for: a regime-aware multifactor allocation that fits a two-state jump model to each equity factor, selects features optimally instead of assuming stationarity, and delivers stronger portfolios than regime-agnostic and static alternatives across six equity factors.

## About the speaker

Yuqi Nie received his PhD and MA in Electrical and Computer Engineering from Princeton University in 2025, and his BS with honors from Peking University in 2020. He is a recipient of Princeton's Francis Robbins Upton Fellowship. His research spans artificial intelligence, time-series analysis and finance, with publications in ICLR, the IEEE Journal on Selected Areas in Communications and The Journal of Portfolio Management; his work has been cited more than 10,000 times.

## Papers

1. *Deep generative models meet statistical methods: a generalized framework for financial regime identification.* Annals of Operations Research, 2026. [Publisher](https://link.springer.com/article/10.1007/s10479-026-07041-z)
2. *Regime-Aware Factor Allocation with Optimal Feature Selection.* The Journal of Financial Data Science, 2024. [DOI](https://doi.org/10.3905/jfds.2024.1.163)

## Recording chapters

| Time | Section |
|---|---|
| 0:00 | What is a financial regime |
| 1:58 | Statistical jump models |
| 4:04 | Regime-aware factor allocation: the problem |
| 4:51 | Algorithm and data |
| 7:10 | Optimal feature selection |
| 8:30 | Allocation strategy and single-factor results |
| 10:40 | Multi-factor portfolio results |
| 12:01 | Which features each factor prefers |
| 13:54 | Summary of the first paper |
| 14:30 | Deep generative models for regime identification |
| 15:57 | Variational autoencoders and latent regimes |
| 18:20 | Jump model vs VAE |
| 19:53 | The Mixture-VAE framework |
| 21:59 | Deriving the loss and its link to the jump penalty |
| 24:32 | Audience questions: learned states and persistence |
| 27:00 | Two-state example: jump model vs Mixture-VAE |
| 29:08 | Synthetic intraday experiments |
| 31:53 | Latent-space visualization and three-state results |
| 35:30 | Real intraday S&P 500 results |
| 36:55 | Limitations and extensions |
| 38:25 | Window-length sensitivity and summary |

---

FinHorizons Foundation is an open research community advancing responsible AI in finance. Upcoming seminars and registration: [finhorizons.org](https://finhorizons.org)
