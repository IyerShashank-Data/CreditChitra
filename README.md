# CreditChitra
District-Level Geospatial Lending Risk Simulator for India
A Geo-Analytics Dashboard to Simulate, Visualize & Optimize Lending Risk across 589 Indian Districts

## 🧠 Overview

Traditional lending strategies in India often rely on borrower-centric models that ignore **geo-socioeconomic factors** like unemployment, credit penetration, or migration trends. This leads to:
- **Mispriced credit products**
- **Under-served rural areas**
- **Excessive exposure in high-risk districts**

**CreditChitra** fills this gap by simulating district-level lending risk using geospatial and socio-economic parameters, visualized through an interactive Power BI dashboard. It enables banks and NBFCs to **make risk-informed lending, expansion, and pricing decisions**.

---

## 🚩 Problem Statement

> ❗ *"Why does lending risk vary so dramatically across districts — and why don't our models reflect it?"*

Financial institutions in India face challenges such as:
- Ignoring **regional stressors** like unemployment, slum density, or political risk
- Flat pricing and uniform credit policies despite **localised vulnerabilities**
- Lack of branch-level strategic insights for **expansion, divestment, or loan repricing**

CreditChitra was designed to solve this by answering:  
💬 *"Where should we lend, pause, or price differently based on regional risk factors?"*

---

## ✅ Features

| Capability                     | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| 🗺️ Geo-Based Risk Mapping     | District-level heatmaps of simulated lending risk                          |
| 📊 What-If Simulations        | Dynamic toggling of thresholds for key variables like Unemployment or Credit Penetration |
| ⚠️ Risk Flag Generator        | Categorizes districts as **Safe** or **At Risk** using multi-variable logic |
| 📉 KPI Dashboards             | Visuals showing risk breakdown by region, state, and vulnerability cluster |
| 🔍 Scenario Comparison        | Analyze the impact of changing policies or economic conditions on credit risk  |

---

## 🧰 Tech Stack

- 🐍 **Python** (data simulation, risk scoring logic)
- 📍 **Folium** (for map generation, prototyping)
- 📊 **Power BI** (dashboarding, slicers, KPI visuals)
- 🧼 **Pandas / NumPy** (data manipulation)
- 🌐 **GeoPandas** (district geometry)
- 🔁 **What-If Parameters** (Power BI interactivity layer)

---

## 📦 Data Sources

| Data Type                     | Source / Method                                   |
|------------------------------|--------------------------------------------------|
| District Names               | Actual District Names used at random positioning          |
| Lat-Long Coordinates         | Merged from real Indian district shapefiles      |
| Unemployment, Credit Access  | Simulated using normal distributions + real-world bounds |
| Economic Vulnerability Score | Synthetic (0–10 scale, correlated with poverty/agri dependency) |
| Slum Population %, Migration | Simulated with clipping to ensure realism        |

*Note: All datasets are generated with statistically valid methods to simulate real-world randomness and avoid bias.*

---

## 📍 Key Insights
Over 135+ districts were flagged as Simulated At Risk, despite appearing safe under conventional credit models.

Low credit penetration and high unemployment were dominant risk indicators — especially in rural West Bengal, eastern Maharashtra, and northern UP.

Several agrarian zones showed low risk but poor credit access — indicating strong expansion potential.

What-If simulations allowed for real-time policy stress testing (e.g., what happens to risk levels if unemployment rises by 2%).

---

## 💡 Strategic Recommendations
📌 Branch Network Optimization

Expand into low-risk, high-agri zones with under-penetrated credit footprints.

📌 Dynamic Credit Pricing

Use regional risk score to modulate interest rates and LTV ratios.

📌 Digital Onboarding

Target semi-urban districts with medium slum population & medium risk for fintech-led inclusion.

📌 Policy Integration

Share insights with regulatory teams for pre-emptive policy shifts (e.g., district reclassification, subsidy targeting).

---
