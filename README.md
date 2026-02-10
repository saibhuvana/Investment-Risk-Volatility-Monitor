# Investment Risk & Volatility Monitor (AlphaPulse)

## Project Overview
This project focuses on analyzing financial market data to understand price trends, volatility, and risk exposure using Python.

The project is divided into four major phases:
- Week 5: Data Cleaning & Wrangling
- Week 6: Exploratory Data Analysis & Visualization
- Week 7: Risk Modeling & Simulation
- Week 8: Dashboard Development (Tableau)
---

Investment-Risk-Volatility-Monitor

- Week_5_Data_Cleaning
  - Data cleaning notebook
  - Cleaned dataset output (CSV)

- Week_6_Visualization
  - Exploratory Data Analysis (EDA) and visualization notebook

- Dataset
  - Raw finance dataset (Excel file)


## Week 5 – Data Cleaning (Pandas)

### Key Activities:
- Handling missing values
- Removing duplicate records
- Standardizing column names
- Data type conversion
- Feature engineering
- Exporting cleaned dataset

### Output:
`week5_finance_cleaned.csv`

---

## Week 6 – Exploratory Data Analysis (EDA)

### Visualizations Created:
- Line chart for price trend analysis
- Bar chart for stock comparison
- Histogram for return distribution
- Boxplot for outlier detection
- Pie chart for profit vs loss days
- Correlation heatmap for asset relationships

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## Key Insights
- Identified long-term market trends
- Measured volatility using return distributions
- Analyzed correlations between financial indicators
- Interpreted market sentiment using profit/loss ratio

---

## Week 7 – Risk Modeling & Portfolio Analytics
## Objective
To implement advanced financial risk metrics and simulate portfolio performance under uncertainty.

## Key Activities
## Portfolio Return Calculation
-	Computed daily log returns
-	Applied equal weight portfolio assumption
-	Created aggregated portfolio return metric

## Rolling Volatility (30-Day)
- Calculated 30-day moving standard deviation
-	Measured short-term market uncertainty
-	Identified volatility spikes during unstable periods
## Output:
  rolling_volatility.csv

## Monte Carlo Simulation (10,000 Runs)
- Simulated 1-year future portfolio performance
-	Used historical mean & standard deviation
-	Generated probability distribution of returns
-	Ensured statistical stability using large sample size
## Purpose:
To estimate potential future risk exposure under random market conditions.

## Value at Risk (VaR – 95%)
•	Calculated 5th percentile of simulated returns
•	Estimated maximum expected loss at 95% confidence level
## Output:
var_results.csv

## Additional Outputs Generated
week5_finance_cleaned.csv
rolling_volatility.csv
var_results.csv

## Key Financial Metrics Implemented
Daily Log Returns
Portfolio Returns
Rolling Volatility (30-Day)
Monte Carlo Simulation (10,000 iterations)
Value at Risk (VaR 95%)

---

## Week 8 – Business Intelligence Dashboard (Tableau)
## Objective
To transform quantitative risk analysis into an interactive financial dashboard for decision-making.

## Dashboard Components

## Portfolio Return Trend
- Line chart showing daily portfolio performance
- Highlights profit/loss cycles

## Rolling Volatility Chart
- Visualizes market uncertainty
- Identifies high-risk periods

## Value at Risk (VaR) KPI Card
-	Displays downside risk percentage
-	Quick risk exposure indicator

## Correlation Visualization
-	Heatmap to analyze asset relationships
-	Helps evaluate diversification strategy
-	Dashboard Features
-	Interactive Date Filters
-	Percentage Formatting
-	Clean Professional Layout
-	Cross-filtering between visuals
-	Dynamic updates without lag


## Tools & Technologies (Extended)

Python
Pandas
NumPy
Matplotlib
Seaborn
Tableau
Google Colab
yfinance API

---

## Project Architecture
Raw Data (Excel)
        ↓
Data Cleaning (Week 5 - Pandas)
        ↓
EDA & Visualization (Week 6)
        ↓
Risk Modeling & Simulation (Week 7)
        ↓
Business Dashboard (Week 8 - Tableau)

---

## Business Impact
AlphaPulse enables:
-	Portfolio risk monitoring
-	Downside loss estimation (VaR)
-	Volatility tracking
-	Diversification analysis
-	Interactive financial decision support

---

## Final Status
Data Cleaning Complete
Exploratory Analysis Complete
Risk Modeling Implemented
Monte Carlo Simulation Integrated
Value at Risk Calculated
Interactive Tableau Dashboard Developed

## Author
Sappati Bhuvana Surya Sai Sudha
