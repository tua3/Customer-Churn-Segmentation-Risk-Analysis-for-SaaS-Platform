# Customer-Churn-Segmentation-Risk-Analysis-for-SaaS-Platform
Churn segmentation and behavioral risk analysis for SaaS users using SQL and Power BI.
# Customer Churn Segmentation & Behavioral Risk Analysis (SaaS)

## 📌 Project Overview
This project analyzes customer churn behavior for a SaaS platform to identify which user segments are most at risk of cancellation and what behaviors predict churn.

The objective is to support data-driven retention strategies by understanding how device type, acquisition channel, and early product engagement affect customer retention.

---

## 🎯 Business Questions
- Which user segments have the highest churn rates?
- Does device type influence churn behavior?
- Do acquisition channels bring long-term users or high-risk users?
- How does activation speed affect churn probability?

---

## 📊 Dashboard
Power BI dashboard showing churn trends, segmentation, and behavioral risk factors:

📄 `/dashboard/churn_segmentation_dashboard.pdf`  
*(Screenshots may also be available in the dashboard folder)*

---

## 🗂 Dataset
All datasets are available in the `/data` folder:

- `saas_users.csv` — user signup, device, and acquisition data
- `saas_events.csv` — product usage events
- `saas_subscriptions.csv` — subscription status and revenue
- `marketing_spend.csv` — channel marketing costs

---

## 🛠 Tools & Techniques
- Power BI (data modeling, KPIs, segmentation dashboards)
- SQL (churn segmentation and behavioral queries)
- DAX measures and calculated columns
- Funnel and cohort-style behavioral analysis

---

## 🔍 Key Findings

### 1. Activation Speed Is the Strongest Retention Driver
Users who publish within the first day show significantly lower churn rates compared to slow or inactive users.

### 2. Mobile Users Show Slightly Higher Churn
Device-based analysis indicates usability and engagement differences between platforms.

### 3. Paid Channels Deliver Higher Churn Risk
Users from paid advertising channels churn more frequently than organic and referral users.

---

## ✅ Recommendations

- Improve onboarding flow to encourage immediate publishing behavior.
- Introduce guided templates and first-action prompts for new users.
- Reallocate marketing budget toward high-retention channels.
- Trigger proactive customer success outreach for slow-activation users.

---

## 📁 Repository Structure

