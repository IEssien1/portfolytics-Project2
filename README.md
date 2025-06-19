# 🛒 Olist Sales Funnel Web App

This project analyzes the Olist sales funnel using Python and presents key performance insights through an interactive Streamlit dashboard. The goal is to identify lead drop-off points, optimize conversion rates, and improve business decision-making.

---

## 📌 Problem Statement

Olist is an e-commerce platform that connects small businesses to major marketplaces in Brazil. However, a significant number of potential customers drop off at various stages of the sales funnel, resulting in lost revenue opportunities.

---

## 🎯 Objectives

- Analyze the Olist sales funnel
- Identify bottlenecks where leads are lost
- Evaluate sales team performance and delivery logistics
- Visualize insights using an interactive Streamlit dashboard

---

## 🔧 Tools & Technologies

- Python
- Pandas, NumPy
- Seaborn, Matplotlib, Plotly
- Streamlit
- Kaggle API (for data import)

---

## 🚀 Project Workflow

### 1. Data Collection
- Imported Olist sales data using the Kaggle API

### 2. Data Cleaning & EDA
- Built a reusable data cleaning pipeline
- Performed exploratory data analysis (EDA)

### 3. Metrics Analyzed

#### 🔁 Conversion Metrics
- Overall conversion rate from MQLs to closed deals
- Conversion rates by marketing channel
- Conversion rates by business segment or lead type

#### ⏱️ Time-Based Metrics
- Average time to close a deal
- Conversion velocity by time-to-close buckets

#### 👥 Sales Team Performance
- Top-performing SDRs and SRs based on closed deals

#### 📦 Order Fulfillment Metrics
- Average delivery time
- Percentage of delayed orders

### 4. Dashboard Development
- Built and deployed a Streamlit dashboard for stakeholder interaction

---

## 📊 Key Findings

1. **Low Conversion Rate**  
   - Only **10.4%** of quality leads convert to closed deals.  
   - Recommendation: Train sales teams and introduce performance incentives.

2. **Top Marketing Channels**  
   - Best performing: _Unknown Channel_, followed by Paid Search, Organic Search, Direct Traffic, and Referrals.  
   - Recommendation: Investigate the "Unknown Channel" for optimization opportunities.

3. **Lead Type Performance**  
   - **Online leads** had the highest conversion rate.  
   - Recommendation: Prioritize and nurture these leads for faster deal closures.

4. **Conversion Time**  
   - Average time to close a deal: **49 days**  
   - However, **61.6%** of deals are closed within 30 days, indicating high-quality leads.

5. **Sales Team Efficiency**  
   - The top SDR and SR each closed **2× more deals** than the team average.  
   - Recommendation: Reward high performers and implement mentorship for low performers.

6. **Order Delivery Issues**  
   - Average delivery time: **13.9 days**  
   - **10%** of orders delayed  
   - Recommendation: Optimize logistics and reduce delay rate to under **5%**

---

## 🖥️ Web App Demo

⚡ _Deployed with Streamlit_

> 📌 _[Include a link here if deployed]_  
> _e.g., [View Dashboard](https://olist-sales-funnel.streamlit.app)_

![Screenshot](images/barplot.png)  
*Conversion rate and lead source breakdown example*

---

## 💻 How to Run the Project Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/olist-sales-funnel.git
   cd olist-sales-funnel
