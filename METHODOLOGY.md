# S&P-Style Crypto Index Engine

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Quant Research](https://img.shields.io/badge/Field-Quant_Finance-blue)

Professional cryptocurrency index builder replicating S&P Global methodologies.

## Index Composition
![S&P Crypto Index](https://raw.githubusercontent.com/ArpitPandey9/SP-Crypto-Index-Engine/main/snp_crypto_index.png)

## Key Features
- Free-float adjusted market cap weighting
- Liquidity screening ($1M+ daily volume)
- Automated daily reports
- Anomaly detection integration

 
## Free-Float Adjustment Factors  
| Asset      | Factor | Reason                          |  
|------------|--------|---------------------------------|  
| Bitcoin    | 78%    | Lost coins, long-term holdings  |  
| Ethereum   | 85%    | Moderate staking                |  
| Tether     | 95%    | High circulation stability      |  
| Default    | 80%    | General assumption              |  

## Liquidity Screening Criteria  
- Minimum daily volume: $1,000,000 USD  
- Must be traded on ≥ 3 reputable exchanges  
- Stablecoin trading pairs required  

## Rebalancing Rules  
- Monthly review (first Friday of month)  
- 5% buffer zone for weight changes  
- Emergency rebalance if >30% price move in 24h  
