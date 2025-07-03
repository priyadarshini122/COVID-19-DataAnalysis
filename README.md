# 🦠 COVID-19 Data Visualization Dashboard using Power BI

This project presents an interactive and insightful **COVID-19 dashboard** built using **Power BI**. It visualizes the spread and impact of the virus across different countries/regions using official data, offering users a comprehensive view of trends in confirmed cases, recoveries, deaths, and active cases over time.

---

## 📁 Project Overview

- 📊 **Tool Used**: Power BI Desktop
- 🗂️ **Dataset Source**: Kaggle – [COVID-19 Dashboard Dataset](https://www.kaggle.com/datasets/muntahamahin/covid-19-dashboard-with-powerbi)
- 🌐 **Scope**: Global COVID-19 data
- 📅 **Time Frame**: Daily updated data from 2020–2022 (depends on dataset version)

---

## 🎯 Key Features

- **KPI Cards**: Total Confirmed, Deaths, Recovered, Active Cases
- **Interactive Filters**: Country selection, date range slicers
- **Line Charts**: Daily trends of confirmed, deaths, and recovered cases
- **Map Visuals**: Geographic spread of the virus by country
- **Bar & Column Charts**: Top 10 affected countries
- **Custom DAX Measures**:
  - `Active Cases = Confirmed - Recovered - Deaths`
  - Mortality and Recovery Rate

---

## 🧠 Skills Demonstrated

- Data Import and Transformation using **Power Query**
- Data Modeling and Relationships
- Custom **DAX Calculations**
- Dashboard UI/UX Design in Power BI
- Data Storytelling and Insight Generation

---

## 📂 Files Included

- `COVID-19 Dashboard.pbix` – Power BI Dashboard file  
- `covid_19_data.csv` – Source dataset  
- `README.md` – Project overview and instructions  
- `Dashboard Screenshot.png` – Snapshot of final report

---

## 🛠️ How to Use

1. Clone/download this repository
2. Open `COVID-19 Dashboard.pbix` in Power BI Desktop
3. If dataset paths are broken, update source via:
   `Home > Transform Data > Data Source Settings`
4. Interact with slicers, maps, and charts for analysis

---

## 📌 About the Dataset

- Dataset includes columns: `Date`, `Country`, `Confirmed`, `Deaths`, `Recovered`
- Some versions may include state-wise or continent grouping
- Cleaned and formatted in Power BI for visualization

---

## 👤 Author

**Gaddala Priyadarshini**  
📍 Ongole, India  
📧 priyadarshinigaddala52@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/priyadarshini-g) | [GitHub](https://github.com/priyadarshini122)

---

## 🌟 Connect & Collaborate

If you have suggestions to improve the dashboard, feel free to fork this repo and open a pull request. Let’s learn and grow together!

---

## 📷 Sample Dashboard

*(Insert screenshot here)*

![COVID-19 Dashboard Screenshot](./Dashboard%20Screenshot.png)

---

## 📢 License

This project is for educational and portfolio purposes only.
