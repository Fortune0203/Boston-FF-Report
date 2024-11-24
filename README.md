# **Power BI Report: Boston Freight Forwarder Company Analysis**

### **Overview**
This Power BI report analyzes operational and financial data for **Boston Freight Forwarders**, highlighting their performance from **2020 to 2023**. The report provides insights into revenue, profit, and cost trends across different clients and service types, helping the company optimize operations and profitability.

---

### **Key Features**
1. **Dashboard Overview**:
   - **KPI Cards**: 
     - Total Revenue
     - Total Profit
     - Average Profit per Job
   - Dynamic slicers for Year, Month, and Client Name.
   
2. **Profit Trends**:
   - Line chart visualizing profit over time (2020–2023).
   - Comparison across clients and service types using a legend.

3. **Revenue vs. Cost Analysis**:
   - Line chart comparing monthly revenue and cost trends.

4. **Detailed Job Breakdown**:
   - Table with columns: Job ID, Year, Month, Client Name, Service Type, Revenue, Cost, Profit.
   - Interactivity through slicers for Year, Month, and Client Name.

5. **Filters for Enhanced Interactivity**:
   - Year Selector
   - Month Selector
   - Client Name Selector

---

### **Visualizations**
- **KPI Dashboard**:
  - Summarizes key performance indicators (KPIs) such as Total Revenue, Total Profit, and Average Profit per Job.
  
- **Line Charts**:
  - Monthly trends for Revenue, Cost, and Profit.
  - Split by Client or Service Type for deeper insights.
  
- **Detailed Data Table**:
  - Shows job-level details for transparency and granular analysis.

---

### **Data Model**
The report is based on simulated data for **Boston Freight Forwarders**. Key assumptions include:
- Clients: Mikano, Philips, and individual car clearance services.
- Revenue and Cost figures in **millions of naira (₦)**, while Profit is in **thousands of naira (₦)**.
- Time range: 2020 to 2023.

---

### **How to Use**
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/boston-freight-powerbi-report.git
   cd boston-freight-powerbi-report
   ```

2. **Open the Power BI File**:
   - Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
   - Open the `Boston Freight Forwarder Report.pbix` file.

3. **Interact with the Report**:
   - Use slicers to filter data by year, month, or client name.
   - Explore KPIs, trends, and detailed tables to gain insights.

---

### **Technical Details**
1. **Power BI Features Used**:
   - Card Visuals for KPIs.
   - Line Charts for trends.
   - Table Visual for detailed breakdown.
   - Slicers for interactivity.
   - Page Navigation Buttons for better usability.
   - Drill Through For Revenue and profit to the Detailed Breakdown

2. **Data Transformations**:
   - Applied calculated columns for Monthly Profit, Revenue, and Cost.
   - Used custom formatting for monetary figures (millions/thousands).
   - Sorted months chronologically using a separate column.

3. **Pages**:
   - **Page 1: KPI Dashboard**
   - **Page 2: Profit & Revenue Trends**
   - **Page 3: Profit Trends**
   - **Page 4: Detailed Breakdown**

---

### **Future Improvements**
- Add predictive analytics to forecast revenue and profit.
- Incorporate additional metrics such as job completion time and customer satisfaction.
- Automate data updates using Power BI Service.

---

### **License**
This project is licensed under the [MIT License](LICENSE).

---
