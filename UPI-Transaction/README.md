# 📊 UPI Transaction Analysis – India 2021

An end-to-end data analysis project exploring Unified Payments Interface (UPI) app trends in India using Python for EDA and Tableau for visualization.

---

## 🚀 Project Goals

- Analyze monthly UPI transactions for major apps like PhonePe, Paytm, and Google Pay
- Compare transaction volume and value trends across 2021
- Visualize market share of each app
- Identify seasonal or quarterly shifts

---

## 🛠️ Tools Used

- **Python** (Pandas, Seaborn, Matplotlib)
- **Jupyter Notebook**
- **Tableau Public**
- **GitHub** for version control

---

## 📁 Dataset

- 📄 File: `UPI apps transaction data in 2021.csv`
- 📦 Source: Open data (NPCI) or [Kaggle](https://www.kaggle.com/)
- 📊 Columns:
  - `upi_banks` – App names (PhonePe, Paytm, etc.)
  - `volume_(mn)` – Transactions (millions)
  - `value_(cr)` – Transaction value (crores)
  - `month`, `year` – Time data

---

## 📊 Exploratory Data Analysis (Python)

Performed using Jupyter Notebook:
- Grouped total transactions per app
- Plotted monthly volume and value trends
- Saved key visualizations in the `Plots` folder

🧪 Notebook: [`UPI.ipynb`]

---

## 📈 Tableau Dashboard

Interactive dashboard showing:
- Monthly volume & value trends by app
- Total volume bar chart
- December 2021 market share pie chart
- Filters for app, month, and year

🔗 [👉 View Tableau Dashboard](https://public.tableau.com/views/IndiasUPIGrowthDashboard/IndiasUPIGrowthDashboard2021Analysis?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 🧠 Key Insights

- **PhonePe** consistently led in both volume and value in 2021.
- **Paytm** showed noticeable growth in Q4.
- **December 2021** had the highest transaction activity.

---

## 💻 How to Use Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/shikatare/UPI-Dashborad
   cd upi-dashboard
