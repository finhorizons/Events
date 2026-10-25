# Decision Focused Learning for Portfolio Optimization

**FinHorizons Seminar 01**

- **Speaker:** Yoontae Hwang, Assistant Professor, Graduate School of Data Science, Pusan National University
- **Date:** Saturday 17 October 2026, 13:00 BST, online on Zoom
- **Recording:** [YouTube](https://www.youtube.com/watch?v=4OzjlrNVQ2k)
- **Slides:** [PDF](./Yoontae_Hwang_Decision_Focused_Learning_for_Portfolio_Optimization.pdf)

## Abstract

This talk addresses the disconnect between prediction and decision quality in portfolio optimization by integrating large language models with decision-focused learning. Minimizing prediction error alone leads to suboptimal portfolio decisions, both theoretically and empirically. The proposed model, DINN, uses an attention mechanism over asset relationships, temporal dependencies and macro variables, feeding directly into a differentiable portfolio optimization layer so that predictions align with the decision objective. Experiments on the S&P 100 and Dow 30 show consistent gains over state-of-the-art deep learning models, and gradient-based analyses show that the model prioritizes the assets that matter most for the decision.

## About the speaker

Yoontae Hwang is an Assistant Professor at the Graduate School of Data Science, Pusan National University, where he leads the Time Series Intelligence (TSI) Lab. Before joining in September 2025, he was a postdoctoral researcher at the University of Oxford with Professor Stefan Zohren. He earned his PhD in Industrial Engineering from UNIST in 2024. His research focuses on financial AI, time-series modeling and foundation models for finance, with applications to portfolio optimization, asset allocation and volatility forecasting. He co-organizes [FinFM: Foundation Models and Generative AI for Finance](https://finfm.finhorizons.org) at AAAI 2027.

## Paper

Yoontae Hwang, Yaxuan Kong, Stefan Zohren and Yongjae Lee. *Decision-informed Neural Network with Large Language Model Integration for Portfolio Optimization.* Expert Systems with Applications, 2026.
[Publisher](https://www.sciencedirect.com/science/article/abs/pii/S0957417426032938) · [arXiv](https://arxiv.org/abs/2502.00828)

## Recording chapters

| Time | Section |
|---|---|
| 0:00 | Introduction and outline |
| 0:46 | Prediction error vs decision regret |
| 2:01 | Prediction-, metric- and decision-based learning |
| 3:25 | A two-asset example |
| 4:22 | Adding a decision loss to existing forecasters |
| 4:56 | Results: more stable portfolios on S&P 100 and Dow 30 |
| 6:38 | DINN architecture |
| 8:34 | Text prompts and macroeconomic data |
| 9:56 | Expected return and covariance estimation |
| 10:53 | Mean-variance layer and the oracle portfolio |
| 12:26 | How the decision loss changes the gradient |
| 13:08 | Implicit differentiation and sensitivity analysis |
| 14:19 | Data split and baselines |
| 15:23 | Results on S&P 100 and Dow 30 |
| 16:39 | Ablations: decision loss and prompts |
| 19:04 | Lower regret with higher MSE; decision sensitivity |
| 20:22 | Prompt shuffling test and summary |
| 21:28 | FinFM workshop at AAAI 2027 |

---

FinHorizons Foundation is an open research community advancing responsible AI in finance. Upcoming seminars and registration: [finhorizons.org](https://finhorizons.org)
