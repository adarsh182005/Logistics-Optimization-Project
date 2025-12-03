# Logistics & Order Fulfillment Optimization Pipeline

### 📌 Project Overview
This project transforms raw logistics data into actionable insights. It processes unorganized courier timestamps to calculate delivery sessions, transit times, and performance KPIs. It also includes a forecasting model to predict future delivery trends.

### 🛠 Tech Stack
* **Language:** Python
* **Libraries:** Pandas (Data Manipulation), Plotly (Visualization), Statsmodels (Forecasting)

### ⚙️ Key Features
1.  **Automated Sessionization:** Converts raw timestamps into unique "Order Sessions" using a logic-based time gap threshold.
2.  **Data Cleaning:** Handles missing courier IDs and parses non-standard date formats.
3.  **KPI Analysis:** Calculates Average vs. Median transit times to filter out outliers.
4.  **Forecasting:** Uses Exponential Smoothing to predict next month's delivery speeds.

### 🚀 How to Run
1.  Install dependencies: `pip install -r requirements.txt`
2.  Open `logistics_pipeline.ipynb` in Jupyter or Google Colab.
3.  Upload your dataset CSV when prompted.
