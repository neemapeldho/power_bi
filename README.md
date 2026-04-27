
# 📊 Cybersecurity Incident Analysis Dashboard

This project is a **Power BI dashboard** that analyzes cybersecurity incidents across countries, attack types, and years. It provides insights into incident frequency, financial losses, and resolution efficiency to support data-driven security decisions.

---

## 🚀 Overview

The dashboard helps answer key questions such as:

* Which cyber attacks are most frequent?
* Which attack types cause the highest financial loss?
* How long does it take to resolve incidents?
* Which countries are most impacted?

---

## 📌 Key Metrics

* **Average Resolution Time**

  ```DAX
  avg resolution = AVERAGE(Facts_cyber[Incident Resolution Time (in Hours)])
  ```
* Total Financial Loss (in Million $)
* Total Incident Count
* Target vs Actual performance comparison

---

## 📊 Dashboard Features

### 1. KPI Cards

* Displays high-level metrics like:

  * Avg resolution time
  * Financial loss
  * Target comparison

### 2. Attack Type Distribution

* Pie chart showing proportion of:

  * DDoS
  * Phishing
  * SQL Injection
  * Ransomware
  * Malware
  * Man-in-the-Middle

### 3. Financial Loss by Attack Type

* Bar chart comparing economic impact of each attack category

### 4. Country-Level Analysis

* Table showing:

  * Financial loss by country
  * Total resolution time
* Helps identify high-risk regions

### 5. Interactive Filters (Slicers)

* Country
* Year (2015–2020)
* Attack Type

---

## 🧩 Data Model

The report follows a **star schema**:

* **Fact Table**

  * `Facts_cyber`

* **Dimension Tables**

  * `Attack_type`
  * `Defense_mechanism`
  * `Location`
  * `Target_Industry`
  * `Year`

---

## 🛠 Tools & Technologies

* Power BI
* DAX (Data Analysis Expressions)
* Data Modeling

---

## 🎯 Use Cases

* Cybersecurity performance monitoring
* Risk assessment by attack type
* Financial impact analysis
* Strategic decision-making

---

## 📷 Dashboard Preview

<img width="1312" height="728" alt="Screenshot 2026-04-27 131028" src="https://github.com/user-attachments/assets/3780257c-3d15-42a1-932f-a786e5dedbea" />


<img width="1316" height="737" alt="Screenshot 2026-04-27 131137" src="https://github.com/user-attachments/assets/b7d2de7a-a96e-4a2e-8424-1413ed44b9db" />


---

## 📁 How to Use

1. Download the `.pbix` file from this repository
2. Open it using Power BI Desktop
3. Interact with filters and visuals

---

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repo and submit a pull request.

---
