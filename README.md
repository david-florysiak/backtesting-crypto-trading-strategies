# Backtesting Crypto Trading Strategies

This repository contains a [Jupyter notebook](backtesting-crypto-trading-strategies.ipynb) and the 
[presentation slides](Presentation_PyChain2022_David_Florysiak.pdf) that I used for my talk at the [PyChain 2022 
conference](https://www.pychain.org), the first Python and blockchain online developer conference.

The main question of this talk is how can trading strategies be evaluated? In other words, how can I avoid investing in 
supposedly profitable trading strategies?

We use a Simple Moving Average strategy for cryptos as an example to show how multiple testing issues arise through data
mining. We use methods proposed in [Harvey and Liu (2015), Backtesting, The Journal of Portfolio Management, 42 (1), 13-28](https://doi.org/10.3905/jpm.2015.42.1.013), 
to adjust our performance measures for multiple testing, for example, by calculating a “haircut Sharpe ratio”. The 
idea of this talk is to raise awareness that many supposedly profitable strategies, if “fair” backtesting is performed 
and high but reasonable testing standards are applied, are no longer profitable.

The talk is available on YouTube: https://youtu.be/N0VfTcBzqVY

You can get in touch with me on LinkedIn: https://www.linkedin.com/in/florysiak/
