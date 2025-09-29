# GADHT: A Generative Adaptive Decomposition Hierarchical Transformer for Stock Price Forecasting

Official implementation of **GADHT**, as described in the paper:  
*A Generative Adaptive Decomposition Hierarchical Transformer for Stock Price Forecasting* (AI Open, 2025).  
📄 DOI: [10.2139/ssrn.5379116](https://doi.org/10.2139/ssrn.5379116)

---

## 📌 Overview
GADHT is a hybrid forecasting framework that combines:
- **CEEMDAN decomposition** for adaptive multi-scale signal separation,  
- **Generative pretraining via IMF masking and reconstruction**,  
- **Energy-weighted hierarchical Transformers** for robust financial time series prediction.  

The model is evaluated on stock price data with daily OHLCV features, extended to multi-step forecasting horizons (1, 5, and 10 days ahead), and benchmarked against recent baselines.

---

## ⚙️ Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
