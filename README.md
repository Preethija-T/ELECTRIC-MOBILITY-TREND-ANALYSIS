# ELECTRIC-MOBILITY-TREND-ANALYSIS (WASHINGTON)
A data-driven analysis of electric vehicle adoption trends across Washington State, examining yearly growth, city-wise distribution, vehicle types, and charging infrastructure to understand the state’s rapid shift toward sustainable transportation.

> **Tools:** Power BI | Excel | DAX | Power Query | Data Modeling  
> **Domain:** sales Analytics

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![Excel](https://img.shields.io/badge/Tool-Excel-green)
![Domain-Sales](https://img.shields.io/badge/Domain-Sales-blue)
![Language-DAX](https://img.shields.io/badge/Language-DAX-orange)

---

## 📌 Project Overview and Objective
This project analyses a government dataset containing information about electric vehicles (EVs) registered in the state of Washington. The goal is to produce a clean, reproducible analysis that describes the EV population, 
its spatial distribution, temporal trends, and infrastructure implications (charging stations), and to provide visualizations and actionable insights for stakeholders.This project involves cleaning, transforming, and 
analysing raw data using Power BI and creating an interactive Power BI dashboard to derive meaningful business insights.

---

## 📂 Data Sources
•	Source Description and Timeline: Government dataset provided by the user (assumed to be Washington state EV registration dataset). 
  Include original filename and download URL here. https://data.wa.gov/Transportation/Electric-Vehicle-Population-Data/f6w7-q2d2/about_data

---

## ❓ Problem Statement
The project aims to:
1.	Analyze EV adoption across Washington’s counties and cities.
2.	Identify the most popular EV makes and models.
3.	Compare battery electric vehicles (BEV) and plug-in hybrid vehicles (PHEV).
4.	Study electric ranges and their distribution.
5.	Check CAFV eligibility and clean-fuel trends.
6.	Build Power BI dashboards for visual insights.
7.	Support government and utility companies in infrastructure planning.

---

## 🧾 Attribute Details
| **Attribute Name** | **Description** |
|--------------------|---------------|
| VIN (unique identifier)	|Unique identifier for each Vehicle |
| Country	| Registered country |
| City	| Registered city |
| State| Registered state |
| Postal Code	|Postal code for city |
| Model Year	| Manufacturing year of the vehicle |
| Make	| Brand of the vehicle (Tesla, Volvo, KIA, etc.) |
| Model	| Model name (Model 3, Roadster, Wheego etc.) |
| Electric Vehicle type	|Electric type of the Vehicle|
| CAFV Eligibility |	Clean Alternative Fuel Vehicle eligibility |
| Electric Range	| Distance the vehicle can travel on battery power|
| Base MSRP	| Manufacturers Starting Retail Price |
| Legislative District| Number of job offers received after graduation |
| DOL Vehicle ID	| Department of Licensing (Washington) |
| Vehicle Location	| Location of the Electric Vehicle |
| Electric Utility	| Electricity provider for the vehicle’s location |
| 2020 census Tract		| Geographic location for analysis |
|MSRP Category	| Budget, Mid-Range and Premium |
|EV Age	| Age of the vehicle |
| Range Category	| Range category as Low, Medium and High |
| CAFV category	| Category as Eligible or Not Eligible |
| EV Type	| BEV or PHEV|

---

## 🧹 Data Cleaning & Preprocessing
Performed using **Power Query**:
### ✔ Handled missing or invalid values:
•	Records with Electric Range = 0 handled according to business rules
•	Replaced blank/nulls where possible
•	Standardized county and city names

### ✔ Removed duplicate vehicle records 
      Based on VIN 
      
### ✔ Categorized vehicle types:
•	BEV – Battery Electric Vehicle
•	PHEV – Plug-in Hybrid Electric Vehicle

### ✔ Created new calculated columns (Power BI):
•	EV Age = Current Year – Model Year
•	EV Category (BEV/PHEV)
•	Range Category (Low/Medium/High)

---

## 📉 Analysis & Visualizations

### Distribution of Electric Vehicle type: (Pie Chart)
BEVs dominate Washington’s EV landscape, accounting for nearly two-thirds of total electric vehicles, indicating a strong shift toward fully electric, zero-emission transportation.

### Electric vehicles over country: (Bar Chart)
EV adoption in Washington is highly concentrated in King County, which alone accounts for the majority of the state’s EV population, while most rural counties show very low adoption.

### EV Population in city over Year: (Waterfall chart)
EV adoption in Washington is rapidly increasing, with the majority of vehicles being recent 2024–2025 models, reflecting strong growth in the latest EV purchases.

### EV Model Year Insights: (Column chart)
Washington’s EV market is rapidly growing, with most vehicles from 2023–2025, showing strong adoption of the latest models.

### EV Distribution by County: (Map)
•	King County: Highest EV adoption with 7,190 vehicles, leading statewide.
•	Snohomish, Clark, Pierce: Strong adoption, 891–1,314 EVs, major urban hubs.
•	Thurston, Whatcom, Kitsap, Island, Jefferson: Moderate EV adoption, 100–500 vehicles.
•	Skagit, Yakima, Benton, Chelan, Lewis, Mason, San Juan: Emerging adoption, 50–150 vehicles.
•	Ferry, Lincoln, Wahkiakum, Garfield, Pend Oreille: Minimal adoption, 1–2 EVs.
•	Observation: EV adoption is heavily urban-focused, with rural counties showing very low penetration.

### EVs by CAFV Eligibility: (Donut Chart)
Most EVs fall under ‘Unknown’ CAFV status, while among classified vehicles, the majority are eligible, highlighting strong compliance but a major gap in data completeness.

### EV Distribution by Model: (Bar Chart)
EV adoption is led by high-demand SUVs and crossovers—topped by the Mustang Mach-E and Volvo XC series—while Tesla, Hyundai-Kia, and rising brands like Rivian and Lucid strengthen a diverse, rapidly expanding EV market.

### EVs by Model Year: (Line Chart)
EV adoption shows strong year-over-year growth, peaking in 2024 and reflecting a rapidly accelerating shift toward newer electric models.

### EVs by Make: (Tree Map)
Volvo leads EV registrations, followed by Audi, Tesla, and Ford, while emerging brands like Rivian, Lucid, and Polestar signal growing market diversification.

---

## 📈 Performance Insights

•	Tesla dominates Washington’s EV market, especially Model S
•	King County contributes the highest number of EV registrations.
•	EV adoption is increasing rapidly after 2020.
•	Majority of vehicles are Battery Electric Vehicles (BEVs), not PHEVs.
•	Most BEVs are CAFV eligible and meet clean-fuel standards.
•	Districts with high income and urban infrastructure show higher EV concentration.

---

## 🧠 Conclusion
Washington State continues to exhibit strong growth in EV adoption. With widespread availability of charging infrastructure and strong state policies, EV registrations will likely keep increasing. This analysis can help:
•	Government agencies allocate EV infrastructure
•	Utilities plan energy distribution
•	Policy makers track clean-fuel adoption
•	Researchers study environmental impact

---

## 👩‍💻 Author

**Preethija T**  
*Data Analyst | Power BI Developer*  

- 🌐 GitHub: (https://github.com/Preethija-T) 
- 💼 LinkedIn:(www.linkedin.com/in/preethija23051989)
- 📧 Email: Preethija23@gmail.com

If you found this project useful or have feedback, feel free to reach out!  

---

## 📚 Tags
`#PowerBI` `#DataAnalysis`  `#Sales Analytics` 
`#DAX` `#DataVisualization` `#ExcelPowerQuery`

