# people-analytics-employee-lifecycle
End-to-end People Analytics case study simulating a high-growth fintech environment, covering hiring funnel analysis, attrition modeling, engagement insights, and workforce planning using SQL (BigQuery), Python, and Looker-style dashboards.

# 👥 People Analytics Case Study  
## Employee Lifecycle Insights & Attrition Strategy (Fintech-Style)

📌 **Project Type:** Portfolio Case Study  
🏢 **Domain:** People Analytics / HR Analytics  
🚀 **Context:** High-growth Fintech (Tabby-style)

---

## TL;DR
• Built an end-to-end People Analytics solution covering hiring, attrition, engagement, and workforce planning  
• Used SQL (BigQuery), Python, and Looker-style dashboards  
• Focused on leadership decision-making, not just reporting  
• Designed to mirror real People Data Analyst work in a fintech company  

---

## 📌 Project Overview
This project simulates a **People Analytics function inside a high-growth fintech company**, demonstrating how HR data can be transformed into **actionable insights for People, Finance, and Leadership teams**.

The case study covers the **entire employee lifecycle** — from hiring and onboarding to performance, engagement, attrition, and workforce planning — using **SQL, Python, and BI dashboards**.

---

## 🎯 Business Objectives
The People Team aimed to answer:

- Where are we losing employees — and **why**?
- Which employee segments are at **highest attrition risk**?
- How efficient is our **hiring funnel and time-to-hire**?
- How do **engagement and performance** impact retention?
- What does our **workforce trajectory** look like over the next 6 months?

---

## 🗂️ Data Sources (Simulated HR Systems)

| Dataset | Description |
|------|------------|
| employees | Core HRIS data (role, department, hire/exit dates, performance, engagement) |
| recruitment | ATS-style hiring funnel data (applications → interviews → offers → hires) |
| attendance | Absenteeism & working-hours data (engagement proxy) |
| performance_history | Historical performance review records |

Datasets were modeled to reflect **real-world HR data challenges** (missing values, delayed updates, cross-system joins).

---

## 🧠 Key Analyses Performed

### 1️⃣ Workforce & Headcount Analysis
- Active headcount trends
- Department & location distribution
- Manager span-of-control analysis

### 2️⃣ Hiring Funnel & Time-to-Hire
- Funnel conversion rates by role and department
- Time-to-hire diagnostics
- Identification of hiring bottlenecks

### 3️⃣ Attrition & Retention Analysis
- Monthly & annualized attrition rates
- Attrition by tenure, department, and performance
- Early-tenure attrition risk (0–6 months)

### 4️⃣ Engagement & Performance Insights
- Engagement score vs attrition relationship
- Performance rating vs retention
- Absenteeism as early risk indicator

### 5️⃣ Attrition Risk Modeling
- Logistic regression model for attrition risk segmentation
- Key drivers: tenure, engagement, performance, absenteeism
- Model used for **decision support**, not prediction theater

### 6️⃣ Workforce Planning
- Headcount trend analysis
- 6-month workforce forecast
- Hiring vs attrition scenario thinking

---

## 📊 Dashboards (Leadership-Ready)

**Designed using Looker-style best practices**

### Executive People Dashboard
- Active Headcount
- Attrition %
- Hiring Velocity
- Engagement Index

### Hiring & Recruitment Dashboard
- Funnel conversion rates
- Time-to-hire by department
- Offer acceptance trends

### Attrition & Retention Dashboard
- Attrition by tenure & department
- Performance vs attrition
- Engagement risk heatmap

### Workforce Planning Dashboard
- Headcount forecast
- Attrition risk distribution
- Manager span-of-control

---

## 🧰 Tech Stack

**Analytics & Modeling**
- SQL (BigQuery-style)
- Python (pandas, numpy, scikit-learn)

**Visualization**
- Looker Studio
- Tableau

**Data Handling**
- HRIS & ATS-style data modeling
- Data quality validation

---

## 📈 Key Insights & Recommendations

### Insights
- Attrition risk is **highest in the first 6 months**, especially among low-engagement employees
- Performance ratings below 3 strongly correlate with voluntary exits
- Hiring bottlenecks occur at the interview-to-offer stage
- Referral hires show faster time-to-hire and stronger retention

### Recommendations
- Introduce structured onboarding & early engagement checks
- Focus retention interventions on high-risk segments
- Optimize hiring workflows for critical roles
- Use workforce forecasting to align hiring with growth plans

---

## 👩‍💼 Why This Case Study Matters
This project demonstrates how **People Analytics directly supports business outcomes**, including:
- Data-driven retention strategies
- Efficient hiring decisions
- Proactive workforce planning
- Clear executive communication

It reflects the responsibilities of a **People Data Analyst in a fintech environment**.

---

people_analytics_executive_dashboard_final.png

## 📁 Repository Structure
