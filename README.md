# Retail Coupon Analysis

A group academic project examining the relationship between coupon
redemption, customer spending, and demographic patterns.

[View the full analysis](2026_BANA4080_Group11.ipynb)

## Business Question

How is coupon redemption associated with customer spending, and which
customer segments show stronger spending and promotional engagement?

## Data

The analysis uses retail data accessed through `completejourney_py`,
including transactions, coupon redemptions, and household demographics.

The analyzed data includes approximately:
- 1.47 million transaction records
- 2,469 purchasing households
- 410 households with recorded coupon redemptions

Demographic information is available for only a subset of households.

## Tools

Python · pandas · NumPy · Matplotlib · Seaborn · completejourney_py

## Approach

- Aggregated transaction records into household-level spending,
  shopping frequency, and average basket spending.
- Joined household summaries with coupon redemption and demographic data.
- Compared coupon redeemers with non-redeemers.
- Examined spending and redemption patterns across customer segments.
- Compared shopping frequency and basket spending among high- and
  low-spending coupon redeemers.

## Selected Findings

- Coupon redeemers had higher average total spending than non-redeemers
  in the analyzed data.
- Among redeemers, the highest-spending quarter averaged approximately
  174 shopping trips, compared with 67 for the lowest-spending quarter.
- Average basket spending was approximately $50.87 for the
  highest-spending quarter and $28.92 for the lowest-spending quarter.
- Some income segments contained very few households, limiting the
  reliability of comparisons.

## Business Implications

The analysis provides a starting point for investigating customer
segments and designing promotional tests. Both shopping frequency and
basket spending are useful considerations when comparing customer value.

A controlled experiment would be needed to establish whether targeted
coupons increase spending or profit.

## Limitations

This repository preserves the original academic submission.

The analysis is observational: higher spending among coupon redeemers
does not establish that coupons caused the difference.

The notebook's ROI proxy is a descriptive spending-to-discount measure,
not a measurement of incremental promotional profit. Net-spending
interpretations depend on confirming how the source data records
sales and discounts.

Missing demographic information and small segment sizes limit
demographic conclusions. The parent-status comparison also requires
revision because the original classification includes missing values
in the parent group.

## Viewing and Running

Open the notebook above to view the code and saved outputs.

To rerun it, install the imported Python packages, including
`completejourney_py`, and run the cells in order. The notebook retrieves
its source tables using that package.

## Project Team

- Adam Laughlin
- Finnian Kephart
- Finnian Traubert
- Jack Magee

Completed as a group project at the University of Cincinnati.
