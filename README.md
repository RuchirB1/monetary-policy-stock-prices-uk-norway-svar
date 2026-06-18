

# Monetary Policy and Stock Prices: Evidence from the UK and Norway

## Overview

This repository contains my MSc Economics dissertation examining how domestic and foreign monetary-policy shocks affect equity markets in the United Kingdom and Norway.

The study applies Structural Vector Autoregression models to monthly macroeconomic and financial data from January 1997 to December 2023. The comparative design evaluates whether monetary-policy transmission differs between the UK’s larger, market-based financial system and Norway’s smaller, more open and energy-sensitive economy.

## Research objectives

The dissertation addresses four principal questions:

- How do contractionary domestic monetary-policy shocks affect UK and Norwegian equity prices?
- How quickly do equity markets respond, and how persistent are the effects?
- How do foreign monetary-policy shocks transmit to domestic equity markets?
- How sensitive are the results to alternative structural identification strategies?

## Data

The monthly dataset contains 324 observations and includes:

- Industrial production
- Consumer prices
- Broad money supply
- Domestic central-bank policy rates
- Nominal effective exchange rates
- Real equity-price indices
- The U.S. federal funds rate
- Global economic activity controls

The FTSE 100 represents the UK equity market, while the OBX index represents Norway. Financial and macroeconomic series are transformed to achieve stationarity and maintain economically interpretable impulse responses.

## Methodology

The empirical analysis estimates two principal models for each country:

- A recursively identified SVAR using Cholesky ordering
- A non-recursive, short-run-restricted SVAR with an explicit foreign monetary-policy block

The baseline open-economy specification contains domestic output, prices, broad money, the policy rate, the exchange rate, equity prices and the U.S. federal funds rate.

The analysis reports:

- Accumulated impulse-response functions over 24 months
- Structural forecast-error variance decompositions
- Monte Carlo bootstrap confidence intervals
- Alternative lag specifications
- Oil-price and global-activity controls
- Local-projection robustness estimates
- Stability, residual and structural-identification tests

## Main findings

- Contractionary domestic monetary-policy shocks reduce real equity prices in both countries.
- Norwegian equities respond earlier, consistent with greater sensitivity to exchange rates, commodity exposure and external financial conditions.
- UK equity responses are weaker in the immediate period but become more persistent at longer horizons.
- Foreign monetary-policy spillovers are heterogeneous across the two economies.
- Domestic monetary-policy shocks explain only a relatively small proportion of equity-price variation at business-cycle horizons.
- The findings are broadly consistent across recursive, short-run-restricted and robustness specifications.

## Interpretation

The results support the discount-rate channel of monetary-policy transmission. Higher policy rates increase required returns and reduce the present value of expected corporate cash flows, producing a negative equity-market response.

The cross-country differences indicate that monetary-policy transmission depends on financial structure, economic openness, exchange-rate exposure and sectoral composition. Norway’s smaller and more externally exposed economy reacts more quickly, while the UK response is comparatively delayed and persistent.

The limited contribution of monetary-policy shocks to overall equity volatility suggests that interest-rate policy is a blunt instrument for managing stock-market valuations. Equity markets remain strongly influenced by global risk conditions, earnings expectations, foreign policy and other financial shocks.

## Repository contents

- `Masters Thesis.pdf`  
  Full MSc Economics dissertation containing the literature review, theoretical framework, data construction, SVAR identification, impulse-response analysis, variance decompositions, robustness tests, policy implications and appendices.



## Author

**Ruchir Banerjee**

MSc Economics  


## Citation

Banerjee, R. (2025). *Monetary Policy and Stock Prices: Evidence from the UK and Norway*. MSc Economics dissertation.

## Disclaimer

This repository is provided for academic, educational and portfolio purposes.

The findings depend on the data, structural restrictions, identification assumptions and model specifications used in the dissertation. They should not be interpreted as investment, financial or monetary-policy advice.
