# 🚴 Cyclistic Bike-Share: Member vs. Casual Rider Optimization
**Google Data Analytics Professional Certificate — Capstone Case Study 1**

---

## 📌 Executive Summary
Cyclistic is a bike-share program featuring a fleet of over 5,800 geotracked bicycles and 692 docking stations across Chicago. The company’s commercial growth strategy hinges on maximizing annual memberships, as financial analysis demonstrates that annual members generate significantly higher long-term profit margins than casual riders (single-ride and full-day pass users).

This project analyzes over 5.7 million historical trip records to identify behavioral divergence between casual riders and annual members, providing data-backed marketing strategies to drive conversion into annual subscribers.

* **Technical Stack:** Python (Pandas, NumPy, Glob), Power BI, Jupyter Notebook, Microsoft Word
* **Dataset Scope:** 12 consecutive months of ride data (~5.7M+ records)

---

## 📊 Executive Dashboard Preview
![Cyclistic Executive Dashboard](visualization/CYCLISTIC%20EXECUTIVE%20DASHBOARD.png)

---

## 🔍 Key Analytical Findings

1. **Trip Duration Divergence:**
   * **Casual Riders:** Average trip duration is approximately **23.8 minutes**, showing strong alignment with leisure, recreation, and exploratory weekend travel.
   * **Annual Members:** Average trip duration is consistently **12.4 minutes**, reflecting purposeful, time-optimized commuting routines.

2. **Temporal & Weekly Cyclical Trends:**
   * **Weekdays (Mon–Fri):** Member ridership peaks sharply during rush hours (**7:00 AM – 9:00 AM** and **4:30 PM – 6:30 PM**), confirming high utilitarian commute usage.
   * **Weekends (Sat–Sun):** Casual ride volume surges by over **85%**, dominating lakefront and park-adjacent docking stations (e.g., Streeter Dr & Grand Ave).

3. **Seasonal Volume Drops:**
   * Both groups peak between **June and August**, but casual ridership drops by more than **78%** in the winter months (Dec–Feb), whereas member usage maintains steady baseline utility throughout the year.

---

## 💡 Strategic Business Recommendations

* **"Weekend-to-Annual" Commuter Trial:** Introduce an introductory "Flex/Hybrid Pass" targeted at frequent Saturday/Sunday casual riders that credits their weekend spend toward a discounted first-year annual membership.
* **Geofenced In-App Promotions:** Deploy automated push notifications and QR promotions at high-traffic casual tourist hubs (Lakefront, Navy Pier, Millennium Park) highlighting cost savings for rides over 20 minutes with a membership.
* **Winter Retention & Gamification:** Launch cold-weather milestone challenges and indoor partner perks during Q4 and Q1 to maintain user brand engagement across off-peak months.

---

## 📁 Repository Structure
```text
├── 01_SCRIPTS/              # Python processing scripts and Jupyter Notebooks
├── 02_PROCESSED_DATA/       # Cleaned ride summaries and aggregated trend CSVs
├── 03_DOCUMENTATION/        # Complete executive case study report (.docx)
├── visualization/           # Power BI dashboard screenshots and assets
└── README.md                # Project documentation and executive overview
