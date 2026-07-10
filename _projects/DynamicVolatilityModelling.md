---
title: "Dynamic Volatility Modelling for Option Hedging"
layout: single
collection: projects
permalink: /projects/DynamicVolatilityModelling

---
Abstract
-
The standard Black-Scholes (BS) model’s assumption of constant volatility is its
primary weakness. This project investigates whether dynamic volatility models provide
more effective delta-hedging performance. We implement a rolling-window backtest
on five major tech stocks (AAPL, GOOGL, MSFT, NVDA, TSLA) to compare the
hedging P&L variance of three models: a 30-day Historical Volatility (HV) benchmark, a
symmetric GARCH(1,1), and an asymmetric GJR-GARCH(1,1). The results show that
”no one size fits all.” The optimal model is asset-specific, depending on the significance
and extremity of the leverage effect. For assets with moderate leverage (GOOGL,
MSFT), GJR-GARCH is superior. For assets with extreme leverage (AAPL, NVDA),
it creates a costly ”whipsaw” effect. For assets with no leverage (TSLA), it fails due to
over-parameterization. We conclude that a successful hedging strategy requires a model
correctly specified for the asset’s unique volatility structure.

<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->
- [Jupyter Notebook](https://github.com/DhanashreeSomani/Quant-Finance-Bootcamp-2025/blob/main/Quant_Bootcamp_Project.ipynb)
- [Slides](https://github.com/DhanashreeSomani/Quant-Finance-Bootcamp-2025/blob/main/Quant_Bootcamp_Project.pdf)
- [Certificate and Presentation](https://www.erdosinstitute.org/certificates/fall-2025/quant-finance-boot-camp/dhanashree-somani/4254936c-4299-440e-92fa-f52e06af5c5a)
