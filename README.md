# Energy Equity Intelligence Framework

### Integrated Analysis of Renewable Energy, Oil Markets, and Macroeconomic Signals (2012–2025)

---

## Overview

The **Energy Equity Intelligence Framework** is a financial data science and market intelligence project that examines how renewable energy and traditional oil & gas equities respond to changing commodity-market conditions, macroeconomic trends, and broader financial-market environments.

Using historical data from **April 2012 through December 2025**, the project integrates stock market data, crude oil prices, macroeconomic indicators, and market intelligence signals to evaluate performance, risk, downside exposure, and investment opportunities across the energy sector.

Rather than attempting to predict future stock prices, the framework is designed as a **decision-support and market intelligence system** that helps identify market environments historically associated with stronger subsequent equity performance.

---

## Business Context

The global energy sector is undergoing a historic transformation.

While traditional oil and gas companies continue to play a critical role in global energy supply, renewable energy companies are becoming increasingly important as governments, businesses, and investors accelerate the transition toward cleaner energy sources.

This creates a complex investment environment where energy-sector performance is influenced by:

- Commodity prices
- Interest-rate policy
- Inflation
- Economic growth
- Capital-market conditions
- Investor sentiment

Understanding how these factors interact is essential for investors, analysts, and researchers seeking to evaluate opportunities within the energy sector.

---

## Research Objectives

This project was designed to answer three primary research questions:

### 1. Performance and Risk

How have renewable energy and oil & gas equities performed in terms of:

- Returns
- Volatility
- Downside risk
- Long-term growth

between 2012 and 2025?

### 2. Macroeconomic Sensitivity

To what extent do economic conditions and commodity-market dynamics influence energy-equity performance?

### 3. Market Intelligence Signals

Can market-based and macroeconomic signals help identify periods when energy equities may become attractive for investment consideration?

---

## Companies Analyzed

### Renewable Energy

| Company | Ticker |
|----------|----------|
| NextEra Energy | NEE |
| First Solar | FSLR |
| Enphase Energy | ENPH |

### Oil & Gas

| Company | Ticker |
|----------|----------|
| ExxonMobil | XOM |
| Chevron | CVX |
| ConocoPhillips | COP |

### Market and Commodity Benchmarks

| Asset | Ticker |
|----------|----------|
| S&P 500 Index | ^GSPC |
| Crude Oil Futures | CL=F |

---

## Data Sources

### Financial Market Data

- Yahoo Finance
- Daily adjusted closing prices
- Monthly resampling for analysis

### Macroeconomic Data

Federal Reserve Economic Data (FRED)

| Variable | Description |
|-----------|-------------|
| FEDFUNDS | Federal Funds Rate |
| CPIAUCSL | Consumer Price Index |
| GS10 | 10-Year Treasury Yield |
| GDP | Gross Domestic Product |

### Study Period

**April 2012 – December 2025**

This period captures:

- 2014–2016 oil-price collapse
- Renewable-energy expansion
- COVID-19 market disruption
- Post-pandemic recovery
- Inflation and interest-rate cycles
- Recent energy-market developments

---

## Methodology

The project follows a structured financial analytics workflow consisting of seven stages.

### 1. Data Collection

- Financial market data from Yahoo Finance
- Macroeconomic indicators from FRED
- Equity, commodity, and benchmark data integration

### 2. Data Quality Assessment and Preprocessing

- Missing-value analysis
- Frequency standardization
- Monthly resampling
- Dataset alignment
- Data validation

### 3. Feature Engineering

Created investment-oriented analytical variables including:

- Monthly Returns
- Rolling Volatility
- Drawdowns
- Forward Returns
- Macroeconomic Change Variables
- Market Intelligence Signals
- Composite Opportunity Scores

### 4. Exploratory Data Analysis

Analysis of:

- Return behavior
- Volatility
- Downside risk
- Sector differences
- Market relationships

### 5. Performance and Risk Analysis

Evaluation of:

- Wealth creation
- Growth trajectories
- Risk-adjusted performance
- Drawdown characteristics

### 6. Macroeconomic Sensitivity Analysis

Assessment of relationships between stock returns and:

- Crude oil prices
- Interest rates
- Inflation
- GDP growth
- Treasury yields
- Broad market performance

### 7. Signal Framework Development and Evaluation

Development and testing of a rule-based market intelligence system designed to evaluate whether favorable market conditions are associated with stronger future returns.

---

## Key Features

### Monthly Return Analysis

Calculates and compares monthly returns across renewable and traditional energy companies.

### Rolling Volatility Analysis

Measures changing risk levels through time using six-month rolling volatility.

### Drawdown Analysis

Evaluates downside risk by measuring declines from previous market peaks.

### Market Regime Analysis

Examines stock performance under different market environments, including:

- Rising oil prices
- Falling oil prices
- Bull markets
- Bear markets
- Changing interest-rate conditions

### Macroeconomic Sensitivity Analysis

Evaluates relationships between energy equities and:

- Federal Funds Rate
- Inflation
- GDP Growth
- Treasury Yields
- Crude Oil Prices
- S&P 500 Performance

### Market Intelligence Signal Framework

Develops rule-based investment-monitoring signals that identify historically favorable market environments.

---

## Market Intelligence Signals

### Rate Relief Signal

Activated when the Federal Funds Rate declines or remains unchanged.

**Purpose:** Identify supportive monetary-policy environments.

---

### Oil Momentum Signal

Activated when crude oil generates positive monthly returns.

**Purpose:** Capture favorable commodity-market conditions.

---

### Renewable Advantage Signal

Activated when:

- Interest rates are stable or declining
- Crude oil prices are rising

**Purpose:** Identify environments potentially supportive of renewable-energy equities.

---

### Pullback Signal

Activated when a stock declines by more than 10% during a single month.

**Purpose:** Identify potential recovery opportunities after significant market declines.

---

## Key Findings

### Renewable Energy Delivered Higher Growth

Renewable-energy companies generated substantially stronger average returns than traditional oil & gas companies during the study period.

### Higher Returns Came with Higher Risk

Enphase Energy and First Solar produced the highest return profiles but also exhibited significantly higher volatility and drawdowns.

### NextEra Energy Demonstrated Defensive Characteristics

NextEra Energy delivered renewable-energy exposure while maintaining the lowest volatility and smallest drawdown among the companies analyzed.

### Oil & Gas Firms Showed Strong Commodity Sensitivity

Traditional energy companies exhibited stronger relationships with crude oil prices.

### Broader Market Conditions Matter

The S&P 500 displayed meaningful positive relationships with most energy equities.

### Multi-Factor Signals Show Promise

Periods characterized by multiple favorable market conditions generally produced stronger subsequent returns than isolated signal environments.

---

## Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- yFinance
- Pandas DataReader

### Development Environment

- Jupyter Notebook

---

## Repository Structure

```text
Energy-Equity-Intelligence-Framework/
│
├── README.md
├── requirements.txt
├── Energy_Equity_Intelligence_Framework.ipynb
│
├── figures/
│   ├── growth_of_100.png
│   ├── risk_adjusted_performance.png
│   ├── drawdown_analysis.png
│   ├── market_regime_analysis.png
│   ├── macroeconomic_sensitivity_heatmap.png
│   ├── sector_macro_sensitivity.png
│   └── opportunity_score_performance.png
```

---

## Future Enhancements

Potential future improvements include:

- Portfolio optimization
- CAPM analysis
- Fama-French factor modeling
- Statistical significance testing
- Machine learning forecasting
- Interactive dashboards
- Automated reporting systems
- Real-time market monitoring

---

## Disclaimer

This project was developed for educational, analytical, and portfolio purposes only.

The findings presented do not constitute investment advice, financial recommendations, or guarantees of future performance.

---

## Author

### Deng Aguer Bul

**Data Science Student**  
University of Tampa

#### Areas of Interest

- Financial Analytics
- Data Science
- Quantitative Research
- Market Intelligence
- Investment Analysis
- Economic Intelligence

---

## Acknowledgments

Data provided by:

- Yahoo Finance
- Federal Reserve Economic Data (FRED)

Special thanks to the University of Tampa for supporting the academic and analytical development that contributed to this project.
