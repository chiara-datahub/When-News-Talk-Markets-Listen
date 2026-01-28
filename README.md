# When News Talk, do Markets listen?
Examining whether interpretative uncertainty in media coverage correlates with stock market volatility.

**Overview**

This repository contains the code, data, and analysis developed for the project When News Talk, Markets Listen. The goal of the project is to investigate whether interpretative uncertainty in media coverage—rather than sentiment polarity alone—is associated with financial market volatility.
To this end, we introduce the Media Disagreement Index (MDI), a measure capturing the dispersion of sentiment signals across social media and news outlets. The analysis focuses on how disagreement and informational disorder evolve over time and how they relate to market dynamics during salient events.


**Methodology Overview**

**Data Sources**:

Social media data (Twitter/X, collected via Apify)
News articles (Google News)
Financial market data (Yahoo Finance)

**Sentiment Analysis**:

- Pre-trained NLP models: NLPTown and CardiffNLP
  
**Index Construction**
  
- Media Disagreement Index (MDI) computed separately for social media and news

**Data Integration**

- Daily aggregation and final merge of media and financial indicators

**Analysis**

- Temporal dynamics of MDI and volatility
- Event-based comparison (e.g. SVB collapse vs. Netflix subscriber loss)
- Network analysis of information diffusion and coordination patterns

**Authors**:

This project was developed as part of an academic research collaboration
