# Hi, I'm Omar 👋

I'm an applied AI scientist with a PhD in Supply Chain & Operations Management and a background spanning MIT, RAND, and MITRE. I build data-driven solutions for supply chain, logistics, and trade problems, from predictive models and risk assessment to optimization and simulation.

**Open to:** Principal / Senior Applied Scientist, Data Scientist, Research Scientist, and ML Engineer roles, ideally in supply chain, operations, logistics, transportation, or international trade.

## Featured projects

**[Forecast-then-Optimize Inventory](https://github.com/oelwakil/inventory-forecast-optimization)**
Does a better demand forecast mean less inventory? LightGBM and a probabilistic PyTorch model forecast 500 store-item series that feed a lost-sales inventory simulation. At a 98% fill rate, LightGBM needs about half the stock of the better simple benchmark. Ordering from the forecast distribution cuts cost about 5% against a classic safety-stock rule, and a PPO reinforcement-learning agent beats a tuned (s, S) policy by 3.5% when orders carry a fixed cost. Built with leakage-safe features, validation-only tuning, bootstrap confidence intervals, and 21 tests.

**[Supply Chain Cascade Testbed (GNN)](https://github.com/oelwakil/supply-chain-cascade-gnn)**
When a shock hits a multi-tier supply network, can a graph neural network predict which entities lose capacity, including those several tiers downstream? On a synthetic network the models never saw, graph attention reaches 0.44 average precision on indirect effects (two or more hops from the shock), against 0.04 for a direct-exposure score and 0.11 for gradient boosting on one-hop features. The result holds under realistic missing-link patterns and with ensemble-calibrated probabilities. It also reports where a simple reachability count matches the GNNs, in choosing which suppliers to harden.

**[Used Car Price Prediction](https://github.com/oelwakil/used-car-price-prediction)**
Feature engineering, linear vs. boosted models, Optuna tuning, and SHAP explanations on Indian used car listings (MIT Applied AI & Data Science capstone).

## What I work on
- **Applied ML:** regression, classification, anomaly detection, clustering, deep learning (ANNs, CNNs, GNNs)
- **Forecasting & optimization:** time series, inventory simulation, stochastic and heuristic optimization
- **Generative AI:** LLMs, RAG, agentic workflows
- **Economics & trade:** econometrics, causal inference, spatial analysis
- - **Applied ML:** regression, classification, anomaly detection, clustering, deep learning (ANNs, CNNs, GNNs), reinforcement learning (PPO)
- **Forecasting & optimization:** time series, probabilistic forecasting, inventory simulation, stochastic and heuristic optimization

## Tools
Python · pandas · scikit-learn · statsmodels · LightGBM · XGBoost · CatBoost · Optuna · SHAP · TensorFlow/Keras · R · SQL

## Connect
[LinkedIn](https://linkedin.com/in/oelwakil)
