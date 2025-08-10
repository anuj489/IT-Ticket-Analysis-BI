# 📊 IT Ticket Analysis - Power BI Dashboard

## 📌 Project Overview
The **IT Ticket Analysis** dashboard provides a comprehensive view of IT help desk ticket data from **100,000 records**.  
It allows IT teams and management to track ticket resolution patterns, severity levels, priorities, and performance metrics.  
The insights help improve ticket resolution times, allocate resources efficiently, and identify problem areas.

---

##  Live Power BI Dashboard

[![View the Live Dashboard](https://img.shields.io/badge/View-Live%20Dashboard-blue?style=for-the-badge)](https://app.powerbi.com/reportEmbed?reportId=1682fa8f-092e-4d42-b0b9-0bd4b9acaf0d&autoAuth=true&ctid=e1d99821-ef38-4f48-836f-7a7ca113dab7)

> **Note:** Clicking the badge will open the live report on Power BI service. A **Power BI Pro** license or Premium capacity may be required to view the report, and users may need to sign in when accessing it.:contentReference[oaicite:0]{index=0}

## 📂 Project Files
| File Name | Description |
|-----------|-------------|
| `IT TICKET ANALYSIS Github.pbix` | Main Power BI report file |
| `IT-Help-Desk.xlsx` | Source dataset for IT tickets |
| `BillTheme1.json` | Custom Power BI theme for styling |
| `Date table code new.txt` | DAX script for creating a date table |
| `last refresh date.txt` | Note on last data refresh date |
| `ticket.png` | Screenshot of the dashboard |

---

## 📊 Dashboard Features
### **KPIs**
- **Total Users:** 967  
- **Total Tickets:** 100K  
- **Total Days:** 684K  
- **Average Resolution Days:** 6.84  
- **Total Departments:** 15  

### **Filters**
- Severity  
- Priority  
- Ticket Type  
- Satisfaction  
- Departments  
- Requestor Seniority  
- Filed Against  

### **Visualizations**
1. **Total Tickets by Business Unit & Groups** – Bar chart showing ticket count by business unit.
2. **Total Tickets & IT Owner Count by Department** – Combo chart with bar & line.
3. **By Severity** – Donut chart showing severity distribution.
4. **By Priority** – Donut chart showing ticket priorities.
5. **By Ticket Type** – Donut chart showing issue/request distribution.
6. **By Gender** – Donut chart for gender-based ticket reporting.

---

## 📏 Measures Used
The following **DAX measures** were created for analysis:
- `AvG RES. Days` → Average ticket resolution days  
- `Total Days` → Total days tickets remained open  
- `Total Departments` → Count of unique departments  
- `Total Tickets` → Count of total tickets  
- `Total Users` → Count of unique users  
- `Measure logic` & `Measure Selected` → Used for dynamic filtering & slicers

---

## 🗂 Data Model
Final columns and data types after Power Query transformations:

| Column Name | Data Type |
|-------------|-----------|
| ticket | Int64.Type |
| Last Name | text |
| Departmets | text |
| Groups | text |
| Marital Status | text |
| Age | Int64.Type |
| Business Unit | text |
| Gender | text |
| Job Classification | text |
| RequestorSeniority | text |
| ITOwner | Int64.Type |
| FiledAgainst | text |
| TicketType | text |
| Severity | text |
| Priority | text |
| daysOpen | Int64.Type |
| Satisfaction | text |

---

## ⚙️ How to Use
1. **Download** the `.pbix` file and open in **Power BI Desktop**.
2. Load the dataset `IT-Help-Desk.xlsx` (already linked inside the report).
3. Refresh data to update KPIs and visuals.
4. Use the slicers on the left to filter and drill down into specific ticket attributes.

---

## 📅 Last Data Refresh
**15-05-2025** (as per dashboard refresh date indicator).

---



## 🚀 Insights & Outcomes
- Analysis based on **100,000 ticket records**.
- Identify departments with high ticket volumes.
- Monitor SLA compliance through resolution days.
- Track severity and priority trends to manage workload.
- Improve resource allocation by analyzing group-wise ticket distribution.

---

## 🛠 Tools & Technologies Used
- **Power BI Desktop**
- **Power Query M**
- **DAX**
- **Excel**

---

## 📬 Contact
**Author:** Anuj Agarwal  
📧 Email: anuj489@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/anuj-agarwal-87140a183)

---
## 📸 Dashboard Preview


<img width="1214" height="680" alt="image" src="https://github.com/user-attachments/assets/128df13e-1ea0-42d0-b22d-54b85c90cd85" />
<img width="1209" height="681" alt="image" src="https://github.com/user-attachments/assets/fdd79be3-cde7-4bf1-b216-2c383d85a911" />


