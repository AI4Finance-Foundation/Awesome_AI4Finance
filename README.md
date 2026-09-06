# Awesome AI for Finance [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/Awesome_AI4Finance?style=social)](https://github.com/AI4Finance-Foundation/Awesome_AI4Finance)
[![License](https://img.shields.io/github/license/AI4Finance-Foundation/Awesome_AI4Finance)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/AI4Finance-Foundation/Awesome_AI4Finance/pulls)

> A curated list of awesome AI / machine learning / deep learning / reinforcement learning / LLM tools, frameworks, and resources for quantitative finance.

This list is maintained by the [AI4Finance Foundation](https://github.com/AI4Finance-Foundation). If you find it useful, please give it a star🌟!

---

## Contents

- [AI4Finance Foundation Ecosystem](#ai4finance-foundation-ecosystem)
- [LLMs for Finance](#llms-for-finance)
- [AI Agents for Finance](#ai-agents-for-finance)
- [Deep Reinforcement Learning](#deep-reinforcement-learning)
- [Machine Learning](#machine-learning)
- [Quantitative Trading & Backtesting](#quantitative-trading--backtesting)
- [Data Sources](#data-sources)
- [Technical Analysis](#technical-analysis)
- [Portfolio Management & Risk](#portfolio-management--risk)
- [Sentiment Analysis & NLP](#sentiment-analysis--nlp)
- [Quantitative Finance Libraries](#quantitative-finance-libraries)
- [Trading Platforms](#trading-platforms)
- [Visualization & Rendering](#visualization--rendering)
- [High Performance Computing](#high-performance-computing)
- [Research Papers & Surveys](#research-papers--surveys)
- [Books](#books)
- [Contributing](#contributing)

---

## AI4Finance Foundation Ecosystem

The [AI4Finance Foundation](https://github.com/AI4Finance-Foundation) provides a full-stack open-source ecosystem for AI-driven finance, from data to deployment.

| Project | Stars | Description |
|---------|-------|-------------|
| [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) | 20.4k ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinGPT?style=flat-square) | Open-source financial large language models. Fine-tuning LLMs (LLaMA, ChatGLM, etc.) with financial data for sentiment analysis, robo-advising, and quantitative trading. |
| [FinRL](https://github.com/AI4Finance-Foundation/FinRL) | 15.3k ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL?style=flat-square) | The first open-source framework for financial reinforcement learning. Full pipeline from data processing to DRL-based trading (stock, crypto, forex). |
| [FinRobot](https://github.com/AI4Finance-Foundation/FinRobot) | 7.2k ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRobot?style=flat-square) | Open-source AI agent platform for financial analysis using LLMs. Multi-agent architecture for report generation, analysis, and trading decisions. |
| [ElegantRL](https://github.com/AI4Finance-Foundation/ElegantRL) | 4.3k ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/ElegantRL?style=flat-square) | Scalable and elastic deep reinforcement learning library using PyTorch. Lightweight, efficient, and cloud-native. |
| [FinRL-X](https://github.com/AI4Finance-Foundation/FinRL-Trading) | 3.2k ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL-Trading?style=flat-square) | AI-native modular infrastructure for quantitative trading. Unifies data, strategy, backtesting, and execution. [Paper](https://arxiv.org/abs/2603.21330) |
| [FinRL-Meta](https://github.com/AI4Finance-Foundation/FinRL-Meta) | 1.9k ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL-Meta?style=flat-square) | A universe of dynamic market environments for financial reinforcement learning. Standardized datasets for stock, crypto, and forex. |
| [FinNLP](https://github.com/AI4Finance-Foundation/FinNLP) | 1.5k ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinNLP?style=flat-square) | Democratizing internet-scale financial data. NLP toolkit for financial news and social media data processing. |
| [FinRL-Tutorials](https://github.com/AI4Finance-Foundation/FinRL-Tutorials) | 1.2k ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL-Tutorials?style=flat-square) | Jupyter notebook tutorials covering stock trading, portfolio allocation, crypto trading, and more. |
| [FinRL-Podracer](https://github.com/AI4Finance-Foundation/FinRL_Podracer) | 501 ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL_Podracer?style=flat-square) | Cloud-based framework for massively parallel financial RL training. |
| [RLSolver](https://github.com/AI4Finance-Foundation/RLSolver) | 167 ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/RLSolver?style=flat-square) | RL-based solver for combinatorial optimization problems in finance. |

---
- [Helium MCP](https://github.com/connerlambden/helium-mcp) — Real-time news with 37-dimension bias scoring, ML options pricing, and live market data. [Interactive demo](https://connerlambden.github.io/helium-news-explorer/) · [REST API](https://heliumtrades.com/mcp-page/)

## LLMs for Finance

Large Language Models are transforming finance through automated analysis, report generation, and intelligent trading.

| Project | Stars | Description |
|---------|-------|-------------|
| [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) | 20.4k ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinGPT?style=flat-square) | Open-source financial LLM framework with LoRA/QLoRA fine-tuning on financial data. |
| [FinRobot](https://github.com/AI4Finance-Foundation/FinRobot) | 7.2k ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRobot?style=flat-square) | AI agent platform for financial analysis using LLMs with multi-agent architecture. |
| [FinGLM](https://github.com/MetaGLM/FinGLM) | 2.2k ![Stars](https://img.shields.io/github/stars/MetaGLM/FinGLM?style=flat-square) | Open financial LLM by Zhipu AI built on ChatGLM, with annual report datasets and challenge competition code. |
| [FinBERT](https://github.com/ProsusAI/finBERT) | 2.1k ![Stars](https://img.shields.io/github/stars/ProsusAI/finBERT?style=flat-square) | Pre-trained NLP model to analyze sentiment of financial text. Built on BERT, fine-tuned on financial corpus. |
| [FinNLP](https://github.com/AI4Finance-Foundation/FinNLP) | 1.5k ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinNLP?style=flat-square) | Toolkit for financial NLP with easy access to financial news and social media data. |
| [XuanYuan](https://github.com/Duxiaoman-DI/XuanYuan) | 1.3k ![Stars](https://img.shields.io/github/stars/Duxiaoman-DI/XuanYuan?style=flat-square) | Chinese financial chat LLM from Du Xiaoman Financial. Hundreds of billions of parameters, fine-tuned on financial domain data. |
| [DISC-FinLLM](https://github.com/FudanDISC/DISC-FinLLM) | 878 ![Stars](https://img.shields.io/github/stars/FudanDISC/DISC-FinLLM?style=flat-square) | Chinese financial LLM from Fudan University. Multi-expert fine-tuning for QA, domain NLP, math computation, and RAG-based consulting. |
| [PIXIU (FinMA)](https://github.com/The-FinAI/PIXIU) | 865 ![Stars](https://img.shields.io/github/stars/The-FinAI/PIXIU?style=flat-square) | Open-source financial LLM evaluation framework with FinMA models (7B/30B), FinBen benchmark, and 136K instruction-tuning dataset. |
| [Fin-R1](https://github.com/SUFE-AIFLM-Lab/Fin-R1) | 790 ![Stars](https://img.shields.io/github/stars/SUFE-AIFLM-Lab/Fin-R1?style=flat-square) | Financial reasoning LLM based on Qwen2.5-7B, trained with SFT + RL on 60K chain-of-thought samples. SOTA on FinQA and ConvFinQA. |
| [InvestLM](https://github.com/AbaciNLP/InvestLM) | 153 ![Stars](https://img.shields.io/github/stars/AbaciNLP/InvestLM?style=flat-square) | Investment-focused LLM fine-tuned on LLaMA-65B using CFA exams, SEC filings, and quant finance data. Rated comparable to GPT-4 by hedge fund managers. |

---

## AI Agents for Finance
| [Pineify](https://pineify.app/) | – | AI-assisted trading workflow with Pine Script, MQL5, and cTrader coding agents, financial research tools, market screening, strategy optimization, and backtest analysis. |

Autonomous AI agents that can analyze markets, make trading decisions, and generate financial reports.

| Project | Stars | Description |
|---------|-------|-------------|
| [TradingAgents](https://github.com/TauricResearch/TradingAgents) | 82.4k ![Stars](https://img.shields.io/github/stars/TauricResearch/TradingAgents?style=flat-square) | Multi-agent LLM financial trading framework. Specialized agents (fundamentals, sentiment, technical) debate and reach consensus on trades. |
| [ai-hedge-fund](https://github.com/virattt/ai-hedge-fund) | 59.7k ![Stars](https://img.shields.io/github/stars/virattt/ai-hedge-fund?style=flat-square) | Multi-agent AI hedge fund simulator with 18 agents modeled after legendary investors (Buffett, Munger, etc.) plus specialist agents. |
| [daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis) | 40.0k ![Stars](https://img.shields.io/github/stars/ZhuLinsen/daily_stock_analysis?style=flat-square) | LLM-powered A/H/US stock analysis system. Multi-source market data + real-time news + LLM decision dashboard + multi-channel push notifications. |
| [Anthropic Financial Services](https://github.com/anthropics/financial-services) | 29.6k ![Stars](https://img.shields.io/github/stars/anthropics/financial-services?style=flat-square) | Anthropic's official reference agents for finance: 10 specialized agents for earnings review, KYC screening, pitch generation, model building, and more. |
| [TradingAgents-CN](https://github.com/hsliuping/TradingAgents-CN) | 27.8k ![Stars](https://img.shields.io/github/stars/hsliuping/TradingAgents-CN?style=flat-square) | Chinese multi-agent LLM trading framework simulating professional trading firm workflows for A/HK/US markets. |
| [AI-Trader](https://github.com/HKUDS/AI-Trader) | 19.1k ![Stars](https://img.shields.io/github/stars/HKUDS/AI-Trader?style=flat-square) | Fully-automated agent-native trading platform from HKU. Cross-platform signal sync and one-click copy trading. |
| [Qbot](https://github.com/UFund-Me/Qbot) | 17.5k ![Stars](https://img.shields.io/github/stars/UFund-Me/Qbot?style=flat-square) | AI-powered quantitative investment research platform with 300+ models from 40+ papers, fully local deployment. |
| [nofx](https://github.com/NoFxAiOS/nofx) | 12.5k ![Stars](https://img.shields.io/github/stars/NoFxAiOS/nofx?style=flat-square) | AI trading terminal for stocks, commodities, forex, and crypto. 7 exchanges + 7 AI models competing in real-time. |
| [Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) | 9.6k ![Stars](https://img.shields.io/github/stars/HKUDS/Vibe-Trading?style=flat-square) | Personal trading agent from HKU for research, simulation, backtesting, and autonomous broker-authorized trading. |
| [FinRobot](https://github.com/AI4Finance-Foundation/FinRobot) | 7.2k ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRobot?style=flat-square) | Open-source AI agent platform for financial applications powered by LLMs. |
| [Polymarket Agents](https://github.com/Polymarket/agents) | 3.6k ![Stars](https://img.shields.io/github/stars/Polymarket/agents?style=flat-square) | Official Polymarket framework for building autonomous AI agents that trade prediction markets. |
| [AutoHedge](https://github.com/The-Swarm-Corporation/AutoHedge) | 3.1k ![Stars](https://img.shields.io/github/stars/The-Swarm-Corporation/AutoHedge?style=flat-square) | Swarm-intelligence-powered autonomous hedge fund with Director, Quant, Risk, and Execution agents. |
| [AlphaGen](https://github.com/RL-MLDM/alphagen) | 1.1k ![Stars](https://img.shields.io/github/stars/RL-MLDM/alphagen?style=flat-square) | Generates synergistic formulaic alpha factors via reinforcement learning (KDD 2023). |
| [QuantaAlpha](https://github.com/QuantaAlpha/QuantaAlpha) | 1.0k ![Stars](https://img.shields.io/github/stars/QuantaAlpha/QuantaAlpha?style=flat-square) | LLM + evolutionary strategies framework for automatic alpha factor mining. |
| [FinMem](https://github.com/pipiku915/FinMem-LLM-StockTrading) | 903 ![Stars](https://img.shields.io/github/stars/pipiku915/FinMem-LLM-StockTrading?style=flat-square) | LLM-based trading agent with layered memory (short/mid/long-term) for evolving market understanding. |
| [QVeris](https://github.com/QVerisAI/qveris-agent-toolkit) | 230 ![Stars](https://img.shields.io/github/stars/QVerisAI/qveris-agent-toolkit?style=flat-square) | Capability routing network for AI agents to discover, inspect, and call 10,000+ real-world financial capabilities through one unified MCP protocol. |
| [Superhighway M&A Research Agent](https://superhighway.walls.sh/guides/ma-research-agent) | – | Python agent that researches comparable M&A transactions, deal multiples, potential acquirers, and recent deal activity via live web search. Generates structured M&A intelligence briefs for corporate development, PE analysts, and investment bankers. Pay-per-call, no signup. |
| [NeuPortal](https://neuportal.ai) | – | AI forecasting-accountability lab. Every AI forecast is locked pre-event, Bitcoin-timestamped via OpenTimestamps, and Brier-scored in public against prediction markets across crypto, macro, and sports. Hosted, closed-source service. |

---
| [Algorier](https://algorier.com) | – | Natural-language ("vibe trading") agent that turns a described trading idea into a generated, backtested and forward-tested algorithm and deploys it to the user's own broker account across forex, crypto, metals, indices, CFDs and equities; strategies can also be sold on its marketplace with the logic kept private from buyers. |

## Deep Reinforcement Learning

Frameworks and libraries applying deep reinforcement learning to trading, portfolio management, and market making.

| Project | Stars | Description |
|---------|-------|-------------|
| [FinRL](https://github.com/AI4Finance-Foundation/FinRL) | 15.3k ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL?style=flat-square) | The first open-source DRL framework for quantitative finance. Supports PPO, A2C, DDPG, SAC, TD3, and more. |
| [TensorTrade](https://github.com/tensortrade-org/tensortrade) | 6.3k ![Stars](https://img.shields.io/github/stars/tensortrade-org/tensortrade?style=flat-square) | An RL framework for training, evaluating, and deploying robust trading agents. |
| [ElegantRL](https://github.com/AI4Finance-Foundation/ElegantRL) | 4.3k ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/ElegantRL?style=flat-square) | Massively parallel deep reinforcement learning using PyTorch. |
| [FinRL-Trading](https://github.com/AI4Finance-Foundation/FinRL-Trading) | 3.2k ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL-Trading?style=flat-square) | Ensemble strategy using DRL for automated stock trading (ICAIF 2020). |
| [gym-anytrading](https://github.com/AminHP/gym-anytrading) | 2.4k ![Stars](https://img.shields.io/github/stars/AminHP/gym-anytrading?style=flat-square) | OpenAI Gym trading environment for reinforcement learning. |
| [FinRL-Meta](https://github.com/AI4Finance-Foundation/FinRL-Meta) | 1.9k ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL-Meta?style=flat-square) | Dynamic market environments and standardized datasets for financial RL. |

---

## Machine Learning

General machine learning approaches for financial prediction, alpha generation, and quantitative investment.

| Project | Stars | Description |
|---------|-------|-------------|
| [Qlib](https://github.com/microsoft/qlib) | 44.0k ![Stars](https://img.shields.io/github/stars/microsoft/qlib?style=flat-square) | Microsoft's AI-oriented quantitative investment platform with full ML pipeline. Supports alpha mining, model training, and backtesting. |
| [ML for Trading](https://github.com/stefan-jansen/machine-learning-for-trading) | 18.7k ![Stars](https://img.shields.io/github/stars/stefan-jansen/machine-learning-for-trading?style=flat-square) | Code for the book *Machine Learning for Algorithmic Trading*. Comprehensive guide on using ML to add value to trading strategies. |
| [Stock-Prediction-Models](https://github.com/huseinzol05/Stock-Prediction-Models) | 9.4k ![Stars](https://img.shields.io/github/stars/huseinzol05/Stock-Prediction-Models?style=flat-square) | Collection of ML and deep learning models for stock forecasting, including transformers, LSTMs, and more. |
| [ai_quant_trade](https://github.com/charliedream1/ai_quant_trade) | 5.7k ![Stars](https://img.shields.io/github/stars/charliedream1/ai_quant_trade?style=flat-square) | Comprehensive AI stock trading platform covering LLMs, factor mining, ML/DL/RL, graph networks, and HFT strategies. |
| [stockpredictionai](https://github.com/borisbanushev/stockpredictionai) | 5.6k ![Stars](https://img.shields.io/github/stars/borisbanushev/stockpredictionai?style=flat-square) | Complete process for predicting stock price movements using deep learning. |
| [TF Quant Finance](https://github.com/google/tf-quant-finance) | 5.4k ![Stars](https://img.shields.io/github/stars/google/tf-quant-finance?style=flat-square) | TensorFlow-based library for quantitative finance by Google. Covers options pricing, volatility models, and more. |
| [QuantsPlaybook](https://github.com/hugo2046/QuantsPlaybook) | 5.2k ![Stars](https://img.shields.io/github/stars/hugo2046/QuantsPlaybook?style=flat-square) | Reproduces 100+ quantitative investment strategies from Chinese brokerage research reports. |
| [MLFinLab](https://github.com/hudson-and-thames/mlfinlab) | 4.8k ![Stars](https://img.shields.io/github/stars/hudson-and-thames/mlfinlab?style=flat-square) | Implementations of methods from *Advances in Financial Machine Learning* by Marcos Lopez De Prado. |
| [Adv_Fin_ML_Exercises](https://github.com/BlackArbsCEO/Adv_Fin_ML_Exercises) | 1.9k ![Stars](https://img.shields.io/github/stars/BlackArbsCEO/Adv_Fin_ML_Exercises?style=flat-square) | Experimental solutions to exercises from *Advances in Financial Machine Learning*. |
| [AlphaPy](https://github.com/ScottfreeLLC/AlphaPy) | 1.7k ![Stars](https://img.shields.io/github/stars/ScottfreeLLC/AlphaPy?style=flat-square) | ML framework for both speculators and data scientists. Automated feature engineering and model selection. |
| [fin-ml](https://github.com/tatsath/fin-ml) | 1.2k ![Stars](https://img.shields.io/github/stars/tatsath/fin-ml?style=flat-square) | Code for case studies in *Machine Learning and Data Science Blueprints for Finance*. |
| [ml-quant-trading](https://github.com/initial-d/ml-quant-trading) | 38 ![Stars](https://img.shields.io/github/stars/initial-d/ml-quant-trading?style=flat-square) | Paper-backed PyTorch research stack for mask-aware multi-factor modeling, ML baselines, portfolio optimization, and vectorized backtesting. |

---

## Quantitative Trading & Backtesting

Frameworks for algorithmic trading, strategy backtesting, and automated trading bots.

| Project | Stars | Description |
|---------|-------|-------------|
| [FreqTrade](https://github.com/freqtrade/freqtrade) | 51.1k ![Stars](https://img.shields.io/github/stars/freqtrade/freqtrade?style=flat-square) | Free, open-source crypto trading bot. Supports backtesting, strategy optimization, and live trading on many exchanges. |
| [vnpy/VeighNa](https://github.com/vnpy/vnpy) | 41.3k ![Stars](https://img.shields.io/github/stars/vnpy/vnpy?style=flat-square) | Python-based open-source quant trading platform. Multi-market gateway support for stocks, futures, options, and crypto. |
| [NautilusTrader](https://github.com/nautechsystems/nautilus_trader) | 23.3k ![Stars](https://img.shields.io/github/stars/nautechsystems/nautilus_trader?style=flat-square) | Production-grade Rust-native trading engine with nanosecond-resolution clock and Python strategy API. |
| [Backtrader](https://github.com/backtrader/backtrader) | 21.8k ![Stars](https://img.shields.io/github/stars/backtrader/backtrader?style=flat-square) | Feature-rich Python framework for backtesting and live trading. Supports multiple data feeds and brokers. |
| [Zipline](https://github.com/quantopian/zipline) | 19.8k ![Stars](https://img.shields.io/github/stars/quantopian/zipline?style=flat-square) | Pythonic event-driven backtesting library, originally powering the Quantopian platform. |
| [QuantConnect/Lean](https://github.com/QuantConnect/Lean) | 19.7k ![Stars](https://img.shields.io/github/stars/QuantConnect/Lean?style=flat-square) | Algorithmic trading engine built for strategy research, backtesting, and live trading. Multi-asset support. |
| [Hummingbot](https://github.com/hummingbot/hummingbot) | 18.8k ![Stars](https://img.shields.io/github/stars/hummingbot/hummingbot?style=flat-square) | Open-source crypto market making and arbitrage bot. Gateway to CeFi and DeFi exchanges. |
| [Abu](https://github.com/bbfamily/abu) | 17.4k ![Stars](https://img.shields.io/github/stars/bbfamily/abu?style=flat-square) | Python quant trading system supporting US/A/HK stocks, futures, options, and Bitcoin with ML-based strategy optimization. |
| [QUANTAXIS](https://github.com/yutiansut/QUANTAXIS) | 10.6k ![Stars](https://img.shields.io/github/stars/yutiansut/QUANTAXIS?style=flat-square) | Distributed quant solution for stocks/futures/options with data, backtesting, simulation, and live trading. |
| [Easytrader](https://github.com/shidenggui/easytrader) | 9.8k ![Stars](https://img.shields.io/github/stars/shidenggui/easytrader?style=flat-square) | Python stock trading automation for Chinese brokers (Tonghuashun/MiniQMT/Xueqiu). |
| [Jesse](https://github.com/jesse-ai/jesse) | 8.0k ![Stars](https://img.shields.io/github/stars/jesse-ai/jesse?style=flat-square) | Advanced algo-trading framework for crypto. Strategy development, backtesting, and live trading. |
| [VectorBT](https://github.com/polakowo/vectorbt) | 7.8k ![Stars](https://img.shields.io/github/stars/polakowo/vectorbt?style=flat-square) | Blazing fast vectorized backtesting and trading analysis using NumPy and Pandas. |
| [ManifoldBT](https://github.com/manifoldbt/manifoldbt) | ![Stars](https://img.shields.io/github/stars/manifoldbt/manifoldbt?style=flat-square) | High-performance Rust-powered Python backtesting: vectorized signals with realistic fills (fees, slippage, look-ahead), parameter sweeps, walk-forward, Monte Carlo. |
| [RQAlpha](https://github.com/ricequant/rqalpha) | 6.4k ![Stars](https://img.shields.io/github/stars/ricequant/rqalpha?style=flat-square) | Extendable Python algorithmic backtesting and trading framework from RiceQuant. |
| [WonderTrader](https://github.com/wondertrader/wondertrader) | 6.1k ![Stars](https://img.shields.io/github/stars/wondertrader/wondertrader?style=flat-square) | High-performance C++ core quant framework with Python layer (wtpy) for research, trading, and operations. |
| [OctoBot](https://github.com/Drakkar-Software/OctoBot) | 6.0k ![Stars](https://img.shields.io/github/stars/Drakkar-Software/OctoBot?style=flat-square) | Open-source crypto trading bot for AI, Grid, DCA, and TradingView strategies on 15+ exchanges. |
| [Krypto-trading-bot](https://github.com/ctubio/Krypto-trading-bot) | 3.7k ![Stars](https://img.shields.io/github/stars/ctubio/Krypto-trading-bot?style=flat-square) | Self-hosted C++ high-frequency crypto market-making bot with sub-millisecond order execution. |
| [Hikyuu](https://github.com/fasiondog/hikyuu) | 3.2k ![Stars](https://img.shields.io/github/stars/fasiondog/hikyuu?style=flat-square) | C++/Python ultra-high-speed quant research framework for A-share market. |
| [bt](https://github.com/pmorissette/bt) | 2.9k ![Stars](https://img.shields.io/github/stars/pmorissette/bt?style=flat-square) | Flexible backtesting framework for Python with modular algorithm stacks and portfolio-level strategy testing. |
| [HFT-LOB-Trading-ML](https://github.com/rorysroes/SGX-Full-OrderBook-Tick-Data-Trading-Strategy) | 2.3k ![Stars](https://img.shields.io/github/stars/rorysroes/SGX-Full-OrderBook-Tick-Data-Trading-Strategy?style=flat-square) | High-frequency trading strategies using ML on full order book tick data. |
| [barter-rs](https://github.com/barter-rs/barter-rs) | 2.2k ![Stars](https://img.shields.io/github/stars/barter-rs/barter-rs?style=flat-square) | Open-source Rust framework for building event-driven live-trading and backtesting systems. |
| [Zipline-Reloaded](https://github.com/stefan-jansen/zipline-reloaded) | 1.8k ![Stars](https://img.shields.io/github/stars/stefan-jansen/zipline-reloaded?style=flat-square) | Community-maintained fork of Zipline, compatible with modern Python. Companion to *ML for Algorithmic Trading*. |
| [Lumibot](https://github.com/Lumiwealth/lumibot) | 1.6k ![Stars](https://img.shields.io/github/stars/Lumiwealth/lumibot?style=flat-square) | Backtestable AI trading agents for stocks, options, crypto, futures, and forex with real broker integration. |
| [AutoTrader](https://github.com/kieran-mackle/AutoTrader) | 1.3k ![Stars](https://img.shields.io/github/stars/kieran-mackle/AutoTrader?style=flat-square) | Python-based platform for development, optimization, and deployment of automated trading systems. |
| [Funcat](https://github.com/cedricporter/funcat) | 1.0k ![Stars](https://img.shields.io/github/stars/cedricporter/funcat?style=flat-square) | Ports Tongdaxin/Tonghuashun financial formula syntax to Python for technical analysis (e.g., `MA(C,5)`). |

---

## Data Sources

Tools and APIs for accessing financial market data — stocks, crypto, forex, and alternative data.

| Project | Stars | Description |
|---------|-------|-------------|
| [OpenBB Terminal](https://github.com/OpenBB-finance/OpenBBTerminal) | 68.5k ![Stars](https://img.shields.io/github/stars/OpenBB-finance/OpenBBTerminal?style=flat-square) | Open-source investment research platform. Access stock, crypto, forex, and macro data with built-in analysis tools. |
| [CCXT](https://github.com/ccxt/ccxt) | 42.8k ![Stars](https://img.shields.io/github/stars/ccxt/ccxt?style=flat-square) | Unified JavaScript/Python/PHP library for 100+ cryptocurrency exchange APIs. Trading and market data. |
| [FinceptTerminal](https://github.com/Fincept-Corporation/FinceptTerminal) | 25.1k ![Stars](https://img.shields.io/github/stars/Fincept-Corporation/FinceptTerminal?style=flat-square) | Modern finance terminal with advanced market analytics, investment research, and economic data tools for interactive exploration. |
| [yfinance](https://github.com/ranaroussi/yfinance) | 24.0k ![Stars](https://img.shields.io/github/stars/ranaroussi/yfinance?style=flat-square) | Download market data from Yahoo Finance. Stocks, ETFs, mutual funds, options, and more. |
| [AKShare](https://github.com/akfamily/akshare) | 20.0k ![Stars](https://img.shields.io/github/stars/akfamily/akshare?style=flat-square) | Elegant Python financial data interface covering A-shares, futures, options, funds, forex, bonds, indices, and crypto from authoritative Chinese sources. |
| [TuShare](https://github.com/waditu/tushare) | 15.1k ![Stars](https://img.shields.io/github/stars/waditu/tushare?style=flat-square) | Financial data interface for Chinese stock markets. Historical and real-time data. |
| [OpenStock](https://github.com/Open-Dev-Society/OpenStock) | 13.0k ![Stars](https://img.shields.io/github/stars/Open-Dev-Society/OpenStock?style=flat-square) | Free open-source market platform alternative with real-time prices, alerts, and company insights. |
| [StockSharp](https://github.com/StockSharp/StockSharp) | 10.0k ![Stars](https://img.shields.io/github/stars/StockSharp/StockSharp?style=flat-square) | Algorithmic trading and quantitative analysis platform. Connects to multiple brokers and exchanges. |
| [FinanceDatabase](https://github.com/JerBouma/FinanceDatabase) | 7.8k ![Stars](https://img.shields.io/github/stars/JerBouma/FinanceDatabase?style=flat-square) | Comprehensive database of 300,000+ symbols: Equities, ETFs, Funds, Indices, Currencies, and Crypto. |
| [FinanceToolkit](https://github.com/JerBouma/FinanceToolkit) | 4.9k ![Stars](https://img.shields.io/github/stars/JerBouma/FinanceToolkit?style=flat-square) | Transparent financial analysis with 150+ ratios, indicators, and performance measurements. |
| [AData](https://github.com/1nchaos/adata) | 4.6k ![Stars](https://img.shields.io/github/stars/1nchaos/adata?style=flat-square) | Free open-source A-share quant trading database with multi-source data fusion and dynamic proxy. |
| [Binance](https://github.com/binance/binance-connector-python) | 2.9k ![Stars](https://img.shields.io/github/stars/binance/binance-connector-python?style=flat-square) | Official Python connector for Binance APIs. Spot, futures, and market data. |
| [ArcticDB](https://github.com/man-group/ArcticDB) | 2.4k ![Stars](https://img.shields.io/github/stars/man-group/ArcticDB?style=flat-square) | High-performance serverless DataFrame database by Man Group for petabyte-scale time-series and tick data. |
| [EdgarTools](https://github.com/dgunning/edgartools) | 2.3k ![Stars](https://img.shields.io/github/stars/dgunning/edgartools?style=flat-square) | Read and analyze SEC EDGAR filings in Python (10-K, 8-K, XBRL, 13F). |
| [FinRL-Meta](https://github.com/AI4Finance-Foundation/FinRL-Meta) | 1.9k ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL-Meta?style=flat-square) | Dynamic datasets and market environments for stock, crypto, and forex. |
| [Alpaca](https://github.com/alpacahq/alpaca-py) | 1.4k ![Stars](https://img.shields.io/github/stars/alpacahq/alpaca-py?style=flat-square) | Official Python SDK for Alpaca. Commission-free stock trading API with paper/live trading. |
| [jqdatasdk](https://github.com/JoinQuant/jqdatasdk) | 1.3k ![Stars](https://img.shields.io/github/stars/JoinQuant/jqdatasdk?style=flat-square) | JoinQuant's Python data SDK for Chinese financial market data. |
| [DeFiLlama Adapters](https://github.com/DefiLlama/DefiLlama-Adapters) | 1.2k ![Stars](https://img.shields.io/github/stars/DefiLlama/DefiLlama-Adapters?style=flat-square) | Open-source DeFi TVL calculation adapters for 2,400+ protocols across 180+ blockchains. |
| [WRDS](https://github.com/wharton/wrds) | 155 ![Stars](https://img.shields.io/github/stars/wharton/wrds?style=flat-square) | Python interface to Wharton Research Data Services for academic financial research. |
| [0xArchive](https://0xarchive.io/) | – | Real-time and historical Hyperliquid and Lighter market data via REST and WebSocket APIs. |
| [The Stall](https://github.com/thebrierfox/the-stall) | ![Stars](https://img.shields.io/github/stars/thebrierfox/the-stall?style=flat-square) | MCP server with 173 financial market data capabilities — stocks, ETFs, crypto, DeFi, options, SEC filings, earnings, analyst ratings, and macro indicators. Pay-per-call via x402 micropayments on Base; no API keys required. |
| [AgentServices](https://agentservices.to) | ![Stars](https://img.shields.io/github/stars/vbkotecha/aiservices-api?style=flat-square) | 54-service x402-paid API platform for AI agents — crypto market data, onchain analytics, financial intelligence, and inference endpoints. MCP server with 37 tools. Pay-per-call via x402 on Base; no API keys required. |
| [Market Brief](https://github.com/beepboop2025/market-brief) | ![Stars](https://img.shields.io/github/stars/beepboop2025/market-brief?style=flat-square) | Free browser app and Python helper for selected funding, capital-market, and liquidity observations, with source links, observation dates, and optional local baseline comparisons. |

---

## Technical Analysis

Libraries for computing technical indicators and performing quantitative analysis on market data.

| Project | Stars | Description |
|---------|-------|-------------|
| [TA-Lib](https://github.com/mrjbq7/ta-lib) | 12.0k ![Stars](https://img.shields.io/github/stars/mrjbq7/ta-lib?style=flat-square) | Python wrapper for TA-Lib. 200+ technical analysis functions: candlestick patterns, momentum, volatility, and more. |
| [ta](https://github.com/bukosabino/ta) | 5.1k ![Stars](https://img.shields.io/github/stars/bukosabino/ta?style=flat-square) | Technical analysis library using Pandas and NumPy. Includes 40+ indicators out of the box. |
| [Clairvoyant](https://github.com/anfederico/Clairvoyant) | 2.4k ![Stars](https://img.shields.io/github/stars/anfederico/Clairvoyant?style=flat-square) | Identify and monitor social/historical cues for short-term stock movement. |
| [Funcat](https://github.com/cedricporter/funcat) | 1.0k ![Stars](https://img.shields.io/github/stars/cedricporter/funcat?style=flat-square) | Tongdaxin/Tonghuashun financial formula syntax ported to Python (e.g., `MA(C,5)`, `CROSS(MA5, MA10)`). |

---

## Portfolio Management & Risk

- [My AI Investment OS](https://ordinarymantrying.com/tools/ai-invest-os.html) - Free 5-question diagnostic that identifies your investing school (Index/Value/Growth/Trend), delivers an 8-AI committee verdict, and generates a personalized Prompt Library. Includes 6 companion tools: DCA Simulator, Recovery Navigator, Dividend Engine, Kelly Master, Pyramid Builder, Portfolio Clarity. No login required.

Tools for portfolio optimization, risk analysis, asset allocation, and performance analytics.

| Project | Stars | Description |
|---------|-------|-------------|
| [QuantStats](https://github.com/ranaroussi/quantstats) | 7.2k ![Stars](https://img.shields.io/github/stars/ranaroussi/quantstats?style=flat-square) | Portfolio analytics for quants with in-depth performance metrics, risk analytics, tear sheets, and HTML reports. |
| [Pyfolio](https://github.com/quantopian/pyfolio) | 6.3k ![Stars](https://img.shields.io/github/stars/quantopian/pyfolio?style=flat-square) | Portfolio and risk analytics in Python with comprehensive tear sheet analysis. |
| [PyPortfolioOpt](https://github.com/robertmartin8/PyPortfolioOpt) | 5.8k ![Stars](https://img.shields.io/github/stars/robertmartin8/PyPortfolioOpt?style=flat-square) | Portfolio optimization in Python. Classical efficient frontier, Black-Litterman, Hierarchical Risk Parity, and more. |
| [Riskfolio-Lib](https://github.com/dcajasn/Riskfolio-Lib) | 4.2k ![Stars](https://img.shields.io/github/stars/dcajasn/Riskfolio-Lib?style=flat-square) | Portfolio optimization and quantitative strategic asset allocation. Supports 20+ risk measures. |
| [ffn](https://github.com/pmorissette/ffn) | 2.6k ![Stars](https://img.shields.io/github/stars/pmorissette/ffn?style=flat-square) | Financial functions library for Python: performance measurement, data transformations, and portfolio analytics. |
| [Empyrical](https://github.com/quantopian/empyrical) | 1.5k ![Stars](https://img.shields.io/github/stars/quantopian/empyrical?style=flat-square) | Common financial risk and performance metrics (Sharpe, Sortino, max drawdown). Used by Zipline and Pyfolio. |
| [OLPS](https://github.com/OLPS/OLPS) | 357 ![Stars](https://img.shields.io/github/stars/OLPS/OLPS?style=flat-square) | Toolbox for On-Line Portfolio Selection strategies. |

---

## Sentiment Analysis & NLP

Tools for extracting trading signals from text — news, social media, SEC filings, and earnings calls.

| Project | Stars | Description |
|---------|-------|-------------|
| [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) | 20.4k ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinGPT?style=flat-square) | Financial LLMs with built-in sentiment analysis capabilities via fine-tuning. |
| [VADER](https://github.com/cjhutto/vaderSentiment) | 5.0k ![Stars](https://img.shields.io/github/stars/cjhutto/vaderSentiment?style=flat-square) | Valence Aware Dictionary and sEntiment Reasoner. Rule-based sentiment analysis tool, widely used for financial social media and news text. |
| [FinBERT](https://github.com/ProsusAI/finBERT) | 2.1k ![Stars](https://img.shields.io/github/stars/ProsusAI/finBERT?style=flat-square) | Pre-trained NLP model for financial sentiment analysis. Fine-tuned on financial communication text. |

---

## Quantitative Finance Libraries

Core quantitative finance libraries for derivatives pricing, risk management, and financial modeling.

| Project | Stars | Description |
|---------|-------|-------------|
| [gs-quant](https://github.com/goldmansachs/gs-quant) | 10.5k ![Stars](https://img.shields.io/github/stars/goldmansachs/gs-quant?style=flat-square) | Goldman Sachs Python toolkit for quantitative finance, derivatives pricing, and risk analytics. |
| [QuantLib](https://github.com/lballabio/QuantLib) | 7.2k ![Stars](https://img.shields.io/github/stars/lballabio/QuantLib?style=flat-square) | The canonical open-source C++ library for quantitative finance: derivatives pricing, fixed income, and risk management. |
| [RustQuant](https://github.com/avhz/RustQuant) | 1.8k ![Stars](https://img.shields.io/github/stars/avhz/RustQuant?style=flat-square) | Rust library for quantitative finance covering stochastic processes, options pricing, bonds, and Monte Carlo methods. |

---

## Trading Platforms

End-to-end platforms for algorithmic trading with broker integration.

| Project | Stars | Description |
|---------|-------|-------------|
| [QuantConnect/Lean](https://github.com/QuantConnect/Lean) | 19.7k ![Stars](https://img.shields.io/github/stars/QuantConnect/Lean?style=flat-square) | Algorithmic trading engine. Multi-asset support with cloud integration for backtesting and live trading. |
| [StockSharp](https://github.com/StockSharp/StockSharp) | 10.0k ![Stars](https://img.shields.io/github/stars/StockSharp/StockSharp?style=flat-square) | Algorithmic trading for stocks, forex, crypto, and options. GUI and API-based development. |
| [FinRL-X](https://github.com/AI4Finance-Foundation/FinRL-Trading) | 3.2k ![Stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL-Trading?style=flat-square) | AI-native modular infrastructure for quantitative trading. Unifies data processing, strategy construction, backtesting, and broker execution with RL/LLM support. [Paper](https://arxiv.org/abs/2603.21330) |

---

## Visualization & Rendering

Tools for visualizing market data, trading activity, and agent performance.

| Project | Stars | Description |
|---------|-------|-------------|
| [KLinePic MCP](https://github.com/sher1096/klinepic-agent-api-examples) | ![Stars](https://img.shields.io/github/stars/sher1096/klinepic-agent-api-examples?style=flat-square) | First-party MCP server and [Agent API](https://klinepic.com/guides/trade-review-chart-api/?utm_source=github&utm_medium=referral&utm_campaign=geo202607) for turning broker or exchange fills into annotated candlestick trade-review charts. Supports A-shares, US stocks, crypto, and futures; post-trade review only, with no signals or order execution. |
| [mplfinance](https://github.com/matplotlib/mplfinance) | 4.4k ![Stars](https://img.shields.io/github/stars/matplotlib/mplfinance?style=flat-square) | Financial data visualization using Matplotlib. Candlestick charts, OHLC, Renko, and more. |
| [TradingGym](https://github.com/Yvictor/TradingGym) | 1.9k ![Stars](https://img.shields.io/github/stars/Yvictor/TradingGym?style=flat-square) | Toolkit for training and backtesting RL algorithms with real-time rendering. |

---

## High Performance Computing

| Project | Stars | Description |
|---------|-------|-------------|
| [NumPy](https://github.com/numpy/numpy) | 32.1k ![Stars](https://img.shields.io/github/stars/numpy/numpy?style=flat-square) | The fundamental package for scientific computing with Python. Foundation for most quantitative finance libraries. |
| [Azure HPC](https://azure.microsoft.com/en-us/solutions/high-performance-computing/financial-services/) | - | Azure high-performance computing for financial services — risk simulation, pricing, and analytics. |

---

## Research Papers & Surveys

Key academic papers on AI in finance.

### Surveys

- Hambly, Ben, Renyuan Xu, and Huining Yang. "[Recent Advances in Reinforcement Learning in Finance](https://arxiv.org/abs/2112.04553)." *arXiv preprint arXiv:2112.04553*, 2021.
- "[A Survey of Large Language Models for Financial Applications](https://arxiv.org/abs/2402.02315)." *arXiv*, 2024. Covers FinGPT, BloombergGPT, and domain-specific fine-tuning.
- "[FinAgent: A Multimodal Foundation Agent for Financial Trading](https://arxiv.org/abs/2402.18485)." *arXiv*, 2024. Multimodal agent processing text, tables, and charts.
- "[FinRobot: An Open-Source AI Agent Platform for Financial Applications](https://arxiv.org/abs/2405.14767)." *arXiv*, 2024.
- "[Data-Centric FinGPT: Open-Source Financial Large Language Models](https://arxiv.org/abs/2307.10485)." *arXiv*, 2023. Data-centric approach to building financial LLMs.

### Selected Papers

- "[Deep Reinforcement Learning for Automated Stock Trading: An Ensemble Strategy](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3690996)." *ICAIF 2020*. The ensemble strategy behind FinRL-Trading.
- "[FinRL: A Deep Reinforcement Learning Library for Automated Stock Trading in Quantitative Finance](https://arxiv.org/abs/2011.09607)." *NeurIPS 2020 Deep RL Workshop*.
- "[FinRL-Meta: Market Environments and Benchmarks for Data-Driven Financial Reinforcement Learning](https://arxiv.org/abs/2211.03107)." *NeurIPS 2022*.
- "[FinMem: A Performance-Enhanced LLM Trading Agent with Layered Memory](https://arxiv.org/abs/2311.13743)." *arXiv*, 2023. Novel memory architecture for LLM trading agents.
- "[FinGPT: Open-Source Financial Large Language Models](https://arxiv.org/abs/2306.06031)." *arXiv*, 2023. Democratizing financial LLMs with a data-centric approach and accessible fine-tuning.
- "[TradingAgents: Multi-Agents LLM Financial Trading Framework](https://arxiv.org/abs/2412.20138)." *arXiv*, 2024.

---

## Books

- Giller, Graham L. *Adventures in Financial Data Science*. Giller Investments, 2020.
- Jansen, Stefan. *Machine Learning for Algorithmic Trading*. 2nd ed. Packt, 2020. [Code](https://github.com/stefan-jansen/machine-learning-for-trading)
- De Prado, Marcos Lopez. *Advances in Financial Machine Learning*. Wiley, 2018.
- Tatsat, Hariom, Sahil Puri, and Brad Lookabaugh. *Machine Learning and Data Science Blueprints for Finance*. O'Reilly, 2020. [Code](https://github.com/tatsath/fin-ml)
- Dixon, Matthew F., Igor Halperin, and Paul Bilokon. *Machine Learning in Finance: From Theory to Practice*. Springer, 2020.

---

## Contributing

Contributions are welcome! If you have suggestions for new projects or improvements:

1. Fork this repository.
2. Add your project in the appropriate section, following the existing format.
3. Submit a pull request with a brief description of the addition.

**Selection criteria**: Projects should be actively maintained, well-documented, and provide genuine value to the AI for finance community. We particularly welcome:
- Open-source tools with demonstrated community adoption
- Research projects with accompanying papers
- Frameworks that solve real problems in quantitative finance

---

## License

This project is licensed under the [MIT License](LICENSE).

---

**Feedback**: If you have any ideas or want content added to this list, feel free to [open an issue](https://github.com/AI4Finance-Foundation/Awesome_AI4Finance/issues) or [submit a PR](https://github.com/AI4Finance-Foundation/Awesome_AI4Finance/pulls).
- [BDE Score™](https://github.com/hbhqq9/bde-score) - AI-Powered Multi-Market Stock Analysis — transparent multi-factor scoring for 73 stocks across US, HK, and A-share markets. EU AI Act Art.50 compliant.
