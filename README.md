# Electric Vehicle Population Analysis – Power BI Dashboard

## 📊 Project Overview

This project presents an interactive **Power BI dashboard** that analyzes the Electric Vehicle (EV) population dataset.
The dashboard provides insights into electric vehicle adoption trends, vehicle types, manufacturer dominance, and eligibility for Clean Alternative Fuel Vehicle (CAFV) incentives.

The objective of this project is to explore EV market growth and provide a clear visualization of how electric vehicles are distributed across different manufacturers, models, and regions.

---

## 🎯 Purpose of the Project

The main goals of this dashboard are:

* Analyze the **growth of electric vehicles over time**
* Understand the **distribution of Battery Electric Vehicles (BEVs) and Hybrid Electric Vehicles**
* Identify **top EV manufacturers and most popular models**
* Evaluate **CAFV incentive eligibility**
* Examine **electric range categories** across vehicles

The dashboard allows users to interactively explore EV trends through filters and visualizations.

---

## 🛠 Tech Stack

The following tools and technologies were used in this project:

* **Power BI Desktop** – Data visualization and dashboard development
* **Power Query** – Data cleaning and transformation
* **DAX (Data Analysis Expressions)** – Creating KPIs and measures
* **GitHub** – Project version control and documentation

---

## 📂 Data Source

Dataset used for this project:

**Electric Vehicle Population Dataset**

The dataset contains information about electric vehicles including:

* Vehicle Identification Number (VIN)
* City, State, and Postal Code
* Model Year
* Make and Model
* Electric Vehicle Type
* Electric Range
* CAFV Eligibility
* Legislative District
* Electric Utility
* Vehicle Location (Latitude and Longitude)

---

## 🧹 Data Cleaning & Transformation

Several data preparation steps were performed using **Power Query**:

* Renamed EV types for clarity

  * *Battery Electric Vehicle (BEV)* → **Battery Electric Vehicle**
  * *Plug-in Hybrid Electric Vehicle (PHEV)* → **Hybrid Electric Vehicle**

* Removed records with **blank vehicle location values**

* Created a new variable **Electric Range Bin**

  * Low → 0–100 miles
  * Medium → 101–200 miles
  * High → >200 miles

* Extracted **Latitude and Longitude** from the vehicle location field for geographic analysis

---

## 📈 Dashboard KPIs

The dashboard includes the following key performance indicators:

* **Total Vehicles** – Overall count of EVs in the dataset
* **Average Electric Range** – Average driving range of EVs
* **Total BEV Vehicles and Percentage** – Share of fully electric vehicles
* **Total Hybrid EV Vehicles and Percentage** – Share of plug-in hybrid vehicles

---

## 📊 Dashboard Visualizations

The dashboard includes the following visualizations:

* **EV Adoption by Model Year** – Shows EV growth trends over time
* **EV Distribution by State** – Highlights geographic distribution of EV adoption
* **Top 10 EV Manufacturers** – Displays manufacturers with the highest EV counts
* **EV Distribution by CAFV Eligibility Status** – Shows vehicles eligible for incentives
* **Top 10 Electric Vehicle Models** – Identifies the most popular EV models
* **EV Distribution by Electric Range Category** – Categorizes vehicles into Low, Medium, and High range

---

## 🎛 Interactive Features

The dashboard includes several interactive elements:

* Navigation buttons for moving between dashboard pages
* Dynamic filters for exploring data
* Visual highlighting to analyze specific segments

---

## 🚗 Key Insights

Some insights derived from the analysis include:

* Electric vehicle adoption has **increased significantly over recent years**
* **Battery Electric Vehicles dominate the EV market** compared to hybrid EVs
* Certain manufacturers and models lead the EV market in terms of total vehicles
* CAFV incentives play an important role in encouraging EV adoption

---

## 📸 Dashboard Preview

https://github.com/Nakul-GitH/EV-Dashboard/blob/main/Snapshot%20of%20EV%20Dashboard.jpg

---

## 📁 Project Files

* `EV Dashboard.pbix` – Power BI dashboard file
* `README.md` – Project documentation
* `Snapshot of EV Dashboard` – Dashboard Preview

---

## 📌 Author

Nakul Gupta
Power BI Data Visualization Project
