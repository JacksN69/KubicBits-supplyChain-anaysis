# KubicBits-supplychain-analysis
 in-depth look at the supply chain’s performance, focusing on both operational  flow and cost efficiency. It utilizes a wide range of charts and data summaries to highlight key aspects  like shipment volume, route optimization, expense distribution, delivery consistency, and future demand forecasting with models like ARIMA and  LSTM and Prophet.


## Project Overview

The goal is to transform raw logistics datasets into actionable insights and 2025 forecasts to help optimize the supply chain for **Akola (FMCG)** and its transporter.

We clean, explore, analyze, and forecast using structured approaches. Deliverables include KPIs, forecasting models, visual analytics, and strategic recommendations.

---

## Repository Structure

- `Untitled5.ipynb`: Jupyter notebook containing all code from data cleaning to forecasting and visualization.
- `KubicBits - Data Analytics Challenge.pdf`: Challenge instructions and dataset descriptions.
- `akola_shipments_detailed.xlsx`: Shipment dataset (50k+ rows, 25 columns).
- `carrier_data.xlsx`: Carrier dataset (4 tabs: Fleet, Trips, Costs, Tracking).

---

## Setup Instructions

### Requirements

Install the following Python packages (preferably in a virtual environment):

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels prophet

TASKS COMPLETED :

EDA & KPIs:

Calculated OTIF, transport costs, and vehicle utilization.

Visualizations for delivery performance, cost per km/kg, and load efficiency.

Forecasting (2025):

Shipment volumes (units, weight).

Transport costs (MAD).

Models used: ARIMA, Prophet, LSTM (based on performance).

Key Metrics

OTIF (On-Time In-Full) Rate

Average Transport Cost / Delivery

Vehicle Load Utilization

Forecast Accuracy
