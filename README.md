<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/2/2f/Blinkit-yellow-app-icon.svg" width="90"/>

# Blinkit Campaign Analytics Dashboard

**A Microsoft Power BI business intelligence dashboard that transforms raw Excel campaign data into interactive visual insights — tracking revenue, ROI, CTR, conversions, and customer sentiment in real time.**

<br>

<table>
  <tr>
    <td align="center">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cf/New_Power_BI_Logo.svg/1280px-New_Power_BI_Logo.svg.png?_=20210102182532" width="70"><br>Power BI
    </td>
    <td align="center">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/33/Figma-logo.svg/960px-Figma-logo.svg.png?_=20250625151003" width="70"><br>Figma
    </td>
    <td align="center">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/60/Microsoft_Office_Excel_%282025%E2%80%93present%29.svg/960px-Microsoft_Office_Excel_%282025%E2%80%93present%29.svg.png?_=20251114200801" width="70"><br>Excel
    </td>
  </tr>
</table>

</div>

---

<div align="center">
  <img src="https://www.slidegeeks.com/pics/dgm/l/k/Key_Metrics_Ppt_PowerPoint_Presentation_Infographics_Example_Topics_Slide_1.jpg"/>
</div>

---

## Overview

Organizations managing multiple marketing campaigns often struggle to identify which campaigns perform effectively. Raw data stored in Excel files is difficult to interpret and slows decision-making.

This Power BI dashboard presents campaign data in a structured, visual format that enables quick analysis and better business insights in one place.

---

## Problem Statement

Raw spreadsheet data is difficult to interpret and slows reporting and decision-making.

Marketing teams running campaigns across channels such as app push, flash sale, email, SMS, and social ads lack a unified performance view. This dashboard converts Excel data into a clear interactive report.

---

## Tools & Technologies

| Tool | Purpose |
|------|--------|
| Microsoft Power BI | Dashboard development and interactive visuals |
| Figma | UI/UX layout design |
| Excel / CSV | Raw dataset source |
| Power Query | Data cleaning and transformation |
| DAX | KPI and business logic calculations |

---

## Features

### Revenue Analysis
Track campaign revenue over time using KPI cards and line charts to identify growth trends.

### Campaign Performance
Compare campaigns using bar charts to quickly identify top and low performers.

### ROI Tracking
Return on Investment calculated using DAX measures for accurate financial insights.

### CTR & Conversion Funnel
Funnel chart visualizes the journey from impressions → clicks → conversions.

### Customer Feedback
Sentiment scores displayed using cards and tables for qualitative insights.

### Interactive Filters
Filter data by campaign, date range, and marketing channel for detailed analysis.

---

## Dashboard Preview (KPIs)

| Metric | Value | Trend |
|--------|-------|-------|
| Total Revenue | ₹4.2M | ↑ 18.4% |
| Average ROI | 3.6× | ↑ |
| Click-Through Rate | 8.3% | ↑ |
| Total Conversions | 12,400 | ↓ |

---

## Key Metrics Tracked

| Metric | Visual Type | Formula |
|--------|-------------|---------|
| Revenue | Line Chart · KPI Card | `SUM(Revenue)` |
| ROI | KPI Card · Bar Chart | `(Revenue - Cost) / Cost` |
| CTR | KPI Card | `Clicks / Impressions` |
| Conversions | Funnel Chart | `COUNT()` |
| Sentiment | Table · Card | Score |

---

## Project Structure

```bash
blinkit-campaign-analytics-dashboard/
│
├── dataset/
│   └── campaign_data.csv
│
├── dashboard/
│   └── blinkit_dashboard.pbix
│
├── design/
│   └── figma_wireframe.fig
│
└── README.md
