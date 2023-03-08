# Portfolio-Optimizer

### Portfolio optimizer for ESG-Rotman Portfolio Management Competition. 

#### Implementation of the Modern Portfolio Theory.

#### The "frontier.ipynb" notebook achieves the following:
1. Downloads historical stock prices using pandas datareader library and calculates the expected Returns and volatility of the stocks as measured by the covariance matrix.
2. Optimizes Portfolio weights according to Modern Portfolio Theory developed by Harry Markowitz. Sharpe ratio is expressed as a function of Portfolio weights, and is maximized numerically using Sequential Least Squares from scipy.optimize
3. Portfolio diversification guaranteed when restricting the weights bounds.
4. Simulated stock prices could also be used in optimization.

#### Other features found in MC.ipynb
Simulated stock prices alongside their distribution.

Note:
Sequential Least Squares Programming (SLSQP) is usefull in solving quadratic functions with inequality contraints.
