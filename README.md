# Excel_Marketing_Analysis
End-to-end Digital Marketing Campaign &amp; ROI Analytics project in Excel. Features data cleaning of 1,000+ messy records using Power Query, KPI calculations (CPC, CPA, ROI), Pivot Tables, and an interactive executive dashboard
# 📊 Digital Marketing Campaign & ROI Analytics Dashboard

## 🎯 Project Overview
This end-to-end Data Analytics project simulates a real-world freelance client scenario for a digital marketing agency. A messy raw dataset of *1,000+ marketing campaign records* was cleaned, transformed, and analyzed in *Microsoft Excel* to build an interactive executive dashboard tracking *Ad Spend, Revenue, Conversions, CPC, CPA, and ROI* across multiple advertising platforms.

## 🛠️ Tools & Techniques Used
* *Microsoft Excel:* Power Query, Data Cleaning, Advanced Formulas (IFERROR, TEXT, ABS), Pivot Tables, Pivot Charts, Slicers, and Interactive Dashboard Design.
* *Python (Pandas, NumPy):* Synthetic messy dataset generation for realistic data cleaning practice.

## 🧹 Data Cleaning & Transformation
* *Removed Duplicates:* Eliminated 25 duplicate campaign records.
* *Standardized Categories:* Unified inconsistent platform names (IG, Insta → Instagram; FB → Facebook) and campaign statuses (active → Active; PAUSED → Paused).
* *Fixed Mixed Date Formats:* Used *Power Query* (en-GB / en-US fallback logic) to standardize mixed date formats into a single consistent Date column.
* *Handled Errors & Missing Values:* Replaced text errors (abc) and blank values in Ad_Spend and Clicks, and corrected negative Revenue entries.
* *Feature Engineering:* Created calculated columns for *CPC (Cost Per Click), **CPA (Cost Per Acquisition), **ROI (%), and **Month*.

## 📈 Dashboard Features
* *KPI Summary Cards:* Total Ad Spend, Total Revenue, Total Conversions, and Average ROI.
* *Ad Spend vs. Revenue by Platform:* Clustered column chart comparing spending against revenue across Facebook, Google, Instagram, LinkedIn, and Twitter.
* *Monthly Conversions Trend:* Line chart tracking conversion performance over time.
* *Ad Spend Share by Platform:* Donut chart illustrating budget allocation.
* *Interactive Slicers:* Dynamic filters for *Platform, **Status, and **Month* connected to all visuals.

## 🖼️ Dashboard Preview
![Digital Marketing Dashboard](dashboard_screenshot.png)

## 📂 Repository Files
* marketing_data_1000_rows.csv — Raw messy dataset
* Digital_Marketing_Dashboard.xlsx — Cleaned dataset, Pivot Tables, and Interactive Excel Dashboard
* dashboard_screenshot.png — Final dashboard preview image

## 📬 Connect With Me
Open for *Freelance Data Analytics & Excel Dashboard* projects! Feel free to reach out on LinkedIn or Fiverr.
