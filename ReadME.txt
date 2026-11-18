# Investment Portfolio Management & Forecasting (Excel)

University of Macedonia, 2024–25. Course project on managing a simulated
investment portfolio using Excel.

## What this project does
- Estimates risk and return for Greek and US stocks and for government bonds.
- Builds portfolios and optimises their weights.
- Forecasts prices and measures how accurate the forecasts are.

## Data
Daily prices from Investing.com, about one year (around 250 trading days):
- Greece: Sarantis, Cairo Mezz, Ververis, Autohellas, Jumbo, Titan, with the
  Athens General Index as the market benchmark.
- USA: VICI, Visa, Royal Caribbean, Amazon, Alphabet, Apple, with a US market
  index as the benchmark.
- 10-year government bond yields for Greece and the USA.

Methods
1. Daily returns, mean and standard deviation for each asset.
2. Regression against the market index to estimate alpha and beta.
3. CAPM expected returns and Sharpe ratios.
4. Covariance matrix and portfolio optimisation (Markowitz model) with Excel Solver.
5. Bond valuation: present value of coupons and face value.
6. Price forecasts with linear regression; forecast error measured with MAPE.



## Files
- `portfolio-management-forecasting.xlsx`: the full workbook. Some sheet names
  and labels are in Greek.

## Tools
Microsoft Excel.

## Notes
Educational project with simulated investments. Not financial advice.
