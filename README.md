# Apocalypse Food Prep Power BI Model 🛡️

An interactive Power BI data model and dashboard designed to audit and monitor emergency survival food inventories. This project showcases data modeling, relational star schemas, Power Query ETL automation, and advanced DAX calculations in Power BI.

---

## 📌 Project Overview

In resource-constrained or emergency scenarios, managing food inventories is a critical logistics challenge. This Power BI project tracks food stock levels, calorie distribution, storage locations, and expiration timelines to ensure inventory readiness.

### Core Architecture & Modeling
- **Data Model**: Structured as a clean **Star Schema** with a centralized inventory fact table connected to dimension tables for food categories, storage zones, and calendar dates.
- **Power Query ETL**: Auto-cleans raw inventory records, standardizes measurement units (grams, ounces, counts) to metric equivalents, and normalizes calorie scales.
- **DAX Calculations**: Custom measures created to track:
  - Total Calories available across the inventory
  - Burn Rate indicators (days of survival remaining based on group consumption settings)
  - Expiration Alert flags (items expiring in under 30, 60, or 90 days)
  - Category and warehouse utilization ratios

---

## 📂 File Inventory

* **`apocalypse-dashboard.pbix`**: The primary Power BI Desktop file containing the data model, queries, relationships, and interactive report tabs.
* **`apocalypse-dashboard.pdf`**: A high-fidelity static PDF export of the dashboard tabs for quick viewing without Power BI Desktop.

---

## 🚀 How to Open and View
- **Interactive Report**: Download the [`apocalypse-dashboard.pbix`](./apocalypse-dashboard.pbix) file and open it in **Power BI Desktop** (free).
- **Static Preview**: Open the [`apocalypse-dashboard.pdf`](./apocalypse-dashboard.pdf) file directly in your browser or PDF viewer.
