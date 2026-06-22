Financial Tail Risk Modelling with GARCH and Extreme Value Theory

This project explores statistical methods for modelling financial volatility and tail risk using daily S&P 500 return data. The aim was to compare standard volatility models with extreme-value-based approaches for estimating Value-at-Risk (VaR) under market stress.

The project compared three modelling approaches:

1. GARCH baseline:
   
    A standard GARCH model was used to capture time-varying volatility in daily equity returns.
   
2. GARCH + EVT:
   
    Extreme Value Theory was applied to the residuals from the GARCH model to improve the modelling of tail events.
   
3. Time-dependent EVT:
   
    A more flexible tail-risk model was considered, allowing the tail distribution to vary with market conditions.

The models were evaluated using VaR backtesting methods, including exceedance counts and statistical tests such as Kupiec and Christoffersen tests. The project helped me connect statistical theory with practical financial risk modelling, especially in understanding how volatility clustering and heavy-tailed behaviour affect risk estimates.

Key methods:

* Time-series modelling
* GARCH volatility modelling
* Extreme Value Theory
* Generalised Pareto Distribution
* Value-at-Risk estimation
* Residual diagnostics
* VaR backtesting
* Financial return analysis

Note

This repository contains a simplified public-facing version of the project. Some implementation details and original project materials are not included.
