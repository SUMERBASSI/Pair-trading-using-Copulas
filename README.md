Copula-Based Pair Trading Analysis Tool

Overview
This tool uses copula-based techniques to identify and analyze pair trading opportunities between stocks by calculating log returns, fitting univariate distributions, and modeling dependencies using copulas. It then generates trading signals based on a mispricing index.

Features:
Log Returns Calculation: Converts stock prices to log returns.
Correlation Analysis: Computes Kendall's tau correlations between stocks.
Distribution Fitting: Fits univariate distributions to log returns.
Copula Fitting: Models dependencies using Clayton, Gumbel, and Frank copulas, selecting the best based on AIC.
Trading Signals: Identifies and plots trading signals based on the mispricing index.

How It Works:
Log Returns Calculation: Converts stock prices to log returns for normalization.
Kendall's Tau Correlation: Computes correlation between stock pairs to identify dependencies.
Univariate Distribution Fitting: Fits distributions to log returns to transform data for copula modeling.
Pseudo-Observations: Generates uniformly distributed data using fitted distributions.
Copula Fitting: Fits Clayton, Gumbel, and Frank copulas, selecting the best based on AIC.
Conditional Probabilities: Calculates probabilities to identify trading opportunities.
Mispricing Index: Generates an index to signal potential trades based on deviations.
Result Visualization: Produces histograms, log returns plots, and mispricing index charts to visualize analysis and trade signals.






