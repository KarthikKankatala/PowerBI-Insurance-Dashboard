# 📊 Insurance Business & Customer Feedback Analysis Dashboard

## 🔍 Objective
To build a dynamic and interactive Power BI dashboard that analyzes both business metrics and customer sentiment data for an insurance company. The dashboard helps stakeholders make data-driven decisions to optimize policy offerings and improve customer satisfaction.

---

## 🛠️ Tools & Technologies Used
- **Power BI**
- **MySQL Server** (Primary Data Source)
- **CSV & Excel Files**
- **Power Query**
- **DAX (Data Analysis Expressions)**

---

## 🗃️ Data Sources & Integration
1. **Insurance Policy & Transaction Data**  
   - Imported directly from **MySQL Server** into Power BI for real-time and scalable data access.
2. **InsuranceData.csv**  
   - Contains a claim and region-wise breakdown of insurance activities.
3. **Insurance Customer Feedback.xlsx**  
   - Captures customer satisfaction data, including ratings, sentiment, and communication channels.

---

## 🔄 Data Preparation & Transformation
- Connected Power BI to **MySQL Server** using native connectors.
- Performed data wrangling and transformation in **Power Query**:
  - Cleaned nulls and data type mismatches
  - Renamed and removed redundant columns
  - Merged datasets via relationships on policy/customer IDs
- Created custom KPIs and logic using **DAX**

📌 *Visual References*:
- `Insurance Data Transformation.png`
- `Feedback Data Transformation.png`

---

## 📈 Dashboard Features

### 🔹 Insurance Business Overview
- **KPIs:**
  - Total Premium Collected
  - Claim Amounts
  - Net Profit
  - Policy Distribution by Region & Policy Type
- **Visualizations:**
  - Line & bar charts, card KPIs, region-wise maps
- **Interactivity:**
  - Slicers for Date, Region, and Policy Type

📷 *See:* `Insurance Dashboard.png`, `Dashboard.png`

---

### 🔹 Customer Feedback Analysis
- **Sentiment Tracking**: Categorized as Positive, Neutral, and Negative
- **Feedback Channels**: Breakdown by Website, Email, Phone, etc.
- **KPIs**:
  - Average Rating
  - Monthly Feedback Volume Trends

📷 *See:* `Table Visual.png`

---

## 📊 Key Insights
- Identified top-performing regions with the highest premium collections
- Detected high claim regions requiring risk mitigation strategies
- Uncovered negative sentiment trends tied to service delays
- Provided actionable insights to improve customer experience and profitability

---

## ✅ Outcome
- Developed a full-fledged Power BI dashboard with **live MySQL data integration**
- Enabled self-service analytics for stakeholders
- Delivered strategic insights combining business and sentiment data

---

## 👨‍💻 Role & Contributions
- Imported and modeled data from **MySQL Server**
- Performed data cleansing and transformation using Power Query
- Built calculated fields and KPIs using DAX
- Designed and published dashboard visuals
- Presented findings to the team with actionable insights

---

## 📎 Files Included
- `InsuranceData.csv`
- `Insurance Customer Feedback.xlsx`
- `Insurance Dashboard.pbix`
- `Dashboard.png`, `Insurance Dashboard.png`
- `Insurance Data Transformation.png`
- `Feedback Data Transformation.png`
- `Table Visual.png`

---

## 🏷️ Tags
`Power BI` `MySQL` `Dashboard` `Insurance Analytics` `Customer Feedback` `DAX` `Data Transformation` `Sentiment Analysis`

---

## 📷 Dashboard Previews

### Insurance Business Overview
![Insurance Dashboard](Insurance%20project/Assets/Insurance%20Dashboard.png)

### Table Visual
![Table Visual](Insurance%20project/Assets/Table%20Visual.png)

### Feedback Analysis
![Feedback Analysis](Insurance%20project/Assets/Feedback%20Analysis.png)

### Dashboard
![Dashboard](Insurance%20project/Assets/Dashboard.png)

### Insurance Data Transformation
![Insurance Data Transformation](Insurance%20project/Assets/Insurance%20Data%20Transformation.png)

### Feedback Data Transformation
![Feedback Data Transformation](Insurance%20project/Assets/Feedback%20data%20transormation.png)
