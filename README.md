# 🚚 **SmartMove Logistics Analytics (Tableau BI Project)**  

## 🧭 **Table of Contents**
1. 📖 [Project Overview](#project-overview)  
2. 🎯 [Project Objectives](#project-objectives)  
3. 🧰 [Tools & Technologies](#tools--technologies)  
4. 📂 [Project Files](#project-files)  
5. 📊 [Data Description](#data-description)  
6. 🧹 [Data Preparation](#data-preparation)  
7. 🧩 [Data Modeling](#data-modeling)  
8. 📈 [Analysis & Key Insights](#analysis--key-insights)  
9. 💡 [Recommendations](#recommendations)  
10. 🔮 [Future Enhancements](#future-enhancements)  
11. 👤 [Project Owner](#project-owner)  

---

## 📖 **Project Overview**
**SmartMove Logistics** is a rapidly expanding third-party logistics provider operating across major Nigerian cities. With rising customer demand and increased delivery operations from 2021–2024, the company began experiencing challenges around delivery efficiency, increasing costs, inconsistent performance across cities, and a lack of consolidated reporting for strategic decision-making.

This Tableau BI project delivers an end-to-end analytics solution that transforms SmartMove’s operational dataset into **clear, actionable insights**, enabling leadership to monitor year-over-year delivery performance, identify bottlenecks, evaluate delivery delays, optimize fleet usage, and reduce operational costs.

This project demonstrates strong capabilities in:
- Data cleaning and preparation  
- KPI-driven logistics analysis  
- Tableau dashboard development  
- Insight storytelling  
- Operational and strategic recommendations  

---

## 🎯 **Project Objectives**
The project aims to provide clarity on SmartMove’s operational performance across cities, years, vehicle types, and delivery metrics. Key objectives include:

- 📦 Evaluate delivery volume trends across four years (2021–2024)  
- 🕒 Analyze average delivery time and on-time performance across cities  
- 🚚 Determine which vehicle types contribute most to logistics operations  
- ⏳ Identify where and when most delivery delays occur  
- 📈 Compare city-level performance to identify improvements or declines  
- 💰 Examine cost-per-delivery trends and operational cost efficiency  
- 🧭 Support strategic resource allocation and fleet optimization  

---

## 🧰 **Tools & Technologies**
| Tool / Technology | Purpose |
|------------------|----------|
| **Tableau Desktop** | Visualization and analytical dashboards |
| **Excel / CSV** | Raw dataset, preprocessing |
| **Tableau Workbook (.twbx)** | Final interactive BI solution |
| **PDF** | Project summary and insight documentation |

---

## 📂 **Project Files**
| File | Description |
|------|-------------|
| **SmartMove_Logistic_Dataset.csv** | Raw operational dataset (2021–2024) |
| **Smart Move Logistics.twbx** | Tableau packaged workbook containing dashboards |
| **SmartMove Logistics Analytics.pdf** | Analytical report covering insights & conclusions |

---

## 📊 **Data Description**
The dataset contains key logistics indicators recorded across multiple years, cities, and vehicle types.

### **Fields Included**
- **Date** — Date of recorded delivery activity  
- **City** — Delivery destination or operation city  
- **Vehicle Type** — Bike, Van, Truck, etc.  
- **Deliveries** — Number of successful deliveries  
- **Average Delivery Time** — Mean hours taken per delivery  
- **Average Cost** — Operational cost per delivery  
- **On-Time Rate (%)** — Percentage of deliveries completed within schedule  
- **Delays** — Number of late deliveries  

This structure supports multi-dimensional analysis across:
- Region  
- Time period  
- Fleet type  
- Cost and delivery efficiency  

---

## 🧹 **Data Preparation**
Cleaning and transformation steps included:

- Removal of missing or duplicate entries  
- Validation of delivery numbers, time values, and cost fields  
- Standardization of city and vehicle type labels  
- Calculation of YoY changes in key delivery metrics  
- Preparation of aggregated tables for city-level and fleet-level insights  
- Ensuring Tableau-ready formats for date and numeric fields  

---

## 🧩 **Data Modeling**
The modeling approach supports flexible slicing and filtering across operational dimensions.

### **Core Model Components**
- **Fact Table:** Delivery metrics (Deliveries, Delays, Costs, Avg Time)  
- **Dimension Tables:** City, Vehicle Type, Date  

This structure allows dynamic analysis such as:
- Trends over four years  
- City-by-city performance  
- Comparison across vehicle types  
- Delay distribution by month and region  

---

## 📈 **Analysis & Key Insights**

### **📦 1. Delivery Volume Trends**
- SmartMove recorded **steady growth in total deliveries** from 2021 to 2024.  
- However, growth slowed in 2023 due to rising operational costs and regional delays.  

### **🕒 2. Delivery Time & On-Time Rate**
- Cities like **Abuja and Lagos** showed the strongest on-time performance.  
- **Port Harcourt and Kano** experienced the **highest delays and slowest delivery times**, impacting satisfaction.  

### **🚚 3. Vehicle Type Utilization**
- **Bikes** handled most deliveries, offering speed and cost efficiency.  
- **Vans and trucks** were used for heavier loads but recorded **higher average delivery time and costs**.  
- Underutilization of certain vehicle types contributed to rising costs.  

### **⏳ 4. Delay Analysis**
- Delays peaked during specific months, driven by:  
  - Weather conditions  
  - Traffic congestion in major cities  
  - Poor route optimization  
- Port Harcourt recorded the **highest share of monthly delays**.  

### **💰 5. Cost Efficiency**
- Average cost per delivery increased significantly in 2023 due to:  
  - Fuel price fluctuations  
  - Increased vehicle maintenance costs  
  - Non-optimized delivery routes  

---

## 💡 **Recommendations**

### **📍 City-Level Improvements**
- Prioritize process improvements in **Port Harcourt and Kano**, focusing on delay reduction.  
- Expand operational resources in Lagos and Abuja to maintain competitive advantage.  

### **🚚 Fleet Optimization**
- Reallocate underutilized vehicles to high-demand routes.  
- Expand bike-based delivery operations to reduce average cost and improve delivery speed.  

### **⏳ Delay Reduction Strategies**
- Implement real-time route optimization tools.  
- Establish city-specific delivery schedules to reduce peak-time congestion.  
- Strengthen maintenance procedures for heavily-used vehicle types.  

### **💰 Cost Management**
- Negotiate fuel contracts or adopt fuel-efficient delivery strategies.  
- Introduce incentive programs for drivers with consistent on-time delivery rates.  
- Improve forecasting models to anticipate high-volume periods.  

---

## 🔮 **Future Enhancements**
- Integrate real-time GPS and telematics data  
- Build a predictive model for delay likelihood  
- Automate cost-per-delivery dashboards for weekly monitoring  
- Expand analysis to include customer satisfaction metrics  
- Introduce machine learning for optimal fleet allocation  

---

## 👤 **Project Owner**
**👨‍💼 Presented by:** *Nureni Tijani*  
**📍 Location:** United States  
**🔗 GitHub:** https://github.com/NureniTijani  
**🛠 Skills:** Tableau | Logistics Analytics | Data Cleaning | Visualization | KPI Design  
