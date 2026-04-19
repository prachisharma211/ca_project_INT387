# ca_project_INT387
# India Renewable Energy Dashboard (2019–2024)
> Interactive Power BI dashboard analyzing India's energy transition using the Ember Climate dataset

## Overview
This project presents a two-page interactive Microsoft Power BI dashboard built on 238,200+ monthly energy records across all Indian states and union territories from January 2019 to December 2024.

## Dashboard Pages
**Page 1 — Energy Overview**
- 4 KPI Cards: Solar (10.17M MW), Hydro (8.35M MW), Wind (6.87M MW), Renewables (27.13M MW)
- Stacked area chart: Solar, Wind & Hydro capacity growth with trend line
- Line charts: Electricity generation trend + CO₂ intensity decline
- Donut chart: Energy mix by fuel type

**Page 2 — State-wise Analysis**
- Geographic bubble map: Renewable capacity by state
- Pie chart: State-wise capacity distribution
- Bar chart: Top states ranked by total energy capacity

## Key Findings
| Metric | Finding |
|--------|---------|
| Solar growth | ~3x increase from 2019 to 2024 |
| Top renewable states | Gujarat, Maharashtra, Tamil Nadu |
| Coal share | 65.94% of total capacity |
| Solar share | 15.27% (fastest growing) |
| CO₂ intensity | Consistent declining trend |

## Dataset
- **Source:** Ember Climate — India Monthly Full Release
- **Records:** 238,200 rows, 13 columns
- **Period:** January 2019 – December 2024
- **Coverage:** All 28 states + 8 union territories

## Features
- 3 interactive slicers: State, Date range, Variable
- Dynamic cross-filtering across all visuals
- Analytics trend line on area chart
- Two-page dashboard layout

## Tools Used
- Microsoft Power BI Desktop (free)
- Dataset: `india_monthly_full_release_long_format.csv`

## How to Use
1. Download Power BI Desktop from powerbi.microsoft.com
2. Clone this repository
3. Open `CA2_INT387.pbix` in Power BI Desktop
4. Use slicers to explore state-wise and time-based data

## Author
**Prachi Sharma**
Department of Computer Science and Engineering
Lovely Professional University, Punjab, India
