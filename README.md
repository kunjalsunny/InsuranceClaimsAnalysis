# Insurance Claims Analysis

## Overview
This repository contains scripts and workflows for analyzing insurance claims data. It includes:

- **Data Warehousing**: Implementation using PostgreSQL with a star schema design.
- **Data Visualizations**: Power BI dashboards showcasing insights like region-wise claims and feature effectiveness.

## Features

### 1. Data Warehousing
- Designed a star schema with the following:
  - **Fact Table**: `Claims`
  - **Dimension Tables**: `Customers`, `Vehicles`, `Features`, `Regions`, `Engines`, `Models`
- Populated data using Python and PostgreSQL.

### 2. Data Visualization
- Created dashboards in Power BI:
  - **Region-wise Claims Heatmap**: Visualize claim counts across different regions.
  - **Vehicle Metrics Over Time**: Analyze trends in vehicle performance metrics like torque and power.
  - **Feature Effectiveness on Claims**: Evaluate the impact of specific vehicle features on claim approvals.

## Prerequisites

### Tools and Technologies
- **PostgreSQL**: For database and data warehousing.
- **Python**: For data extraction, processing, and modeling.
- **Power BI**: For creating interactive dashboards.

### Libraries
- `psycopg2`: To connect Python with PostgreSQL.
- `pandas`: For data manipulation.


###  Clone the Repository
```bash
git clone https://github.com/kunjalsunny/InsuranceClaimsAnalysis.git
cd InsuranceClaimsAnalysis
```

## Future Enhancements
- Add advanced predictive modeling using deep learning.
- Automate ETL workflows with Apache Airflow.
- Integrate dashboards with live database updates.
