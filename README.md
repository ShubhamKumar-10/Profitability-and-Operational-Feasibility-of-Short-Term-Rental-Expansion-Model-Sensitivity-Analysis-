# Profitability-and-Operational-Feasibility-of-Short-Term-Rental-Expansion-Model-Sensitivity-Analysis-

Evaluating the Profitability and Operational Feasibility of Short-Term Rental Expansion: A Sensitivity Analysis Approach

## 1. Business Objective

Watershed Properties is evaluating whether to convert a subset of its long-term rental properties into short-term rentals. The objective of this project is to assess profitability, capital requirements, and operational feasibility under varying market and cost assumptions, while respecting a strict capital constraint.

## 2. Key Business Questions

Under what conditions does short-term rental conversion become profitable?

What is the worst case and best case profitability scenario?

Which assumptions have the largest impact on profits?

Given a $500,000 capital constraint, how many properties should be converted?

Which property types and locations should be prioritized?

## 3. Data & Tools Used

-Data Extraction	:                     SQL 
-Financial Modeling:	                 Microsoft Excel
-Sensitivity Analysis:	               Excel + Tableau
-Visualization:	                       Tableau Public
-Reporting:	                           Word (White Paper), PowerPoint

## 4. Financial Model Overview

The financial model estimates:

Conversion costs per property

Operating expenses (utilities, upkeep, fees)

Revenue from short-term rentals

Net cash flow and yearly profits

Outputs are calculated per property and aggregated across portfolios.

## 5. Sensitivity Analysis Design

Key assumptions tested:

Profitability threshold

Conversion cost

Transaction & regulatory fees

Average rental period

Yearly upkeep

Utilities and service costs

Each parameter was tested across realistic minimum and maximum ranges to identify risk exposure and upside potential.

## 6. Action
Extracted and integrated data for 244 client-owned properties with ~84,000 rows of historical short-term rental data (2 years) using SQL joins on location and property type

Computed property-level occupancy rates and comparable nightly rents by matching Watershed properties with short-term rentals in the same city and ZIP code

Built a revenue optimization model by applying linear regression on normalized rent bands (10th–90th percentile) to estimate the rent–occupancy tradeoff for each property

Forecasted property-specific optimal nightly rent and occupancy to maximize annual short-term rental revenue

Developed a financial model in Excel to calculate yearly cash flows and profits for both the conversion year and post-conversion year, incorporating capex, operating costs, platform fees, and regulatory buffers



## 7. Tableau Dashboard

The interactive dashboard allows decision makers to:

Adjust assumptions dynamically

Compare fixed vs variable parameter models

Visualize geographic concentration of profitable properties

Identify top-performing property types

## Dashboard Link:
https://public.tableau.com/views/SensitivityAnalysisofShort-TermRentalConversionProfitability/SensitivityAnalysisofShort-TermRentalConversionProfitability?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## 8. Key Insights

Identified 44 of 244 properties exceeding a $6,000 annual profit uplift threshold versus long-term leasing; eliminated cash flow negative properties through multi year cash flow screening

Performed scenario and sensitivity analysis in Tableau, revealing transaction fees and average stay length as the most profit-sensitive drivers

Prioritized 20 properties for phased conversion under a $500K capital constraint, focusing on 2-bedroom houses in coastal markets (TX, FL, CA)

Delivered a recommendation increasing projected profits from $0.77M (long-term leases) to $1.46M (short-term rentals) while minimizing cash flow risk

## 9. Final Recommendation

Given the $500,000 capital constraint, Watershed should:

Convert 20 out of 244 properties in Phase 1

Prioritize houses over apartments

Focus on high-performing geographic clusters near coast- Florida, Texas, California

Expand in stages based on realized cash flow increasing projected profits from $0.77M (long-term leases) to $1.46M (short-term rentals) while minimizing cash flow risk

This approach maximizes profit while minimizing financial risk.
