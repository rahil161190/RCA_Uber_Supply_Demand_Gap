# 🚖 Uber Supply–Demand Gap: Root Cause Analysis & Business Insights

## 📌 Project Overview
This case study investigates **why Uber customers face high ride cancellations and “No Cars Available” issues** for **City ↔ Airport** routes.  
Using **Python, Pandas, Seaborn, and Matplotlib**, I performed **exploratory data analysis (EDA)** to uncover **time‑bound and location‑specific supply–demand mismatches** and proposed **data‑driven recommendations** to improve driver allocation and revenue.

---

## 🎯 Problem Statement
Uber observed:
- High **ride cancellations** by drivers
- Frequent **“No Cars Available”** responses
- Disproportionate impact on **Airport ↔ City** trips

This was hurting **customer satisfaction** and **revenue**.

---

## 🔍 Approach
1. **Data Cleaning & Preprocessing**
   - Handled missing values & timestamp formatting
   - Created derived features: `Request_hour`, `Time_slot`, `Cab_availability`
2. **Exploratory Data Analysis**
   - Hourly & time‑slot based demand–supply patterns
   - Pickup point–wise gap analysis
   - Cancellation vs. no‑availability trends
3. **Root Cause Identification**
   - Segmented by route, time, and status
4. **Business Recommendations**
   - Incentive structures for drivers
   - Operational tweaks for peak hours

---

## 📊 Key Insights
- **Late Evening (5–9 PM)**:  
  High demand **Airport → City**, but **low supply** → “No Cars Available” spikes.
- **Early Morning (5–9 AM)**:  
  High demand **City → Airport**, but **driver cancellations** dominate.
- **Gap Concentration**:  
  Late Evening & Early Morning slots show the **highest mismatch**.
- **Driver Behavior**:  
  Avoidance of certain routes during peak times due to low perceived earnings or empty return trips.

---

## 💡 Recommendations
- **Evening Airport Pickups**:  
  - Surge pay / guaranteed minimum fare  
  - Bonus for positioning at the airport
- **Morning Airport Drop‑offs**:  
  - Drop‑off bonuses  
  - Facilitate quick return trips
- **General**:  
  - Real‑time demand heatmaps in driver app  
  - Loyalty rewards for covering peak airport slots

