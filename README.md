# Regional Performance Dashboard

**Author:** Ogaba Faina Ogenyi
**Date:** 2026-09-24

## Project Background

The regional operations team is heading into the December holiday rush facing four unresolved operational concerns across its three supermarket branches (New York, Austin, Chicago). Branch managers are reporting conflicting staffing complaints, Finance is questioning whether the Member loyalty program is worth its cost, Marketing suspects its ad targeting may be misdirected, and leadership is concerned that high-spending "premium" customers may be quietly dissatisfied.

This project analyzes transaction-level sales data from January to November 2025 and presents the findings through an interactive Excel dashboard, supported by a board-ready presentation, to support evidence-based decision-making ahead of the holiday season.

## Project Objectives

1. Determine actual peak transaction hours by city, to test whether a single staffing roster can realistically serve all three branches.
2. Compare Member vs. Normal average ticket size and payment-method mix to evaluate the loyalty program's real revenue value.
3. Examine gender purchasing patterns by product line and city to test current ad-targeting assumptions.
4. Assess the relationship between transaction spend and customer satisfaction rating.
5. Track the monthly revenue trend heading into the December holiday rush.
6. Build an interactive Excel dashboard to support management reporting and board-level decision-making.

## Dataset

The project dataset contains 21,000 transaction-level sales records across the three branches, covering January 1 - November 30, 2025, with zero null values.

The dataset includes:

1. Invoice ID
2. Branch / City
3. Customer Type
4. Gender
5. Payment
6. Product Line
7. Unit Price
8. Quantity
9. Tax 5%
10. Total
11. COGS
12. Gross Margin %
13. Date
14. Time
15. Rating

City and Branch are a confirmed 1:1 match (A = New York, B = Austin, C = Chicago). Customer Type identifies Member vs. Normal walk-in customers, and Rating records customer satisfaction on a 1-10 scale.

## Dashboard Features

### Key Performance Indicators

1. Total Revenue - $666,783,065
2. Average Rating - 7.00 / 10
3. Rating Standard Deviation - 1.73
4. Peak Hour Spread - Austin 5 PM, Chicago 9 AM, New York 8 PM
5. High-Value Customer Avg Rating - 7.01
6. Member vs. Normal Ticket Gap - -0.95%
7. Member Revenue Share - 50.28%
8. Gender Split Range - 48%-52% across all categories
9. Health & Beauty Revenue - $112,068,421
10. Electronics Revenue - $111,893,520
11. Top Product Line by Revenue - Sports & Travel ($112,585,389)

### Dashboard Analyses

1. Rush Hour Traffic by City
2. Revenue by Hour
3. Average Ticket Size by Customer Type
4. Payment Method Mix by Customer Type
5. Revenue by Gender and Product Line
6. Customer Rating by Spend Band
7. Spend vs. Rating (scatter with trendline)
8. Monthly Revenue Trend

The dashboard is organized around the four business questions raised by regional leadership: staffing, membership value, marketing efficiency, and premium customer experience.

## Interactive Filters

The dashboard includes two global controls, connected to every pivot table and chart:

1. City Slicer (New York, Austin, Chicago)
2. Date Timeline (filterable by month)

## Key Findings

### Overall Performance

The dataset covers 21,000 transactions totaling $666,783,065 in revenue, with an average customer rating of 7.00 out of 10 (standard deviation 1.73). Revenue is not flat across the period - it climbs from $59.8M in January to $63.8M in November, the highest month on record, directly ahead of the December rush.

### Staffing and Peak Hours

Peak transaction hours differ sharply by city: Austin peaks at 5 PM, Chicago peaks at 9 AM, and New York peaks at 8 PM - a spread of up to 11 hours. A single staffing roster cannot realistically serve all three branches; each city needs its own schedule built around its own rush hour.

A further nuance appears in Chicago specifically: its highest transaction volume occurs in the morning, but its highest revenue hour is in the evening (approximately $21.8M). Rosters built on foot-traffic counts alone risk understaffing the hour that matters most for revenue.

### Membership Program

Members spend $31,601 on average per visit, compared to $31,905 for Normal customers - a gap of -0.95%, meaning Members spend slightly less, not more. Payment-method mix is also nearly identical between the two groups (Cash, Credit Card, and E-wallet each sit within a point or two of 33% for both), so there is no fee-saving payment behavior to offset the gap. Finance's skepticism about the program's cost-effectiveness is supported by the data.

### Marketing and Gender Purchasing

Across every product line and city - including the Austin / Fashion Accessories case specifically raised by leadership - gender purchasing splits fall within 48%-52%, with the overall revenue split at 49.98% Female / 50.02% Male. There is no meaningful gender divide in purchasing behavior anywhere in the dataset, so gender-based ad targeting is not supported by the evidence.

### Customer Experience

The correlation between transaction spend and customer rating is effectively zero (r is approximately 0.004), confirmed across all 21,000 individual transactions and when grouped into spend bands (Low 7.00, Mid 6.98, High 7.01). High-value customers are not being under-served - satisfaction does not decline as spend increases.

### Monthly Revenue Trend

Revenue rises from a January low, dips briefly in February and August, and climbs to a Jan-Nov high of $63.8M in November - reinforcing the urgency of resolving the staffing issue before, not after, the December holiday rush.

## Recommendations

### Staffing & Scheduling

1. Replace the universal roster with branch-specific shifts matched to each city's real peak hour.
2. Pull payroll data to confirm and size the potential overtime savings.

### Membership Program

1. Reform or retire current Member perks, since revenue does not currently justify them.
2. If the program is kept, redesign it around a higher spend threshold rather than blanket discounts.

### Marketing Targeting

1. Move the Health & Beauty / Electronics ad budget away from gender-based segmentation.
2. Test targeting by city, spend band, or product affinity instead.

### Customer Experience

1. No urgent service-quality fix is needed for high-spending customers - satisfaction is already flat across spend levels.
2. Redirect attention and budget toward the staffing fix, which affects satisfaction more directly.

### Data Limitations & Further Analysis Needed

This transaction log cannot answer everything leadership asked. The following require data from other departments and are flagged rather than assumed:

1. Overtime and payroll cost (HR / Finance)
2. Customer wait times (operational logs)
3. Membership program administrative cost (Finance)
4. Actual processing-fee rates by payment method (Finance)
5. Marketing ad-spend ROI and attribution (Marketing)

## Tools & Techniques

1. Microsoft Excel
2. PivotTables
3. PivotCharts
4. Slicers & Timelines
5. Data cleaning and transformation
6. KPI development (SUMIF, AVERAGEIF, INDEX/MATCH, pivot-linked formulas)
7. Descriptive analytics
8. Dashboard design and visualization
9. Executive presentation design

## Project Files

1. `Regional-Performance-Dashboard.xlsx` — Interactive Excel dashboard
2. `Regional Performance Presentation Slide.pptx` — Board presentation summarizing findings and recommendations
3. `README.md` — Project documentation

## How to Run / View

1. Open `Regional-Performance-Dashboard.xlsx` using Microsoft Excel, preferably the desktop version.
2. Enable content if prompted so that PivotTables, slicers, and the timeline can function correctly.
3. Use the City Slicer and Date Timeline to filter the connected charts and pivot tables.
4. Review the KPI cards and charts to investigate staffing, membership value, marketing efficiency, and customer experience.
5. Refer to the presentation for a summarized view of the key findings and recommendations.

## Contact

Ogaba Faina Ogenyi

Email: Ogaba.faina@gmail.com

