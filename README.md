# NHS GP Appointments Analysis — England 2023 to 2026

![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![NHS](https://img.shields.io/badge/NHS-005EB8?style=for-the-badge&logo=nhs&logoColor=white)
![GitHub](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

![Dashboard Overview](screenshots/dashboard-overview.png)

## Project Overview

This project analyses over 929 million GP appointment records published by NHS England, covering September 2023 to February 2026. The aim was to identify patterns in consultation delivery, attendance behaviour and monthly demand trends across primary care in England.

This was completed as an independent portfolio project to demonstrate applied data analysis skills using real publicly available NHS data.

## Business Context

GP appointment demand and missed appointments are a significant operational challenge for the NHS. Understanding how appointments are delivered, how often patients do not attend, and how demand fluctuates over time helps NHS planners and commissioners make informed decisions about resource allocation and service design.

## Methodology

- Downloaded raw appointment data from NHS England Open Data Portal
- Explored and cleaned data structure in Microsoft Excel
- Built pivot tables to aggregate appointment volumes by month, delivery mode and attendance status
- Created a 3-month rolling average trendline to smooth short term fluctuations and reveal underlying demand trends
- Designed an interactive dashboard with a year slicer allowing dynamic filtering by period
- Identified and annotated peak demand months directly on the trend chart

## Dashboard Screenshots

### Full Dashboard
![Dashboard Overview](screenshots/dashboard-overview.png)

### KPI Cards
![KPI Cards](screenshots/kpis.png)

### Monthly Appointment Trends
![Appointment Trends](screenshots/appointment-trends.png)

### Delivery Method and Attendance Status
![Delivery and Attendance](screenshots/delivery-attendance.png)

## Key Findings

- **Face-to-face consultations dominated** at 64.9% of all appointments, suggesting that despite the post-pandemic push toward digital consultations, patients and clinicians continue to prefer in-person care
- **Telephone appointments accounted for 25.0%** of activity, making it the second most common delivery method
- **DNA (Did Not Attend) rate stood at 4.4%** equating to approximately 40 million missed appointments across the period, representing a significant cost and capacity challenge for the NHS
- **Overall attendance rate was strong at 89.6%**, indicating consistent patient engagement across the full period
- **October recorded the highest appointment volumes** across all three years analysed, likely reflecting the onset of winter pressures and seasonal illness

## Skills Demonstrated

- Data cleaning and exploration in Microsoft Excel
- Pivot table construction and aggregation
- Dashboard design and data visualisation
- Trend analysis using rolling averages
- Extracting and communicating actionable insights from large datasets
- Working with real NHS open data

## Limitations

- Data is aggregated at national level only, no regional breakdown by ICB or NHS Trust is available in this dataset
- 2026 data is partial and covers January and February only, which may affect full year trend interpretation
- The Unknown appointment category is not fully defined in the NHS source documentation
- The dataset does not include patient level demographics, limiting analysis of attendance patterns by age or deprivation

## Future Analysis

With access to additional data, this analysis could be extended to include:
- Regional breakdown by Integrated Care Board or NHS Trust to identify geographical variation in appointment demand
- Comparison with GP workforce data to assess capacity relative to demand
- Demographic analysis including age and deprivation if patient level data becomes available
- Longitudinal comparison pre and post 2019 to assess the lasting impact of the pandemic on primary care delivery

## Project Structure

```
nhs-gp-appointments-dashboard/
│
├── screenshots/
│   ├── dashboard-overview.png
│   ├── kpis.png
│   ├── appointment-trends.png
│   └── delivery-attendance.png
│
├── NHS_GP_Appointments_Dashboard.xlsx
└── README.md
```

> **Note:** The Excel file cannot be previewed directly on GitHub due to file size. To explore the full interactive dashboard including slicers and pivot tables, download the file and open locally in Microsoft Excel.
>
> [Download Excel Dashboard](https://github.com/Fariha-K/nhs-gp-appointments-dashboard/raw/refs/heads/main/NHS_GP_Appointments_Dashboard.xlsx)

## Tools Used

Microsoft Excel — Pivot Tables, Pivot Charts, Slicers, Trendlines, Dashboard Design

## Data Source

NHS England GP Appointments Data — publicly available at:
https://digital.nhs.uk/data-and-information/publications/statistical/appointments-in-general-practice

*Reporting period: September 2023 to February 2026 (2026 data partial)*
