Copula-Based Pair Trading Analysis Tool

Overview
This tool uses copula-based techniques to identify and analyze pair trading opportunities between stocks by calculating log returns, fitting univariate distributions, and modeling dependencies using copulas. It then generates trading signals based on a mispricing index.

Features:
1. Log Returns Calculation: Converts stock prices to log returns.
2. Correlation Analysis: Computes Kendall's tau correlations between stocks.
3. Distribution Fitting: Fits univariate distributions to log returns.
4. Copula Fitting: Models dependencies using Clayton, Gumbel, and Frank copulas, selecting the best based on AIC.
5. Trading Signals: Identifies and plots trading signals based on the mispricing index.

How It Works:
1. Log Returns Calculation: Converts stock prices to log returns for normalization.
2. Kendall's Tau Correlation: Computes correlation between stock pairs to identify dependencies.
3. Univariate Distribution Fitting: Fits distributions to log returns to transform data for copula modeling.
4. Pseudo-Observations: Generates uniformly distributed data using fitted distributions.
5. Copula Fitting: Fits Clayton, Gumbel, and Frank copulas, selecting the best based on AIC.
6. Conditional Probabilities: Calculates probabilities to identify trading opportunities.
7. Index: Generates an index to signal potential trades based on deviations.
8. Result Visualization: Produces histograms, log returns plots, and mispricing index charts to visualize analysis and trade signals.






