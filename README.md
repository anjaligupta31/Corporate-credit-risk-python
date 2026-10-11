# Corporate-credit-risk-python
Python-based corporate credit risk analysis using financial ratios, borrower segmentation, rule-based warning indicators, and portfolio-level insights.

# Corporate Credit Risk & Portfolio Analytics | Python

## Project Overview

This project analyzes the financial health of 100 fictional corporate borrowers using Python to identify potential credit-risk warning signals and support portfolio monitoring.

The analysis uses financial statement data, profitability and leverage ratios, liquidity indicators, cash-flow measures, and working-capital metrics to evaluate borrower financial performance and highlight companies that may require further review.

Using Python and Pandas, I cleaned and prepared the dataset, engineered financial ratios, developed rule-based warning indicators, and conducted borrower-level and industry-level analysis.

The objective is to demonstrate how financial data analysis can support corporate credit assessment, early-warning monitoring, and data-driven portfolio management.

## Project Objectives

- Assess borrower financial performance using key financial ratios.
- Analyze revenue growth and EBITDA profitability.
- Evaluate leverage and debt-servicing capacity.
- Assess liquidity and short-term financial obligations.
- Examine cash flow and working-capital efficiency.
- Develop rule-based indicators to flag potential credit concerns.
- Identify borrowers requiring further financial review.
- Compare financial risk indicators across industries.

## Key Financial Metrics

- Revenue Growth (%)
- EBITDA Margin (%)
- Debt-to-EBITDA
- Interest Coverage Ratio
- Current Ratio
- Cash Conversion Cycle
- Overdue Days
- Borrower Warning Score

## Methodology

1. **Data Preparation:** Cleaned the borrower dataset and handled selected missing values using median imputation.
2. **Feature Engineering:** Calculated financial ratios and derived indicators to evaluate profitability, leverage, liquidity, and working-capital efficiency.
3. **Risk Flagging:** Applied illustrative thresholds to identify potential warning signals, including declining revenue, high leverage, weak interest coverage, liquidity pressure, negative cash flow, and overdue payments.
4. **Borrower Screening:** Combined warning indicators into a Warning Score and identified borrowers with two or more warning signals for further review.
5. **Portfolio Analysis:** Compared borrower performance, examined financial relationships, and analyzed risk indicators across industries.
6. **Visualization:** Used charts and statistical summaries to communicate findings and highlight areas requiring further investigation.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Excel

## Project Scope

This project is an exploratory financial analytics and rule-based risk-screening exercise using synthetic data. The warning thresholds are illustrative and are not calibrated against actual defaults or validated credit-risk outcomes.

The results demonstrate analytical methods for borrower monitoring rather than a production-ready credit scoring model.

## Key Financial & Risk Insights

### 1. Revenue Growth and Financial Performance

Revenue growth provides an initial indicator of business momentum. Borrowers experiencing negative revenue growth may require closer examination of operating performance, profitability, and debt-servicing capacity.

### 2. Profitability as an Indicator of Financial Resilience

EBITDA margin helps assess how effectively a company converts revenue into operating earnings. Borrowers with EBITDA margins below 8% are flagged for review under the project's illustrative screening criteria.

### 3. Leverage and Debt Sustainability

The Debt-to-EBITDA ratio helps assess debt relative to operating earnings. A ratio above 4 is treated as a potential warning signal, prompting further investigation into debt levels, earnings stability, and repayment capacity.

### 4. Interest Coverage and Debt-Servicing Capacity

Interest Coverage measures the ability of operating earnings to cover interest expenses. A ratio below 2 is flagged for review because it may indicate limited headroom to service borrowing costs.

### 5. Liquidity and Short-Term Financial Obligations

The Current Ratio compares current assets with current liabilities. A ratio below 1 is treated as a liquidity warning signal, indicating that short-term liabilities exceed current assets under the measure used.

### 6. Cash Flow and Working-Capital Efficiency

Negative cash flow and an extended Cash Conversion Cycle can highlight potential pressure on operating liquidity. These indicators help complement profitability and leverage analysis when assessing borrower financial health.

### 7. Rule-Based Early-Warning Screening

The Warning Score combines multiple illustrative financial and payment-related warning indicators. Borrowers with a score of 2 or more are placed on a review watchlist, helping prioritize further investigation.

### 8. Industry-Level Risk Comparison

Comparing borrowers across industries helps explore differences in profitability, leverage, liquidity, and working-capital characteristics. These comparisons can inform further investigation while accounting for differences in business models and industry economics.

## Key Insights

### 1. Portfolio screening identified 22 borrowers for further review

Using an illustrative rule-based framework, 22 out of 100 borrowers (22%) triggered at least two warning indicators. A further 20 borrowers triggered one warning indicator, while 58 triggered none of the defined indicators.

### 2. Revenue decline was the most common warning signal

24 borrowers (24%) reported lower revenue in FY25 than in FY24. This highlights the importance of monitoring revenue momentum alongside profitability and repayment capacity.

### 3. Profitability and leverage warrant attention

19 borrowers had EBITDA margins below 8%, while 17 had Debt-to-EBITDA ratios above 4x. These indicators help identify companies that may have limited financial flexibility or elevated leverage relative to operating earnings.

### 4. Debt-servicing pressure was present in a subset of borrowers

17 borrowers had interest coverage below 2x. Such borrowers may have limited earnings headroom to absorb higher borrowing costs or weaker operating performance.

### 5. Liquidity warnings were less frequent than profitability warnings

6 borrowers had Current Ratios below 1x, compared with 19 borrowers flagged for low EBITDA margins. This demonstrates why credit screening should consider multiple dimensions of financial health rather than relying on a single ratio.

### 6. Pharmaceuticals had the highest watchlist concentration

4 of 9 pharmaceutical borrowers (44.4%) met the watchlist threshold. Food Processing and Auto Components each had 3 or more flagged borrowers, with watchlist rates of 33.3%.

### 7. Payment delays and negative operating cash flow provide complementary signals

11 borrowers had payments overdue by more than 30 days among the 98 borrowers with recorded overdue-day data. 4 borrowers had negative operating cash flow. These signals can complement financial-ratio analysis when prioritizing borrower reviews.

### 8. Most borrowers showed positive average revenue growth

Average revenue growth across the sample was 6.98%, with median growth of 9.21%. However, 24 borrowers experienced a revenue decline, showing that portfolio averages can mask borrower-specific deterioration.

## Methodology & Limitations

The analysis uses 100 fictional corporate borrowers across 10 industries. Warning thresholds are illustrative: EBITDA margin below 8%, Debt-to-EBITDA above 4x, interest coverage below 2x, Current Ratio below 1x, negative operating cash flow, revenue decline, and payment delays exceeding 30 days.

Borrowers with at least two warning indicators are included on the review watchlist. These rules are intended to prioritize further analysis; they are not validated default predictions or formal credit ratings.

## Important Interpretation

The warning indicators are screening tools, not proof of financial distress or default. Actual credit decisions would require additional borrower information, industry context, historical outcomes, and appropriate validation.

## Technical Implementation

### Data Cleaning & Preparation
- Cleaned and prepared a dataset of 100 fictional corporate borrowers.
- Handled selected missing financial fields using median imputation.
- Organized borrower financial information for further analysis.

### Financial Feature Engineering
- Calculated revenue growth and EBITDA margin.
- Derived Debt-to-EBITDA and Interest Coverage ratios.
- Calculated the Current Ratio and Cash Conversion Cycle.
- Created rule-based financial warning indicators and a consolidated Warning Score.

### Exploratory Data Analysis
- Examined borrowers with low EBITDA margins and elevated warning scores.
- Compared financial performance and risk indicators across industries.
- Analyzed leverage against interest coverage.
- Explored revenue growth against profitability.
- Investigated liquidity, cash flow, and working-capital metrics.

### Risk Screening & Reporting
- Created a rule-based watchlist for borrowers with Warning Scores of 2 or higher.
- Used summary statistics, grouped analysis, and visualizations to identify potential risk areas.
- Prepared borrower-level outputs to support further review and portfolio monitoring.
