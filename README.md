# Chocolate Sales Analytics Dashboard

## Short Description / Purpose

The Chocolate Sales Analytics Dashboard is an interactive Power BI report designed to analyze sales performance, shipment activity, product trends, and team performance. It enables stakeholders to monitor key business metrics and gain actionable insights through interactive visualizations and secure data access.

---

## Tech Stack

The dashboard was built using the following tools and technologies:

 **Power BI Desktop** – Used for dashboard development and visualization.
 **Power Query** – Data cleaning, transformation, and preparation.
 **DAX (Data Analysis Expressions)** – Created KPIs and business calculations.
 **Star Schema Data Modeling** – Implemented Fact and Dimension table architecture.
 **Row-Level Security (RLS)** – Implemented both Static and Dynamic RLS.
 **File Format** – `.pbix` for development and `.png` for dashboard previews.

---

## 📂 Data Source

**Source:** Chocolate Sales Dataset

The dataset contains shipment records, product information, sales team details, location data, and calendar information used to analyze revenue, shipment performance, and sales effectiveness.

---

## ✨ Features / Highlights

### Business Problem

Organizations often struggle to monitor sales performance across products, regions, and teams while maintaining secure access to business data.

### Goal of the Dashboard

To provide an interactive analytics solution that enables users to:

* Monitor revenue and shipment performance.
* Analyze product and category contribution.
* Evaluate regional sales distribution.
* Track top-performing sales executives.
* Implement secure role-based data access.

### Walkthrough of Key Visuals

* **KPI Cards:** Total Revenue, Total Shipments, Total Boxes, and Average Shipment Value.
* **Revenue Trend Analysis:** Monthly sales performance tracking.
* **Regional Sales Analysis:** Revenue distribution across regions.
* **Category Contribution:** Product category performance analysis.
* **Product Performance:** Best-performing products by revenue.
* **Top Sales Executives:** Individual sales performance tracking.
* **Interactive Slicers:** Team, Year, and Region-based filtering.

### Data Modeling & Security

* Implemented a **Star Schema** with:

  * Fact Table: Shipments
  * Dimension Tables: People, Products, Locations, Calendar
* Created One-to-Many relationships for optimized performance.
* Implemented **Static RLS** using Team-based roles.
* Implemented **Dynamic RLS** using USERPRINCIPALNAME() and Email Mapping.

### Business Impact & Insights

* Identifies top-performing products and sales teams.
* Supports regional sales analysis and strategic planning.
* Enables secure access to data through role-based filtering.
* Helps stakeholders make informed, data-driven decisions.

---

## 📸 Dashboard Preview

![Dashboard Preview](Add Your Dashboard Screenshot URL Here)

📸 Dashboard Preview

![Dashboard Preview](https://github.com/raut0906/Chocolate-Sales-Analytics-Dashboard-Power-BI/blob/main/image.png))
