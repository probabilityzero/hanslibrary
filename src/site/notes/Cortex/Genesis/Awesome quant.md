---
{"dg-publish":true,"dg-path":"Genesis/Awesome quant.md","permalink":"/genesis/awesome-quant/"}
---

# Awesome Quant

A curated list of insanely awesome libraries, packages and resources for Quants (Quantitative Finance).

[![](https://awesome.re/badge.svg)](https://awesome.re)

## Languages

- [Python](#python)
- [R](#r)
- [Matlab](#matlab)
- [Julia](#julia)
- [Java](#java)
- [JavaScript](#javascript)
- [Haskell](#haskell)
- [Scala](#scala)
- [Ruby](#ruby)
- [Elixir/Erlang](#elixirerlang)
- [Golang](#golang)
- [CPP](#cpp)
- [CSharp](#csharp)
- [Rust](#rust)
- [Frameworks](#frameworks)
- [Reproducing Works, Training & Books](#reproducing-works-training--books)

## Python

### Numerical Libraries & Data Structures

- [numpy](https://www.numpy.org) - NumPy is the fundamental package for scientific computing with Python.
- [scipy](https://www.scipy.org) - SciPy (pronounced “Sigh Pie”) is a Python-based ecosystem of open-source software for mathematics, science, and engineering.
- [pandas](https://pandas.pydata.org) - pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.
- [polars](https://docs.pola.rs/) - Polars is a blazingly fast DataFrame library for manipulating structured data.
- [quantdsl](https://github.com/johnbywater/quantdsl) - Domain specific language for quantitative analytics in finance and trading.
- [statistics](https://docs.python.org/3/library/statistics.html) - Builtin Python library for all basic statistical calculations.
- [sympy](https://www.sympy.org/) - SymPy is a Python library for symbolic mathematics.
- [pymc3](https://docs.pymc.io/) - Probabilistic Programming in Python: Bayesian Modeling and Probabilistic Machine Learning with Theano.
- [modelx](https://docs.modelx.io/) - Python reimagination of spreadsheets as formula-centric objects that are interoperable with pandas.
- [ArcticDB](https://github.com/man-group/ArcticDB) - High performance datastore for time series and tick data.

### Financial Instruments and Pricing

- [OpenBB Terminal](https://github.com/OpenBB-finance/OpenBBTerminal) - Terminal for investment research for everyone.
- [Fincept Terminal](https://github.com/Fincept-Corporation/FinceptTerminal) - Advance Data Based A.I Terminal for all Types of Financial Asset Research.
- [PyQL](https://github.com/enthought/pyql) - QuantLib's Python port.
- [pyfin](https://github.com/opendoor-labs/pyfin) - Basic options pricing in Python. *ARCHIVED*
- [vollib](https://github.com/vollib/vollib) - vollib is a python library for calculating option prices, implied volatility and greeks.
- [QuantPy](https://github.com/jsmidt/QuantPy) - A framework for quantitative finance In python.
- [Finance-Python](https://github.com/alpha-miner/Finance-Python) - Python tools for Finance.
- [ffn](https://github.com/pmorissette/ffn) - A financial function library for Python.
- [pynance](https://github.com/GriffinAustin/pynance) - Lightweight Python library for assembling and analyzing financial data.
- [tia](https://github.com/bpsmith/tia) - Toolkit for integration and analysis.
- [hasura/base-python-dash](https://platform.hasura.io/hub/projects/hasura/base-python-dash) - Hasura quick start to deploy Dash framework. Written on top of Flask, Plotly.js, and React.js, Dash is ideal for building data visualization apps with highly custom user interfaces in pure Python.
- [hasura/base-python-bokeh](https://platform.hasura.io/hub/projects/hasura/base-python-bokeh) - Hasura quick start to visualize data with bokeh library.
- [pysabr](https://github.com/ynouri/pysabr) - SABR model Python implementation.
- [FinancePy](https://github.com/domokane/FinancePy) - A Python Finance Library that focuses on the pricing and risk-management of Financial Derivatives, including fixed-income, equity, FX and credit derivatives.
- [gs-quant](https://github.com/goldmansachs/gs-quant) - Python toolkit for quantitative finance
- [willowtree](https://github.com/federicomariamassari/willowtree) - Robust and flexible Python implementation of the willow tree lattice for derivatives pricing.
- [financial-engineering](https://github.com/federicomariamassari/financial-engineering) - Applications of Monte Carlo methods to financial engineering projects, in Python.
- [optlib](https://github.com/dbrojas/optlib) - A library for financial options pricing written in Python.
- [tf-quant-finance](https://github.com/google/tf-quant-finance) - High-performance TensorFlow library for quantitative finance.
- [Q-Fin](https://github.com/RomanMichaelPaolucci/Q-Fin) - A Python library for mathematical finance.
- [Quantsbin](https://github.com/quantsbin/Quantsbin) - Tools for pricing and plotting of vanilla option prices, greeks and various other analysis around them.
- [finoptions](https://github.com/bbcho/finoptions-dev) - Complete python implementation of R package fOptions with partial implementation of fExoticOptions for pricing various options.
- [pypme](https://github.com/ymyke/pypme) - PME (Public Market Equivalent) calculation.
- [AbsBox](https://github.com/yellowbean/AbsBox) - A Python based library to model cashflow for structured product like Asset-backed securities (ABS) and Mortgage-backed securities (MBS).
- [Intrinsic-Value-Calculator](https://github.com/akashaero/Intrinsic-Value-Calculator) - A Python tool for quick calculations of a stock's fair value using Discounted Cash Flow analysis.
- [Kelly-Criterion](https://github.com/deltaray-io/kelly-criterion) - Kelly Criterion implemented in Python to size portfolios based on J. L. Kelly Jr's formula.
- [rateslib](https://github.com/attack68/rateslib) - A fixed income library for pricing bonds and bond futures, and derivatives such as IRS, cross-currency and FX swaps.
- [fypy](https://github.com/jkirkby3/fypy) - Vanilla and exotic option pricing library to support quantitative R&D. Focus on pricing interesting/useful models and contracts (including and beyond Black-Scholes), as well as calibration of financial models to market data.

### Indicators

- [pandas_talib](https://github.com/femtotrader/pandas_talib) - A Python Pandas implementation of technical analysis indicators.
- [finta](https://github.com/peerchemist/finta) - Common financial technical analysis indicators implemented in Pandas.
- [Tulipy](https://github.com/cirla/tulipy) - Financial Technical Analysis Indicator Library (Python bindings for [tulipindicators](https://github.com/TulipCharts/tulipindicators))
- [lppls](https://github.com/Boulder-Investment-Technologies/lppls) - A Python module for fitting the [Log-Periodic Power Law Singularity (LPPLS)](https://en.wikipedia.org/wiki/Didier_Sornette#The_JLS_and_LPPLS_models) model.
- [talipp](https://github.com/nardew/talipp) - Incremental technical analysis library for Python.
- [streaming_indicators](https://github.com/mr-easy/streaming_indicators) - A python library for computing technical analysis indicators on streaming data.

### Trading & Backtesting
- [skfolio](https://github.com/skfolio/skfolio) - Python library for portfolio optimization built on top of scikit-learn. It provides a unified interface and sklearn compatible tools to build, tune and cross-validate portfolio models.
- [Investing algorithm framework](https://github.com/coding-kitties/investing-algorithm-framework) - Framework for developing, backtesting, and deploying automated trading algorithms.
- [QSTrader](https://github.com/mhallsmoore/qstrader) - QSTrader backtesting simulation engine.
- [Blankly](https://github.com/Blankly-Finance/Blankly) - Fully integrated backtesting, paper trading, and live deployment.
- [TA-Lib](https://github.com/mrjbq7/ta-lib) - Python wrapper for TA-Lib (<http://ta-lib.org/>).
- [zipline](https://github.com/quantopian/zipline) - Pythonic algorithmic trading library.
- [zipline-reloaded](https://github.com/stefan-jansen/zipline-reloaded) - Zipline, a Pythonic Algorithmic Trading Library.
- [QuantSoftware Toolkit](https://github.com/QuantSoftware/QuantSoftwareToolkit) - Python-based open source software framework designed to support portfolio construction and management.
- [quantitative](https://github.com/jeffrey-liang/quantitative) - Quantitative finance, and backtesting library.
- [analyzer](https://github.com/llazzaro/analyzer) - Python framework for real-time financial and backtesting trading strategies.
- [bt](https://github.com/pmorissette/bt) - Flexible Backtesting for Python.
- [backtrader](https://github.com/backtrader/backtrader) - Python Backtesting library for trading strategies.
- [pythalesians](https://github.com/thalesians/pythalesians) - Python library to backtest trading strategies, plot charts, seamlessly download market data, analyze market patterns etc.
- [pybacktest](https://github.com/ematvey/pybacktest) - Vectorized backtesting framework in Python / pandas, designed to make your backtesting easier.
- [pyalgotrade](https://github.com/gbeced/pyalgotrade) - Python Algorithmic Trading Library.
- [basana](https://github.com/gbeced/basana) - A Python async and event driven framework for algorithmic trading, with a focus on crypto currencies.
- [tradingWithPython](https://pypi.org/project/tradingWithPython/) - A collection of functions and classes for Quantitative trading.
- [Pandas TA](https://github.com/twopirllc/pandas-ta) - Pandas TA is an easy to use Python 3 Pandas Extension with 115+ Indicators. Easily build Custom Strategies.
- [ta](https://github.com/bukosabino/ta) - Technical Analysis Library using Pandas (Python)
- [algobroker](https://github.com/joequant/algobroker) - This is an execution engine for algo trading.
- [pysentosa](https://pypi.org/project/pysentosa/) - Python API for sentosa trading system.
- [finmarketpy](https://github.com/cuemacro/finmarketpy) - Python library for backtesting trading strategies and analyzing financial markets.
- [binary-martingale](https://github.com/metaperl/binary-martingale) - Computer program to automatically trade binary options martingale style.
- [fooltrader](https://github.com/foolcage/fooltrader) - the project using big-data technology to provide an uniform way to analyze the whole market.
- [zvt](https://github.com/zvtvz/zvt) - the project using sql, pandas to provide an uniform and extendable way to record data, computing factors, select securities, backtesting, realtime trading and it could show all of them in clearly charts in realtime.
- [pylivetrader](https://github.com/alpacahq/pylivetrader) - zipline-compatible live trading library.
- [pipeline-live](https://github.com/alpacahq/pipeline-live) - zipline's pipeline capability with IEX for live trading.
- [zipline-extensions](https://github.com/quantrocket-llc/zipline-extensions) - Zipline extensions and adapters for QuantRocket.
- [moonshot](https://github.com/quantrocket-llc/moonshot) - Vectorized backtester and trading engine for QuantRocket based on Pandas.
- [PyPortfolioOpt](https://github.com/robertmartin8/PyPortfolioOpt) - Financial portfolio optimization in python, including classical efficient frontier and advanced methods.
- [Eiten](https://github.com/tradytics/eiten) - Eiten is an open source toolkit by Tradytics that implements various statistical and algorithmic investing strategies such as Eigen Portfolios, Minimum Variance Portfolios, Maximum Sharpe Ratio Portfolios, and Genetic Algorithms based Portfolios.
- [riskparity.py](https://github.com/dppalomar/riskparity.py) - fast and scalable design of risk parity portfolios with TensorFlow 2.0
- [mlfinlab](https://github.com/hudson-and-thames/mlfinlab) - Implementations regarding "Advances in Financial Machine Learning" by Marcos Lopez de Prado. (Feature Engineering, Financial Data Structures, Meta-Labeling)
- [pyqstrat](https://github.com/abbass2/pyqstrat) - A fast, extensible, transparent python library for backtesting quantitative strategies.
- [NowTrade](https://github.com/edouardpoitras/NowTrade) - Python library for backtesting technical/mechanical strategies in the stock and currency markets.
- [pinkfish](https://github.com/fja05680/pinkfish) - A backtester and spreadsheet library for security analysis.
- [aat](https://github.com/timkpaine/aat) - Async Algorithmic Trading Engine
- [Backtesting.py](https://kernc.github.io/backtesting.py/) - Backtest trading strategies in Python
- [catalyst](https://github.com/enigmampc/catalyst) - An Algorithmic Trading Library for Crypto-Assets in Python
- [quantstats](https://github.com/ranaroussi/quantstats) - Portfolio analytics for quants, written in Python
- [qtpylib](https://github.com/ranaroussi/qtpylib) - QTPyLib, Pythonic Algorithmic Trading <http://qtpylib.io>
- [Quantdom](https://github.com/constverum/Quantdom) - Python-based framework for backtesting trading strategies & analyzing financial markets [GUI :neckbeard:]
- [freqtrade](https://github.com/freqtrade/freqtrade) - Free, open source crypto trading bot
- [algorithmic-trading-with-python](https://github.com/chrisconlan/algorithmic-trading-with-python) - Free `pandas` and `scikit-learn` resources for trading simulation, backtesting, and machine learning on financial data.
- [DeepDow](https://github.com/jankrepl/deepdow) - Portfolio optimization with deep learning
- [Qlib](https://github.com/microsoft/qlib) - An AI-oriented Quantitative Investment Platform by Microsoft. Full ML pipeline of data processing, model training, back-testing; and covers the entire chain of quantitative investment: alpha seeking, risk modeling, portfolio optimization, and order execution.
- [machine-learning-for-trading](https://github.com/stefan-jansen/machine-learning-for-trading) - Code and resources for Machine Learning for Algorithmic Trading
- [AlphaPy](https://github.com/ScottfreeLLC/AlphaPy) - Automated Machine Learning [AutoML] with Python, scikit-learn, Keras, XGBoost, LightGBM, and CatBoost
- [jesse](https://github.com/jesse-ai/jesse) - An advanced crypto trading bot written in Python
- [rqalpha](https://github.com/ricequant/rqalpha) - A extendable, replaceable Python algorithmic backtest && trading framework supporting multiple securities.
- [FinRL-Library](https://github.com/AI4Finance-LLC/FinRL-Library) - A Deep Reinforcement Learning Library for Automated Trading in Quantitative Finance. NeurIPS 2020.
- [bulbea](https://github.com/achillesrasquinha/bulbea) - Deep Learning based Python Library for Stock Market Prediction and Modelling.
- [ib_nope](https://github.com/ajhpark/ib_nope) - Automated trading system for NOPE strategy over IBKR TWS.
- [OctoBot](https://github.com/Drakkar-Software/OctoBot) - Open source cryptocurrency trading bot for high frequency, arbitrage, TA and social trading with an advanced web interface.
- [bta-lib](https://github.com/mementum/bta-lib) - Technical Analysis library in pandas for backtesting algotrading and quantitative analysis.
- [Stock-Prediction-Models](https://github.com/huseinzol05/Stock-Prediction-Models) - Gathers machine learning and deep learning models for Stock forecasting including trading bots and simulations.
- [TuneTA](https://github.com/jmrichardson/tuneta) - TuneTA optimizes technical indicators using a distance correlation measure to a user defined target feature such as next day return.
- [AutoTrader](https://github.com/kieran-mackle/AutoTrader) - A Python-based development platform for automated trading systems - from backtesting to optimization to livetrading.
- [fast-trade](https://github.com/jrmeier/fast-trade) - A library built with backtest portability and performance in mind for backtest trading strategies.
- [qf-lib](https://github.com/quarkfin/qf-lib) - QF-Lib is a Python library that provides high quality tools for quantitative finance.
- [tda-api](https://github.com/alexgolec/tda-api) - Gather data and trade equities, options, and ETFs via TDAmeritrade.
- [vectorbt](https://github.com/polakowo/vectorbt) - Find your trading edge, using a powerful toolkit for backtesting, algorithmic trading, and research.
- [Lean](https://github.com/QuantConnect/Lean) - Lean Algorithmic Trading Engine by QuantConnect (Python, C#).
- [fast-trade](https://github.com/jrmeier/fast-trade) - Low code backtesting library utilizing pandas and technical analysis indicators.
- [pysystemtrade](https://github.com/robcarver17/pysystemtrade) - pysystemtrade is the open source version of Robert Carver's backtesting and trading engine that implements systems according to the framework outlined in his book "Systematic Trading", which is further developed on his [blog](https://qoppac.blogspot.com/).
- [pytrendseries](https://github.com/rafa-rod/pytrendseries) - Detect trend in time series, drawdown, drawdown within a constant look-back window , maximum drawdown, time underwater.
- [PyLOB](https://github.com/DrAshBooth/PyLOB) - Fully functioning fast Limit Order Book written in Python.
- [PyBroker](https://github.com/edtechre/pybroker) - Algorithmic Trading with Machine Learning.
- [OctoBot Script](https://github.com/Drakkar-Software/OctoBot-Script) - A quant framework to create cryptocurrencies strategies - from backtesting to optimization to livetrading.
- [hftbacktest](https://github.com/nkaz001/hftbacktest) - A high-frequency trading and market-making backtesting tool accounts for limit orders, queue positions, and latencies, utilizing full tick data for trades and order books.
- [vnpy](https://github.com/vnpy/vnpy) - VeighNa is a Python-based open source quantitative trading system development framework.
- [Intelligent Trading Bot](https://github.com/asavinov/intelligent-trading-bot) - Automatically generating signals and trading based on machine learning and feature engineering
- [fastquant](https://github.com/enzoampil/fastquant) - fastquant allows you to easily backtest investment strategies with as few as 3 lines of python code.
- [nautilus_trader](https://github.com/nautechsystems/nautilus_trader) - A high-performance algorithmic trading platform and event-driven backtester.
- [YABTE](https://github.com/bsdz/yabte) - Yet Another (Python) BackTesting Engine.
- [Trading Strategy](https://github.com/tradingstrategy-ai/getting-started) - TradingStrategy.ai is a market data, backtesting, live trading and investor management framework for decentralised finance
- [Hikyuu](https://github.com/fasiondog/hikyuu) - A base on Python/C++ open source high-performance quant framework for faster analysis and backtesting, contains the complete trading system components for reuse and combination.
- [rust_bt](https://github.com/jensnesten/rust_bt) - A high performance, low-latency backtesting engine for testing quantitative trading strategies on historical and live data in Rust.

### Risk Analysis

- [QuantLibRisks](https://github.com/auto-differentiation/QuantLib-Risks-Py) - Fast risks with QuantLib
- [XAD](https://github.com/auto-differentiation/xad-py) - Automatic Differentation (AAD) Library
- [pyfolio](https://github.com/quantopian/pyfolio) - Portfolio and risk analytics in Python.
- [empyrical](https://github.com/quantopian/empyrical) - Common financial risk and performance metrics.
- [fecon235](https://github.com/rsvp/fecon235) - Computational tools for financial economics include: Gaussian Mixture model of leptokurtotic risk, adaptive Boltzmann portfolios.
- [finance](https://pypi.org/project/finance/) - Financial Risk Calculations. Optimized for ease of use through class construction and operator overload.
- [qfrm](https://pypi.org/project/qfrm/) - Quantitative Financial Risk Management: awesome OOP tools for measuring, managing and visualizing risk of financial instruments and portfolios.
- [visualize-wealth](https://github.com/benjaminmgross/visualize-wealth) - Portfolio construction and quantitative analysis.
- [VisualPortfolio](https://github.com/wegamekinglc/VisualPortfolio) - This tool is used to visualize the performance of a portfolio.
- [universal-portfolios](https://github.com/Marigold/universal-portfolios) - Collection of algorithms for online portfolio selection.
- [FinQuant](https://github.com/fmilthaler/FinQuant) - A program for financial portfolio management,