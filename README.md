# Logistics Intelligence Platform: 360° Operational Analytics (Power BI)

![Logistics Intelligence Dashboard Overview](Screenshot%202026-08-13%20202148.png)

## 📌 Executive Summary & Project Objective
This interactive Power BI dashboard provides 360° operational visibility into end-to-end supply chain performance, carrier service-level agreements (SLAs), delivery fulfillment rates, and financial leakage factors across logistics partners (DTDC, BlueDart, Delhivery, Amazon Logistics, FedEx India, Ekart, etc.).

Designed for logistics managers and supply chain directors, the dashboard highlights On-Time Delivery (OTD %) bottlenecks, operational delays, carrier performance variations, and claims/damage costs to drive operational efficiency and cost optimization.

---

## 🛠️ Technical Architecture & Power BI Features
* **Business Intelligence Tool:** Power BI Desktop
* **Data Modeling & DAX:** Dynamic DAX measures calculated for On-Time Delivery % (**51% OTD**), Total Logistics Spend (**3.46M**), Incident Rate per 1k shipments (**625.00**), Fleet Utilization (**0.60**), Cost per Kg (**68.84**), and Average Delay (**0.57 days**).
* **UI/UX Design:** Standardized light gray canvas with drop-shadow KPI cards, right-aligned region filter slicer, carrier scorecard table, and custom waterfall chart for financial leakage.
* **Data Visualizations Used:** Multi-Metric KPI Ribbon, Carrier Performance Matrix Table, Year-over-Year Claims Line Chart, Shipment Status Donut Chart, and Financial Leakage Waterfall Chart.

---

## 📊 Detailed Visual & Insights Analysis

### 1. Executive Performance Metrics
* **On-Time Delivery (OTD %):** 51% (Signifies major operational SLA room for improvement)
* **Total Spend:** 3.46M
* **Incident Rate (per 1k):** 625.00
* **Average Fleet Utilization:** 0.60 (60%)
* **Cost per Kg:** 68.84
* **Average Delay:** 0.57 Days

---

### 2. Deep-Dive Operational Insights

* **Carrier Performance Scorecard:**
  * **Top Performing Carriers:** **DTDC** (0.48 avg delay, 52% OTD) and **BlueDart** (0.50 avg delay, 52% OTD) lead in speed and SLA adherence.
  * **Bottom Performing Carriers:** **Shadowfax** (0.72 avg delay, 48% OTD) and **FedEx India** (0.73 avg delay, 50% OTD) experience higher average delivery delays.
  * Total Volume Tracked: 2,679 shipments across 10 logistics partners.

* **Shipment Status Breakdown (Donut Chart):**
  * **Delivered:** 49.74% (~half of total shipments successfully delivered).
  * **In Transit:** 17.25%
  * **Delayed:** 12.24%
  * **Out for Delivery:** 10.56%
  * **Returned & Lost:** Combined ~9% (~7.44% Returned, remaining Lost).

* **Financial Leakage by Incident Type (Waterfall Chart):**
  * **Delay** and **Damage** represent the two largest drivers of total financial leakage/claims.
  * **Wrong Delivery**, **Vehicle Breakdown**, **Accident**, **Theft**, and **Customs Hold** contribute incrementally to total claim expenses.

---

## 💡 Strategic Supply Chain Recommendations
1. **Carrier Re-allocation & Penalty Enforcement:** Shift higher shipment volumes toward top-performing carriers like **DTDC** and **BlueDart**, while enforcing SLA penalty clauses on carriers averaging delays over 0.7 days (**Shadowfax**, **FedEx India**).
2. **Mitigate Delays & Damage:** Address the root causes of shipment delays (12.24%) and transit damages, which account for the majority of financial leakage claims.
3. **Optimize Fleet Utilization:** Improve cargo loading schedules and route planning to increase average utilization from **60% to 75%+**, lowering the overall cost per kg (68.84).
