# Hotel Revenue and Cancellation Analysis

## Objective
Analyse hotel booking data to understand revenue trends, ADR, cancellation drivers and peak-season pricing.

## Tools
Excel (cleaning, pivot tables), Power BI (dashboard)

## Data Cleaning
- Removed 31,994 duplicate rows (119,390 to 87,396)
- Removed 2 invalid ADR rows (one negative, one extreme)
- Raw cancellation rate of 37% became 27.5% after cleaning

## Key Insights
- Resort ADR is about 3.6x higher in August (175) than in January (49)
- July and August bring about 37% of total revenue
- Online TA bookings cancel at 35%, Corporate at 12%
- Longer lead time means higher cancellation

## Dashboard
![Dashboard](dashboard.png.pdf)

## Notes
- Data covers Jul 2015 to Aug 2017, so 2015 and 2017 are partial years
- Revenue = ADR x nights, for non-cancelled bookings
