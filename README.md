# AUTO-NOVA-SALES-DASHBOARDS-
📊 Autonova Sales Dashboard – Tier 1 vs Tier 2 Cities
🔧 Project Structure (for GitHub)
bash
Copy
Edit
autonova-sales-dashboard/
│
├── data/
│   ├── sales_tier1.csv
│   ├── sales_tier2.csv
│   └── city_tiers_mapping.csv
│
├── notebooks/
│   ├── data_cleaning.ipynb
│   └── dashboard_analysis.ipynb
│
├── scripts/
│   └── data_processing.py
│
├── dashboard/
│   └── app.py   # (e.g., Streamlit or Dash)
│
├── README.md
└── requirements.txt
🏙️ City Tier Definitions
Tier 1 Cities: Mumbai, Delhi, Bengaluru, Hyderabad, Chennai, Kolkata, Pune, Ahmedabad

Tier 2 Cities: Jaipur, Lucknow, Indore, Patna, Bhopal, Nagpur, Chandigarh, etc.

Use a city_tiers_mapping.csv file to classify cities accordingly.
📈 Dashboard Features
KPIs: Total sales, revenue, units sold per tier

City-level Comparison: Bar/line charts for city-wise performance

Model Popularity: Sales by vehicle model in Tier 1 vs Tier 2

Time Trends: Monthly sales trends per tier

Map Visualization (optional): Sales density by city

🛠️ Tech Stack Suggestions
Python (pandas, matplotlib/seaborn/plotly)

Streamlit / Dash / Power BI for dashboards

Jupyter Notebooks for analysis

📄 README Highlights
Project objective

Dataset description

Insights and dashboard demo (screenshots or GIF)


How to run the app

Dependencies (requirements.txt)


