# UK Aviation Passenger Demand Forecasting & Route Risk Analysis

## Forecasting UK airport passenger demand and identifying route concentration risks to support operational resilience, workforce planning, and strategic airport investment decisions.

---

# Executive Summary

This project analyses UK Civil Aviation Authority (CAA) passenger traffic data to evaluate airport growth patterns, route dependency risks, and passenger demand forecasting across UK domestic aviation networks.

Key findings include:
- Medium-sized airports demonstrated stronger growth potential compared to major UK hubs.
- 44% of analysed routes showed high concentration risk.
- Small regional airports displayed significant operational fragility.
- Forecasting models identified divergent recovery trajectories across airport categories.

---

# Business Problem

UK airports require accurate passenger forecasting and route risk analysis to support:
- Capacity planning
- Workforce optimisation
- Operational resilience
- Revenue stability

---

# Technical Stack

 Category | Tools |
|---|---|
| Programming | Python |
| Forecasting | Prophet, ARIMA |
| Visualisation | Jupyter Notebook |
| Querying | Jupyter Notebook |
| Version Control | Git/GitHub |

---

# Methodology

1. Data Cleaning & Preparation
2. Airport Segmentation
3. Route Dependency Analysis
4. Forecast Modelling
5. Model Validation

---

# Key Insights

## Medium Airports Show Strongest Growth Potential

Medium-sized airports demonstrated stronger recovery trends than large hub airports.

<img width="3000" height="1800" alt="airport_growth_analysis" src="https://github.com/user-attachments/assets/58665ecf-ea11-4f3c-bfc0-2afdce79f33a" />


## Route Concentration Creates Operational Risk

44% of domestic routes showed high dependency risk.

<img width="2100" height="2100" alt="risk_distribution" src="https://github.com/user-attachments/assets/354d4d31-26ac-4f87-8d9c-1a7766cdc846" />

Airports where a single route represented more than 50% of total passenger demand were flagged as high-risk.

<img width="2400" height="1500" alt="route_dependency_heatmap" src="https://github.com/user-attachments/assets/43e83bc2-8120-452b-b4ec-96cc74279aa6" />

## Charter Dependency Increases Volatility

Several small airports exhibited high charter reliance and unstable demand patterns.

<img width="2700" height="1800" alt="scheduled_vs_charter" src="https://github.com/user-attachments/assets/7c1198fe-6e31-441a-b13a-1892932198e4" />


---

# Forecasting Approach

Forecasts were developed using:
- ARIMA
- Prophet
  
Prophet models demonstrated stronger performance in volatile regional airport demand scenarios, while ARIMA models performed effectively for stable long-term trend forecasting

  <img width="3000" height="1800" alt="forecast_chart" src="https://github.com/user-attachments/assets/2cbb2105-e8df-4bcd-8bf7-38cd0b39b328" />


Validation metrics included:
- RMSE
- MAE

---

#Dashboard

## Power BI Dashboard Overview


(Adding dashboard screenshots here later)

---

# Business Recommendations

- Diversify high-risk route networks
- Prioritise investment in medium-growth airports
- Implement flexible staffing models
- Embed forecasting into operational planning

---

# Repository Structure

```text
uk-aviation-demand-forecasting/

CAA data/
notebooks/
presentation/
visuals/
README.md

