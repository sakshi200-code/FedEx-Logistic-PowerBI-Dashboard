# FedEx Logistics Performance Dashboard

### Power BI dashboard for shipment tracking, delivery-performance monitoring, and freight-cost analysis

## Overview

The **FedEx Logistics Performance Dashboard** is an interactive Power BI project that transforms logistics data into clear, actionable insights. It brings shipment activity, delivery timelines, processing efficiency, and freight costs into one centralized report.

Logistics teams need more than raw transaction records to make informed decisions. This dashboard makes it easier to understand shipment trends, compare shipment modes, identify freight-cost drivers, and monitor whether deliveries are early or late. Interactive visuals and filters allow users to explore performance from both operational and financial perspectives.

## Purpose

This project supports data-driven logistics decisions by helping stakeholders:

- Monitor shipment volume and freight spend over time.
- Evaluate delivery performance through average delivery variance.
- Compare the efficiency and cost of different shipment modes.
- Identify high-cost countries and products.
- Understand processing-time patterns and possible operational bottlenecks.
- Explore historical data interactively with a year-level filter.

## Data source

The dataset used in this project was provided as part of the **Data Science course at AlmaBetter**. It contains FedEx logistics and supply-chain records, including shipment details, delivery dates, vendor information, product attributes, freight cost, shipment mode, and delivery status.

> The dataset is used for educational and portfolio purposes only.

## Technology stack

| Technology | Usage in this project |
| --- | --- |
| **Power BI Desktop** | Report development, interactive visuals, and dashboard design |
| **Power Query** | Data cleaning, transformation, and preparation |
| **DAX** | Creation of KPI measures and business calculations |
| **Data Modeling** | Organizing tables, fields, relationships, and calculated measures |
| **`.pbit`** | Power BI template format used to share the report structure |

## Features and highlights

- **Executive KPI view:** Track total shipments, total freight cost, average delivery variance, and average processing time.
- **Shipment trend analysis:** Review yearly shipment volumes and monthly shipment patterns.
- **Shipment-mode analysis:** Compare shipment distribution, freight cost, processing time, and delivery variance across modes.
- **Delivery-performance insights:** Analyze the average number of days shipments are early or late.
- **Freight-cost analysis:** Identify shipment modes, countries, and products that contribute most to freight expenditure.
- **Top 10 rankings:** View countries and products with the highest freight cost for prioritized review.
- **Interactive filtering:** Use the delivery-year slicer to focus analysis on a selected time period.
- **User-friendly design:** Two focused report pages separate operational performance from cost analysis.

## Report pages

### 1. Logistics performance overview

This page provides a high-level operational view, including:

- KPI cards for shipment volume and performance metrics
- Shipment volume by year
- Monthly shipment trends
- Shipment-mode distribution
- Average delivery variance by shipment mode

### 2. Freight cost analysis

This page focuses on cost and efficiency drivers, including:

- Total freight cost by shipment mode
- Top 10 countries by freight cost
- Top 10 products by freight cost
- Yearly freight-cost trend
- Average processing time by shipment mode

## Data fields used

The model includes logistics and delivery attributes such as shipment ID, project and purchase-order references, country, vendor, shipment mode, product details, freight cost, delivery dates, delivery delay, processing time, delivery status, and delivery year/month.

## Key measures

- **Total Shipment**
- **Total Freight Cost**
- **Average Delivery Variance**
- **Average Processing Time**

## Insights supported by the dashboard

The dashboard can help answer practical logistics questions such as:

- How has shipment volume changed across years and months?
- Which shipment modes have the highest freight costs?
- Are deliveries generally on time, early, or delayed?
- Which countries and products account for the largest share of freight spending?
- Which shipment modes require the most processing time?

## Getting started

1. Download or clone this repository.
2. Open `FedEx Logistics Performance Dashboard.pbit` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. When prompted, provide the required data source or update the Power Query source path to your dataset.
4. Refresh the data and explore the report pages.

> This project is provided as a `.pbit` Power BI template. A template may require you to supply or reconnect the underlying dataset before visuals can be refreshed.

## Suggested repository structure

```text
.
├── FedEx Logistics Performance Dashboard.pbit
├── README.md
└── assets/
    └── dashboard-preview.png
```

## Author

Created by **Sakshi Chore** as a Data Science / Power BI portfolio project.

## License

This project is intended for portfolio and educational use. Add a license file if you plan to share or reuse it publicly.
