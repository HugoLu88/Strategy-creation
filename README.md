# Strategy-creation

Repo for strategies that utilise technical indicator code in previous modules

*############# Notebook summaries ##############*

Backtesting algorithm

This notebook requires quite a lot of inputs and needs to be cleaned up, that include but are not limited to:

1) Specify file directory
2) Specify technical indicators and associated functions
3) Specify how we deal with autocorrelation
4) Specify which regression systems to use / backtest (e.g. Lasso, Fused Lasso, Elastic Net)
5) Calculate trading signals based on a predictive model in (4)


It will then do the following things

1) Calculate trading indicators
2) Simulate a naive backtestwithout a Monte Carlo simulation

Technical indicator strategy

This notebook requires the following inputs:

1) Specify file directory
2) Specify technical indicators and associated functions
3) Specify how we deal with autocorrelation
4) Specify which clusters to use given outputs


It will then do the following things

1) Return a summary dataframe that can be saved that includes:
- Stationary and normalised variables (independent)
- The relevant y variables



Framework
1. Data ingestion
2. Data cleaning
3. [Strategy Creation]
4. Strategy testing
5. Implementation
6. Implementation testing

