# Liquidity Asset Determinants in Thai Teachers' Savings Cooperatives

Undergraduate thesis (Special Problem course), co-authored | Kasetsart University | March 2025 | SPSS

- **Authors:** Thatchakorn Noichor (ธัชกร น้อยช่อ) and Yaphimon Kaewkumphai (ญาภิมณฐ์ แก้วคุ้มภัย)
- **Advisor:** Assoc.Prof. Nakhun THORANEENITIYAN (รองศาสตราจารย์ ดร.ณคุณ ธรณีนิติญาณ)

## Business question
Which financial factors determine how much liquidity a teachers' savings cooperative holds, and can they be used to set an appropriate liquidity level?

Factors hypothesised to affect liquidity: cooperative size, financial structure, access to funding, profitability, cash flow, members' loan demand, and members' deposit level.

## Data
- Secondary data from cooperatives' financial statements
- Sources: Federation of Savings Cooperatives of Thailand and the Cooperative Auditing Department
- **Sample:** 61 teachers' savings cooperatives with complete financial statements, 2019–2023 (5 years) = **305 cooperative-year observations**

## Method
1. **Descriptive statistics:** minimum, maximum, mean and standard deviation of all variables
2. **Distribution check:** skewness within –2 to +2 treated as acceptable; highly skewed variables were log-transformed (log_CR as the dependent variable; log_CF/TD as an independent variable)
3. **Correlation and multicollinearity:** Pearson correlation between independent variables (flagged if above 0.80); tolerance and VIF used to decide which variables to remove (e.g. log_D/E was removed at VIF = 9.014)
4. **Autocorrelation:** Durbin-Watson was computed during screening (1.614 for the first specification; 1.199 after the log transformation). The value for the final model was not recorded
5. **Regression:** multiple linear regression in SPSS using the Enter method at α = 0.05; tested with F-test (ANOVA) and t-tests, removed non-significant variables, then re-estimated the model
6. **Final model:** 6 variables, all significant; VIF 1.17–2.50, tolerance 0.40–0.86

## Key findings
Final model: 6 significant variables (all p < 0.001), R² = 0.767, **adjusted R² = 0.762**.

| Variable | Definition | Direction | Std. beta |
|---|---|---|---|
| log_CF/TD | Cash flow to total debt (log) | + | 0.712 |
| LTD/TA | Long-term debt to total assets | + | 0.511 |
| D/TA | Total debt to total assets | – | –0.417 |
| L/Dep | Loans to deposits | + | 0.137 |
| L/TA | Loans to total assets | – | –0.131 |
| RE/TA | Retained earnings to total assets | – | –0.129 |

Fitted equation:
log_CR = 0.672 – 1.130(D/TA) + 1.349(LTD/TA) – 1.052(RE/TA) + 0.394(log_CF/TD) – 0.335(L/TA) + 0.016(L/Dep)

**How to read D/TA and LTD/TA together:** total debt = short-term + long-term debt. Holding LTD/TA constant, a higher D/TA means more short-term debt, which is associated with lower liquidity. Holding total debt constant, shifting from short-term to long-term debt (higher LTD/TA) is associated with higher liquidity.

## Recommendations
1. **Debt management:** reduce debt burden, especially short-term debt, or shift toward long-term debt to increase liquidity flexibility
2. **Cash flow:** improve loan-repayment collection and accelerate deposit collection to maintain enough cash for unexpected expenses
3. **Investment planning:** do not invest all retained earnings in illiquid assets, to avoid short-term liquidity problems
