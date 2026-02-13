# Data Science Projects 2026

## INCO9X1: Introduction to Coding for Data Science

### U.J. | M.F.E. Programme

---

## Project Overview

In this course, students undertake comprehensive data science projects that address topical issues currently shaping South Africa and the financial sector. These projects constitute **40%** of the final grade distribution:

- **15%** - Written Report Document
- **15%** - Coding File (Python, presented in PDF format)
- **10%** - Project Presentation

### Project Submission Deadline

**May 22, 2026, at 23:59 South African Time**

---

## Project Requirements

### Group Formation
- Students must form groups of **three (3) members**
- Submit group member list to me
- Include chosen project topic

### Technical Requirements
- Use techniques covered in class
- Include detailed code comments
- Submit Python code as PDF
- Provide comprehensive written report
- Prepare professional presentation

### Required Techniques
Projects leverage key topics including:
- Python programming
- Data preprocessing
- Machine learning algorithms
- Natural Language Processing (NLP)
- Bayesian networks
- Deep learning architectures
- Advanced neural networks

---

## Project Topics

### DATABASE DESIGN and PYTHON PIPELINES

#### Project 0: Real-Time Financial Market Database System

**Data to be Used:**
- Yahoo Finance API: JSE Top 40 stocks (real-time prices via yfinance)
- Alpha Vantage API: Intraday data, technical indicators
- SARB: Historical interest rates, exchange rates (CSV downloads)
- JSE SENS announcements (web scraping)
- Company fundamentals (earnings, dividends, splits)

**Objectives:**
- Design normalized MySQL database schema (3NF) for multi-asset financial market data
- Implement fact tables: stock_prices, options_data, forex_rates, commodities
- Implement dimension tables: companies, sectors, exchanges, calendar_dates
- Build Python ETL pipeline using functions, loops, and error handling to:
  - **Extract**: Fetch data from APIs every 15 minutes (or daily)
  - **Transform**: Clean data, handle missing values, calculate technical indicators (SMA, RSI, MACD)
  - **Load**: Insert/update records in MySQL using pymysql or SQLAlchemy
- Implement data validation: check for duplicates, outliers, data type constraints
- Create stored procedures and triggers for automated data quality checks
- Write complex SQL queries for financial analysis:
  - Top 10 gainers/losers by sector
  - 52-week high/low calculations
  - Moving average crossover signals
  - Portfolio performance attribution queries
- Build Python dashboard (Streamlit/Flask) querying MySQL for real-time portfolio monitoring

**Technologies:** Python, MySQL, pymysql/SQLAlchemy, pandas, yfinance, schedule (for automation)

---

### CLUSTERING and UNSUPERVISED LEARNING PROJECTS

#### Project 1: JSE Stock Clustering for Portfolio Construction Using Machine Learning

**Data to be Used:**
- Yahoo Finance: JSE Top 40 and All Share constituents (daily prices, volumes)
- SARB: Interest rates, exchange rates
- Company financials from annual reports (market cap, P/E, sector)

**Objectives:**
- Apply K-Means, DBSCAN, and hierarchical clustering to group JSE stocks based on returns, volatility, sector, and fundamental metrics
- Discover natural market segments beyond traditional sector classifications
- Build diversified portfolios using cluster representatives to minimize correlation
- Compare cluster-based portfolios vs. sector-based portfolios using Sharpe ratio and maximum drawdown
- Validate clusters using silhouette scores and dendrograms

**Techniques:** K-Means clustering, hierarchical clustering, DBSCAN, dimensionality reduction (PCA, t-SNE), portfolio optimization

#### Project 2: Credit Risk Segmentation of South African Corporate Bonds

**Data to be Used:**
- JSE bond market data (yields, credit ratings)
- Company financial statements (leverage ratios, interest coverage, profitability)
- Macroeconomic indicators from SARB
- Default data from rating agencies (if available)

**Objectives:**
- Cluster SA corporate bonds based on credit risk characteristics
- Identify homogeneous risk groups using financial ratios and bond features
- Develop risk-based pricing strategies for different clusters
- Predict probability of rating downgrades using cluster membership
- Compare unsupervised clustering results with actual credit ratings

**Techniques:** Clustering (K-Means, Gaussian Mixture Models), feature engineering, anomaly detection, credit scoring

#### Project 3: Cryptocurrency Market Segmentation and Trading Strategy Development

**Data to be Used:**
- CoinGecko/CoinMarketCap API: Crypto prices in ZAR (Bitcoin, Ethereum, Altcoins)
- Trading volume, market cap, volatility metrics
- VALR/Luno exchange data for South African crypto markets

**Objectives:**
- Cluster cryptocurrencies based on price behavior, volatility, and correlation patterns
- Identify crypto assets with similar risk-return profiles
- Develop cluster-based rotation strategies (momentum within clusters)
- Test whether crypto clusters provide diversification for SA investors
- Analyze ZAR premium dynamics across clusters

**Techniques:** Time series clustering, K-Means, correlation analysis, backtesting trading strategies

---

### NLP PROJECTS: TEXT VECTORIZATION and TOPIC MODELING

#### Project 4: Topic Modeling of JSE-Listed Company Annual Reports

**Data to be Used:**
- Annual reports and financial statements from JSE-listed companies (2015-2025)
- MD&A (Management Discussion & Analysis) sections
- Chairman's statements and CEO letters
- Company announcements from SENS (Stock Exchange News Service)

**Objectives:**
- Apply LDA and LSA to extract latent topics from corporate reports
- Identify emerging business themes and strategic shifts
- Correlate topic distributions with stock performance
- Detect early warning signals of financial distress through topic changes
- Compare topic evolution across industries and market cap segments

**Techniques:** Topic modeling (LDA, LSA, NMF), TF-IDF vectorization, text preprocessing, visualization (pyLDAvis)

#### Project 5: Sentiment Analysis of SARB Monetary Policy Statements

**Data to be Used:**
- SARB Monetary Policy Committee (MPC) statements (2010-2025)
- SARB Governor speeches and press releases
- JSE All Share Index and bond yields around announcement dates
- Inflation and repo rate data

**Objectives:**
- Extract topics from SARB policy statements using LDA
- Quantify hawkish vs. dovish sentiment using dictionary-based and ML methods
- Predict bond and equity market reactions to MPC announcements
- Build text-based indicators for monetary policy stance
- Test whether textual analysis improves forecasts beyond rate changes alone

**Techniques:** Topic modeling (LDA), sentiment analysis, TF-IDF, regression analysis, event study methodology

#### Project 6: News-Based Alpha: Extracting Trading Signals from Financial News

**Data to be Used:**
- Financial news articles (Business Day, Moneyweb, Bloomberg, Reuters)
- JSE stock prices and trading volumes
- Company-specific news from SENS
- Web scraping of news headlines

**Objectives:**
- Build document-term matrices using TF-IDF for financial news corpus
- Apply LDA to discover latent topics in financial news
- Extract sentiment scores for individual stocks and sectors
- Develop news-based trading strategies (long stocks with positive news sentiment)
- Backtest alpha generation from news signals on JSE equities

**Techniques:** Web scraping, TF-IDF, topic modeling (LDA), sentiment scoring, backtesting

---

### WORD EMBEDDINGS and SENTIMENT PREDICTION

#### Project 7: Word2Vec Embeddings for Financial Text: Predicting Stock Movements

**Data to be Used:**
- JSE company announcements and SENS filings
- Financial news headlines (Moneyweb, Business Day)
- Earnings call transcripts (if available)
- JSE stock returns (daily and intraday)

**Objectives:**
- Train Word2Vec (CBOW and Skip-gram) models on financial corpus
- Extract semantic relationships between financial terms (e.g., "dividend" similar to "payout")
- Use word embeddings as features for stock return prediction models
- Compare Word2Vec vs. TF-IDF for sentiment-based trading strategies
- Predict stock price direction using embedding-based features + machine learning

**Techniques:** Word2Vec, feature extraction, sentiment analysis, classification (Logistic Regression, Random Forest, XGBoost)

#### Project 8: Social Media Sentiment and Cryptocurrency Price Prediction

**Data to be Used:**
- Twitter/X data on Bitcoin and Ethereum (using API or scraped)
- Reddit crypto discussions (r/Bitcoin, r/CryptoCurrency)
- BTCZAR and ETHZAR prices from VALR/Luno
- Google Trends data for crypto search volume

**Objectives:**
- Train Word2Vec or GloVe embeddings on crypto social media text
- Extract sentiment scores using pre-trained embeddings + supervised learning
- Predict short-term crypto price movements (1-day, 1-week ahead)
- Test Granger causality between social sentiment and prices
- Build sentiment-based trading strategy and backtest performance

**Techniques:** Word embeddings (Word2Vec, GloVe), sentiment analysis, time series forecasting, Granger causality, backtesting

---

### DEEP LEARNING: ANNs and MLPs

#### Project 9: Deep Neural Networks for Credit Default Prediction

**Data to be Used:**
- Home Credit Default Risk dataset (Kaggle, adapted for SA)
- South African credit bureau data (synthetic or anonymized)
- Macroeconomic variables (unemployment rate, inflation, GDP growth)
- Loan application features (income, debt-to-income ratio, credit history)

**Objectives:**
- Build Multi-Layer Perceptron (MLP) for binary credit default classification
- Handle class imbalance using SMOTE, undersampling, or focal loss
- Compare MLP performance vs. traditional models (Logistic Regression, XGBoost)
- Interpret model predictions using SHAP values for regulatory compliance
- Develop credit scoring system with probability calibration

**Techniques:** Multi-Layer Perceptron (MLP), class imbalance handling, SHAP, hyperparameter tuning, evaluation metrics (AUC-ROC, Precision-Recall)

#### Project 10: Options Pricing Using Neural Networks: Black-Scholes Alternative

**Data to be Used:**
- JSE options data (if available, or use US options as proxy)
- Yahoo Finance: Implied volatility, option Greeks
- Underlying asset prices (JSE stocks, indices)
- Risk-free rate from SARB

**Objectives:**
- Train deep neural network to price European and American options
- Use features: spot price, strike, time to maturity, volatility, interest rate, dividends
- Compare ANN-based prices vs. Black-Scholes model
- Test model performance across different moneyness and maturity ranges
- Explore whether ANNs can capture market frictions ignored by Black-Scholes

**Techniques:** Multi-Layer Perceptron, regression, activation functions, loss functions (MSE, MAE), model validation

---

### CNNs FOR FINANCIAL TIME SERIES

#### Project 11: Candlestick Chart Pattern Recognition Using CNNs

**Data to be Used:**
- Yahoo Finance: OHLCV data for JSE Top 40 stocks
- Generate candlestick chart images programmatically
- Label patterns: doji, hammer, engulfing, morning star, etc.
- Historical price data for pattern backtesting

**Objectives:**
- Convert OHLCV data into candlestick chart images
- Train CNN (ResNet, VGG, custom architecture) to classify chart patterns
- Predict short-term price direction after pattern occurrence
- Backtest pattern-based trading strategy on JSE
- Compare CNN accuracy vs. traditional technical analysis rules

**Techniques:** Convolutional Neural Networks (CNN), image classification, data augmentation, transfer learning, backtesting

#### Project 12: 2D CNN for Financial Time Series: Correlation Matrix Analysis

**Data to be Used:**
- Yahoo Finance: JSE sector indices and individual stocks
- Construct rolling correlation matrices (images)
- Macroeconomic regime indicators (bull/bear markets, recessions)

**Objectives:**
- Convert rolling correlation matrices of stock returns into 2D images
- Train CNN to classify market regimes (high volatility, crisis, calm)
- Predict regime switches using correlation structure
- Develop regime-adaptive portfolio strategies
- Visualize learned convolutional filters to interpret correlation patterns

**Techniques:** 2D CNN, image representation of time series, regime detection, portfolio management

---

### RNNs & LSTMs FOR FINANCIAL FORECASTING

#### Project 13: USD/ZAR Exchange Rate Forecasting Using LSTM Networks

**Data to be Used:**
- SARB: Daily USD/ZAR exchange rates (2010-2025)
- Commodity prices (gold, platinum, oil) - South Africa is commodity exporter
- Interest rate differentials (US Fed Funds vs. SARB repo rate)
- Economic indicators (trade balance, inflation, GDP growth)

**Objectives:**
- Train LSTM/GRU to forecast USD/ZAR exchange rate (1-day, 1-week, 1-month ahead)
- Incorporate multivariate features (commodities, rates, macro variables)
- Compare LSTM vs. ARIMA, GARCH, and random walk models
- Test forecasting accuracy using RMSE, MAE, directional accuracy
- Develop FX trading strategy based on LSTM predictions

**Techniques:** LSTM, GRU, multivariate time series, sequence-to-sequence models, walk-forward validation, backtesting

#### Project 14: High-Frequency Trading Strategy Using RNNs

**Data to be Used:**
- Intraday tick data for liquid JSE stocks (if available, or simulate)
- Order book features (bid-ask spread, depth, order imbalance)
- Technical indicators (RSI, MACD, Bollinger Bands)
- Volume-weighted average price (VWAP)

**Objectives:**
- Build RNN/LSTM to predict short-term price movements (next 5 minutes, 1 hour)
- Use high-frequency features (lagged returns, order flow, volatility)
- Develop intraday mean-reversion or momentum strategies
- Account for transaction costs and market impact
- Backtest HFT strategy with realistic execution assumptions

**Techniques:** RNN, LSTM, high-frequency data analysis, feature engineering, backtesting, transaction cost modeling

#### Project 15: Portfolio Risk Forecasting Using Sequence Models

**Data to be Used:**
- Yahoo Finance: JSE portfolio constituents (daily returns)
- Realized volatility and covariance matrices
- VIX-equivalent for SA (if available, or construct volatility index)
- Macroeconomic uncertainty proxies

**Objectives:**
- Train LSTM to forecast portfolio volatility and Value-at-Risk (VaR)
- Model time-varying covariance structure using RNN
- Compare LSTM-based VaR vs. GARCH, Historical Simulation, Parametric VaR
- Backtest VaR predictions using violation ratios (Kupiec test)
- Develop dynamic risk management framework

**Techniques:** LSTM, volatility forecasting, Value-at-Risk (VaR), backtesting, risk management

---

### GANs FOR SYNTHETIC FINANCIAL DATA

#### Project 16: Generating Synthetic Market Scenarios Using GANs

**Data to be Used:**
- Yahoo Finance: JSE All Share Index and constituent returns
- Historical crisis periods (2008, 2020, SA-specific shocks)
- Volatility and correlation data
- Economic stress indicators

**Objectives:**
- Train GAN (Vanilla GAN, WGAN, TimeGAN) to generate synthetic return paths
- Ensure generated scenarios preserve statistical properties (mean, volatility, skewness, kurtosis)
- Validate synthetic data using KS test, moment matching, correlation structure
- Use synthetic scenarios for stress testing portfolios
- Compare GAN-generated scenarios vs. Monte Carlo simulation

**Techniques:** GANs (WGAN, TimeGAN), synthetic data generation, statistical validation, stress testing

#### Project 17: Conditional GAN for Option Price Surface Generation

**Data to be Used:**
- Options data (JSE or international markets)
- Implied volatility surfaces across strikes and maturities
- Underlying asset characteristics (stock price, sector, beta)

**Objectives:**
- Train Conditional GAN to generate realistic implied volatility surfaces
- Condition on underlying asset features and market regime
- Use generated surfaces for pricing exotic options
- Validate GAN outputs against market-observed surfaces
- Apply to missing/illiquid option data imputation

**Techniques:** Conditional GAN (cGAN), volatility surface modeling, options pricing, data augmentation

---

### TRANSFORMER MODELS FOR FINANCE

#### Project 18: Transformer-Based Stock Return Prediction

**Data to be Used:**
- Yahoo Finance: JSE stocks (prices, returns, volumes)
- Technical indicators (MA, RSI, MACD, Bollinger Bands)
- Fundamental data (P/E, dividend yield, market cap)
- Macroeconomic factors

**Objectives:**
- Apply Transformer architecture (with attention mechanism) to stock return forecasting
- Compare Transformer vs. LSTM/GRU for time series prediction
- Visualize attention weights to interpret which features drive predictions
- Test on multi-step ahead forecasts (1-day, 5-day, 20-day)
- Develop long-short equity strategy based on Transformer predictions

**Techniques:** Transformer models, attention mechanism, multi-step forecasting, feature importance, backtesting

#### Project 19: Fine-Tuning FinBERT for South African Financial Sentiment Analysis

**Data to be Used:**
- Financial news (Business Day, Moneyweb, Bloomberg SA)
- Company announcements from SENS
- Earnings call transcripts (if available)
- Social media financial discussions (Twitter/X)
- Stock price reactions to news

**Objectives:**
- Fine-tune FinBERT (pre-trained on financial text) for SA financial sentiment
- Label training data: positive/negative/neutral sentiment
- Predict stock price movements from sentiment scores
- Build sentiment-based trading strategy for JSE
- Compare FinBERT vs. Word2Vec-based sentiment models

**Techniques:** Transformer fine-tuning (BERT, FinBERT), sentiment analysis, transfer learning, classification, backtesting

---

### LLMs, RAG and AUTOMATED AGENTS

#### Project 20: RAG System for Financial Research: Equity Analysis Assistant

**Data to be Used:**
- JSE company annual reports, financial statements, MD&A
- Analyst reports (if publicly available)
- Financial news archives
- Regulatory filings (SENS announcements)
- Economic research from SARB

**Objectives:**
- Build Retrieval-Augmented Generation (RAG) system using LangChain/LlamaIndex
- Index financial documents in vector database (FAISS, Chroma, Pinecone)
- Create conversational AI assistant for equity research queries
- Answer questions: "What are the key risks for Company X?", "Summarize earnings trends for Sector Y"
- Evaluate retrieval accuracy and answer quality using human evaluation

**Techniques:** RAG, LLMs (GPT-4, Claude, Llama), vector databases, document indexing, semantic search, prompt engineering

#### Project 21: Autonomous Trading Agent Using LLMs and Reinforcement Learning

**Data to be Used:**
- Yahoo Finance: JSE stock prices and market data
- Financial news feeds (real-time or simulated)
- Company fundamentals and technical indicators
- Portfolio performance metrics

**Objectives:**
- Build autonomous trading agent using LLM (GPT-4, Claude) + LangChain
- Agent analyzes market data, news, and portfolio state
- Makes trading decisions (buy/sell/hold) with reasoning explanations
- Incorporate risk management rules (position sizing, stop-loss)
- Backtest agent's performance on historical data
- Compare LLM agent vs. rule-based and ML-based strategies

**Techniques:** LLM agents, prompt engineering, ReAct framework, backtesting, portfolio management, reinforcement learning (optional)

---

## Project Guidelines

### Report Structure
Your written report should include:

1. **Executive Summary** (1 page)
   - Problem statement
   - Methodology overview
   - Key findings
   - Recommendations

2. **Introduction** (2-3 pages)
   - Background and context
   - Significance of the problem
   - Research questions
   - Objectives

3. **Literature Review** (3-4 pages)
   - Review relevant academic papers
   - Discuss existing methodologies
   - Identify research gaps

4. **Data and Methodology** (4-5 pages)
   - Data sources and collection
   - Data preprocessing steps
   - Modeling techniques
   - Evaluation metrics

5. **Results** (5-6 pages)
   - Present findings with visualizations
   - Statistical analysis
   - Model performance
   - Interpretation

6. **Discussion** (2-3 pages)
   - Implications of findings
   - Comparison with literature
   - Limitations
   - Future research

7. **Conclusions and Recommendations** (2-3 pages)
   - Summary of findings
   - Practical recommendations
   - Policy implications

8. **References**
   - APA format
   - Include all cited sources

9. **Appendices**
   - Additional tables/figures
   - Code snippets (selected)

### Code Submission
Submit Python code as PDF with:
- Clear section headers
- Detailed comments explaining logic
- Function documentation
- Output visualizations
- Well-formatted and readable

### Presentation
Prepare a 15-20 minute presentation including:
- Problem introduction (2 mins)
- Methodology (3 mins)
- Key findings (5 mins)
- Visualizations (3 mins)
- Recommendations (3 mins)
- Q&A (4-5 mins)

---

## Evaluation Criteria

### Report (10%)
- Clarity and organization
- Technical depth
- Analysis quality
- Writing quality
- Proper citations

### Code (15%)
- Functionality
- Code quality and documentation
- Appropriate techniques
- Reproducibility
- Comments and explanations

### Presentation (10%)
- Clarity of communication
- Visual aids quality
- Time management
- Response to questions
- Professional delivery

---

## Academic Integrity

### Generative AI Usage
The use of Generative AI tools (ChatGPT, Claude, GitHub Copilot, etc.) is **permitted** but must be disclosed:

- State which AI tools were used
- Describe how they were used
- Include AI-generated content citations
- **Failure to disclose AI usage will result in disqualification and a grade of 0 for the assignment**

**Note:** AI detection tools are regularly used to verify compliance with disclosure requirements.

### Collaboration
- Work within your assigned group only
- No sharing of code/analysis with other groups
- Individual contributions must be documented

### Plagiarism
- All sources must be properly cited
- No copying from online sources without attribution
- Paraphrasing requires citation
- Violations result in disciplinary action

---

## Support and Resources

### Office Hours
- Instructor: By appointment
- Email: johnmu@uj.ac.za; and: jwmm@yorku.ca

### Technical Resources
- Python documentation
- Scikit-learn tutorials
- TensorFlow/Keras guides
- NLP libraries documentation

### Data Sources
- Statistics South Africa
- JSE data
- South African Reserve Bank
- World Bank Open Data
- Kaggle datasets
- Social media APIs (with proper authentication)

### Computing Resources
- UJ computer labs
- Google Colab (free GPU)
- Kaggle notebooks
- Personal computers

---

## Timeline
| Milestone | Date | Deliverable |
|-----------|------|-------------|
| Group Formation | February 14, 2026 | Group list with topic |
| Proposal | March 14, 2026 | 2-page project proposal |
| Progress Update | April 18, 2026 | Preliminary results |
| Final Submission | May 22, 2026, 23:59 | Report + Code + Presentation |
| Presentations | May 16, 2026 | In-class presentations |

---

## Tips for Success
1. **Start Early**: Don't wait until the last minute
2. **Communicate**: Regular team meetings and updates
3. **Iterate**: Test models, refine, improve
4. **Document**: Keep detailed notes throughout
5. **Visualize**: Good charts communicate better than tables
6. **Seek Feedback**: Use office hours and peer reviews
7. **Test Code**: Ensure reproducibility
8. **Proofread**: Check for errors before submission

---

**John Weirstrass MUTEBA MWAMBA, Ph.D.**

For the Master of Financial Engineering Programme

© 2026 Analytics Research Group
