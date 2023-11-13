# Data Collection and Sources

For this project, our primary data repository was the Wharton Research Data Services (WRDS).

## **Stock Price Information**

**Source:** Compustat Capital IQ, Yahoo! Finance

**File:** `data_stocks.CSV`

**Features Extracted:**

- **Open Price**
- **Close Price**
- **Adjusted Close Price**
- **High Price of the Day**
- **Low Price of the Day**
- **Earnings Per Share (EPS)**
- **Trade Volume**

**Notes:**

- The data underwent additional preprocessing before analysis.
- Script and logic were employed to clean and format the data.

## Financial Ratios Overview

**Source:** Compustat Capital IQ

**File:** `data_financial_ratios.CSV`

**Features Extracted:**

- `[P/E]` **Price to Earnings Ratio:**
- `[Book/Market]`
**Book to Market Ratio**: Gauge of company valuation relative to market price.

- `[Price/Sales]` **Price to Sales Ratio:** Stock value in relation to sales.
- `[Return on Equity]` **Return on Equity**: Stock value in relation to sales.
- `[Debt/Equity]` **Debt to Equity Ratio:** Measure of company's financial leverage.
- `[quick ratio]` **Quick Ratio:**  Short-term liquidity indicator.
- `[curr ratio]` **Current Ratio:** Broader liquidity metric.
- `[Price/Book]` **Price to Book Value:** Market valuation relative to book value.
- `[divyield]` **Dividend Yield:** ROI via dividends for income-focused investors.

## Historical Volatility Details

**Source:** OptionMetrics

**File:** data_realized_volatility.CSV

**Features Extracted:**

- `[Volatility]` **10-day Historical Volatility:** Calculated on 10 day window.

## Fama-French Factors

**Source:** Kenneth French Database

**File:** `data_fama_french.CSV`

**Features Extracted:**

- **Excess Market Return**
- **Size Factor (Small minus Big)**
- **Value Factor (High minus Low)**
- **Operating Profitability (Robust minus Weak)**
- **Investment Patterns (Conservative minus Aggressive)**
- **Risk-Free Rate**
- **Momentum Factor**






