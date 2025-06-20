# 🛒 AtliQ Mart - Supply Chain Performance Dashboard | Power BI Project
---

## 📌 Project Overview

This Power BI dashboard analyzes key supply chain performance metrics for **AtliQ Mart**, a FMCG (Fast-Moving Consumer Goods) company. The goal is to help stakeholders monitor order fulfillment, delivery performance, and customer satisfaction across regions and product categories.

The dashboard delivers actionable insights for Supply Chain, Warehouse, and Distribution teams by answering questions like:

- Are we delivering customer orders **on time and in full**?
- Which **customers or product categories** need improvement?
- How efficiently are we meeting **line-level and volume-level order fulfillment**?

---

## 📊 Business Problem Statement

> “How well is AtliQ Mart fulfilling customer orders in terms of completeness and timeliness across cities, product categories, and key clients?”

---

## 📈 Key Metrics Tracked

| Metric | Description |
|--------|-------------|
| **In Full %** | Measures if the order was delivered with all items in correct quantities |
| **On Time %** | Measures if the order was delivered on or before promised date |
| **OTIF %** | The toughest metric: Order is counted only if it is both In Full and On Time |
| **Line Fill Rate** | % of individual order lines successfully fulfilled (ignores timing) |
| **Volume Fill Rate** | % of total ordered quantity delivered (case-wise or unit-wise) |
| **Average Delivery Delay** | Days late/early deliveries on average |
| **Order Qty vs Delivered Qty** | Highlights gaps between customer demand vs actual supply |

---

## 🧭 Report Navigation & Features

Power BI report is split into **four major pages**:

---

### 1️⃣ **Executive View **

- Time-based trends for OTIF%, OT%, IF%
- Order by Delievery Status: Early, On Time, Late
- KPI cards: OTIF%, OT%, IF%
- Average Delievery Delay

---

### 2️⃣ **Customer Performance**

- Ranking of customers by all 5 metrics 
- Clear bookmarks to see various performance metrics for top and bottom Customers by Order Qty
- Understanding the overall discrepancy between actual OTIF% and Target OTIF

---

### 3️⃣ **Product Information**

- Clearly defined slicer for each product category and product name
- Matrix to measure Line fill rate and Volume fill rate with visual sparklines for each product
- Important KPIs

---
### 4️⃣ **City Wise Breakdown**

- Metric Performance by each City
- Clear and Simple Map visual to track order amount by product category

---

## 🛠 Technical Features

- ✅ **Interactive Bookmarks** (Top/Bottom/Reset functionality)
- ✅ **Dynamic visuals with DAX** for % KPIs and time-period trends
- ✅ **Clean, intuitive layout** with slicers for city and product categories
- ✅ **Calculated Measures** for OTIF logic, delays, and fill rates
- ✅ **Realistic business logic** from Codebasics Challenge C2

---

## 📁 File Structure


