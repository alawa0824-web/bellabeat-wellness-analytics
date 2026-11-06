# Cyclistic Bike-Share Analysis: Converting Casual Riders to Annual Members

> **Google Data Analytics Professional Certificate Capstone Project**  
> **Author:** Alaa Mohammad Awad  
> **Date:** October 2026  

---

## 📌 Executive Summary
Cyclistic is a premier bike-share program in Chicago featuring more than 5,800 bicycles and 600 docking stations. Financial analysis indicates that annual members are significantly more profitable than casual riders. Therefore, maximizing the number of annual memberships is key to future business growth.

This project analyzes **6,171,756 trip records** covering a continuous 12-month period (**October 2025 – September 2026**) to identify how casual riders and annual members use Cyclistic bikes differently, providing actionable, data-driven marketing strategies to convert casual riders into long-term annual members.

---

## 🛠️ Tools & Technologies Used
* **Data Processing & Manipulation:** Python (`pandas`, `numpy`)
* **Environment:** Google Colab
* **Data Visualization:** `matplotlib`, `seaborn`
* **Data Source:** Publicly available historical Cyclistic trip data provided by Motivate International Inc.

---

## 📊 Key Findings

### 1. Trip Duration
* **Casual riders** consistently log significantly longer single-trip durations compared to annual members.
* Casual trips average **~1,225.2 seconds (~20.4 mins)** compared to **~740.5 seconds (~12.3 mins)** for members across all days of the week.

### 2. Weekly Patterns
* **Annual Members:** Activity peaks sharply during traditional weekday commuting hours (Monday through Friday).
* **Casual Riders:** Activity concentrates heavily on weekends (Saturday and Sunday) for leisure and recreation.

### 3. Hourly Commute Spikes
* **Members:** Display pronounced dual-peak spikes at **8:00 AM** and **5:00 PM** (typical work commute windows).
* **Casual Riders:** Volume builds gradually during the day, peaking in the afternoon around **5:00 PM – 6:00 PM**.

### 4. Seasonal Trends
* Both user segments experience heightened activity during summer months (**June to August**).
* Casual rider demand drops sharply during winter, showing high seasonal sensitivity compared to members.

---

## 💡 Strategic Recommendations

1. **Weekend & Leisure Conversion Campaigns:**
   * Launch targeted digital promotions near popular recreational stations, parks, and tourist spots during weekends.
   * Offer limited-time "weekend-to-annual" membership discounts for frequent weekend riders.

2. **Commuter Incentives:**
   * Introduce gamified rewards or loyalty points for weekday peak rides to encourage casual weekday riders to upgrade to full memberships.

3. **Seasonal Membership Passes:**
   * Offer flexible "Spring/Summer Seasonal Passes" or trial bundles starting in April to capture warm-weather casual demand and gradually transition them into full annual memberships.

---

## 📁 Repository Structure
* `Cyclistic Bike-Share Analysis.docx` — The full academic-style case study report.
* `cyclistic_analysis.ipynb` — The complete Python data cleaning and exploratory data analysis (EDA) notebook.
* `README.md` — Project overview and executive documentation.
