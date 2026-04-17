⚡ Electric Vehicle Data Analysis & Visualization Dashboard

An end-to-end data analytics project that analyzes Electric Vehicle (EV) charging patterns, battery performance, and EV model efficiency using cloud databases, Power BI dashboards, and a Flask web interface.

The project demonstrates how data engineering, visualization, and web integration can be combined to generate meaningful insights from EV datasets.

📌 Project Overview

With the increasing adoption of electric vehicles, understanding charging behavior, battery performance, and model efficiency has become essential for:

Energy planners

Fleet managers

EV manufacturers

Consumers

This project builds an interactive analytics dashboard that helps analyze EV data using modern data tools.

The workflow includes:

Data Collection → Cloud Database → Data Cleaning → Visualization → Dashboard → Web Integration
🗂 Dataset Description

The dataset contains EV-related data including:

Vehicle model

Battery capacity

Charging location

Charging start time

Charging duration

Energy consumed

Driving range

Battery health

Charge cycles

Charging cost per km

Vehicle price

🗄 Database

The data is stored in a cloud PostgreSQL database using NeonDB.

Tables used

1️⃣ EV Charging Dataset

Column	Description
charging_location	Location of EV charging
charging_start_time	Time when charging started
charging_time	Duration of charging
energy_consumed	Energy consumed (kWh)
range	Driving range (km)
vehicle_model	EV model name

2️⃣ Battery Performance Table

Column	Description
battery_health	Battery health percentage
charge_cycles	Number of charge cycles
depth_of_discharge	Battery discharge level
efficiency	Battery efficiency
state_of_charge	Current battery charge
vehicle_model	EV model name

3️⃣ EV Model Table

Column	Description
model_name	EV model
battery_capacity	Battery capacity
range_km	Maximum driving range
price	Vehicle price
charging_cost_per_km	Charging cost per km
📊 Data Visualization

The project uses Microsoft Power BI to create interactive visualizations.

Key Visualizations

Energy consumption by charging location

Charging patterns by time of day

Battery health vs charge cycles

EV model price comparison

Charging cost per km by vehicle model

Battery efficiency vs depth of discharge

KPI Cards

Average driving range

Average battery health

Average energy consumption

📈 Dashboard Features

✔ Interactive charts and graphs
✔ KPI metric cards
✔ Data filters for dynamic analysis
✔ Multiple dashboard pages
✔ Story-based insight presentation

Filters used

Vehicle Model

Charging Location

Charging Time

Battery Capacity

📖 Story Insights

The project includes story pages explaining insights such as:

EV charging demand across locations

Battery performance degradation

EV model efficiency comparison

Cost analysis of EV models

⚙ Performance Testing

Dashboard performance was analyzed using the Power BI Performance Analyzer.

Metric	Value
Average Visual Load Time	~150–200 ms
Maximum Visual Load Time	~480 ms
Minimum Visual Load Time	~70 ms

This indicates efficient dashboard performance.

🌐 Web Integration

The dashboard interface is integrated into a Flask web application.

Flask provides a simple UI where users can access the analytics dashboard via a browser.

Technologies Used

Python

Flask

HTML / CSS

Power BI

🏗 Project Architecture
EV Data
   ↓
Cloud Database (PostgreSQL - NeonDB)
   ↓
Data Cleaning & Preparation
   ↓
Power BI Visualization
   ↓
Interactive Dashboard
   ↓
Flask Web Interface
🛠 Technologies Used
Tool	Purpose
Python	Backend integration
Flask	Web UI
Power BI	Data visualization
PostgreSQL	Cloud database
NeonDB	Cloud database hosting
📁 Project Structure
ev-dashboard-project
│
├── dataset
│
├── database
│
├── powerbi_dashboard
│   └── visualization.pbix
│
├── flask_app
|   |──images
│   ├── app.py
│   |──index.html
│   │──page.html
│   └── static
│
└── README.md
🚀 How to Run the Project
1 Install dependencies
pip install flask
2 Run Flask server
python app.py
3 Open browser
http://127.0.0.1:5000
📌 Key Learnings

Data cleaning and preparation

Database management using PostgreSQL

Data visualization with Power BI

Dashboard performance analysis

Web integration using Flask

Data storytelling through dashboards

📷 Dashboard Preview

(Add screenshots of your dashboard here)

📜 Conclusion

This project demonstrates how data analytics and visualization techniques can be applied to EV data to generate actionable insights.

The dashboard helps stakeholders understand:

EV charging patterns

Battery health trends

Model efficiency and cost comparison

This approach can support data-driven decision making in the electric vehicle ecosystem.

👨‍💻 Author

Piyush Kumar Raj
Computer Science Student
