# Chocolate Sales Analytics Dashboard | Power BI

## Project Overview

Developed an interactive Power BI dashboard to analyze chocolate sales performance across regions, products, teams, and sales executives. The project follows a Star Schema data model and includes both Static and Dynamic Row-Level Security (RLS) implementations.

## Key Features

* Interactive KPI Cards (Revenue, Shipments, Boxes, Average Shipment Value)
* Revenue Trend Analysis
* Regional Sales Analysis
* Category Contribution Analysis
* Product Performance Dashboard
* Top Sales Executive Performance Tracking
* Quarterly Revenue Analysis
* Team-Based Filtering

## Data Modeling

### Star Schema Design

**Fact Table**

* Shipments

**Dimension Tables**

* People
* Products
* Locations
* Calendar

## Security Implementation

### Static RLS

Implemented team-based roles:

* Delish
* Tempo
* Juicies
* Yummies

### Dynamic RLS

Implemented Dynamic Row-Level Security using:

* USERPRINCIPALNAME()
* Email Mapping Column

## Skills Demonstrated

* Power BI
* Data Modeling
* Star Schema
* DAX
* Row Level Security (RLS)
* Dashboard Design
* Data Visualization
* Business Intelligence

## Business Insights

The dashboard helps stakeholders monitor revenue trends, product performance, regional sales distribution, and team-level performance while maintaining secure data access through RLS.
![Dashboard Preview].()
