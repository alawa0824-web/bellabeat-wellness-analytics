# Bellabeat Wellness Analytics Case Study

Author: Alaa Mohammad Awad  
Date: November 2026  
Certificate: Google Data Analytics Capstone Project  

---

## Executive Summary
Bellabeat is a high-tech manufacturer of health-focused products for women. This project analyzes public smart device fitness data (FitBit Fitness Tracker Data) to uncover user behavioral patterns regarding daily activity, sleep hygiene, and weight tracking. The findings inform data-driven marketing strategies and product enhancement initiatives across Bellabeat's ecosystem.

---

## Tools & Technologies Used
- Data Processing & Manipulation: Python (pandas, numpy)
- Environment: Google Colab
- Data Visualization: Matplotlib / Seaborn
- Data Source: Public FitBit Fitness Tracker Data (Mobius via Kaggle)

---

## Key Findings

### 1. Sedentary Lifestyle & Sleep Impact
- A moderate-to-strong negative correlation (-0.53) was established between daytime sedentary minutes and total sleep duration.
- High daytime inactivity directly correlates with reduced overall sleep hygiene and shorter sleep duration.

### 2. Daily Step Distribution
- Users logged an average of 7,281 steps per day, clustering mostly between 4,000 and 10,000 steps.
- A significant portion of users fall short of the recommended 10,000-step daily benchmark.

### 3. Peak Activity Windows
- Hourly step analysis revealed bimodal activity peaks during midday (12:00 PM) and early evening (5:00 PM – 7:00 PM).
- Activity drops sharply during nighttime hours, bottoming out between 1:00 AM and 5:00 AM.

### 4. Health Tracking Friction
- Weight log entries showed a heavy reliance on manual reporting (64.3%) compared to automatic entries (35.7%).
- Manual data entry presents a primary user friction point that leads to long-term tracking drop-offs.

---

## Strategic Recommendations

### 1. Targeted Inactivity Alerts
- Program wearable devices (Leaf, Time) and the Bellabeat app to issue gentle vibration prompts during prolonged daytime inactivity to help users improve overall sleep quality.

### 2. Timed Push Notifications
- Schedule activity prompts and wellness reminders immediately before natural peak hours (12:00 PM and 5:00 PM – 7:00 PM) when users are most likely to engage.

### 3. Streamlined Ecosystem Integration
- Highlight automated tracking features (such as smart scales and the Spring water bottle integration) in marketing campaigns to reduce manual tracking burden and improve user retention.

---

## Repository Structure
- Bellabeat Wellness Analytics Case Study.docx — Full academic report.
- bellabeat_analysis.ipynb — Python data analysis notebook.
- README.md — Project documentation.
