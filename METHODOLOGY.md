# S&P-Style Crypto Index Engine

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Professional cryptocurrency index builder replicating S&P Global methodologies.

## Index Composition
![Index Composition](https://raw.githubusercontent.com/ArpitPandey9/SP-Crypto-Index-Engine/main/snp_crypto_index.png)

## Key Features
- Free-float adjusted market cap weighting
- Liquidity screening ($1M+ daily volume)
- Automated daily reports
- Anomaly detection integration

## Usage
```python
# To generate the index
run_index_engine()
## Free-Float Adjustment Factors  
| Coin       | Adjustment Factor | Reason                     |  
|------------|-------------------|----------------------------|  
| Bitcoin    | 78%               | Lost coins, long-term holds |  
| Ethereum   | 85%               | Moderate staking           |  
| Stablecoins| 95%               | High circulation           |  
