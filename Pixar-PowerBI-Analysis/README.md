# 🎬 Pixar Feature Films: Financial Performance & Profitability Analysis

## **Power BI Portfolio Project**

### **Project Overview**

This project delivers a  financial and commercial evaluation of Pixar Animation Studios' feature movies. Developed in Microsoft Power BI, the interactive dashboard converts  entertainment industry metrics into an actionable, data-driven narrative. 

By implementing  relational data modeling and creating custom DAX measures, the dashboard analyzes production budgets, worldwide box office gross distributions, Return on Investment (ROI) tiers, critical award recognitions, release timelines, and genre profitability dynamics.

The primary objective is to evaluate: **How does Pixar balance blockbuster franchise reliance with original intellectual property, and what factors drive long-term commercial and critical ROI?**

---

### **Key Insights & Practical Applications**

* **Blockbuster Dependency vs. Portfolio Stability:** Pixar’s long-term profitability ($13B+ net profit on a $4B aggregate budget) is anchored by top-tier sequels (*Toy Story*, *The Incredibles*) and select standalone masterworks (*Toy Story*, *Finding Nemo*, *Inside Out 2*) achieving Green-tier ROI status (>100%).
* **Genre Profitability Concentration:** While Family and Adventure titles generate the largest aggregate gross volume, niche narrative categories such as Teen Drama achieve exceptional average gross margins when executed successfully.
* **Critical & Commercial Alignment:** Multi-variable correlation analysis confirms that critical acclaim (notably Academy Award nominations and wins) demonstrates a positive relationship with upper-tier global box office yields.

---

### **Dashboard Architecture & Visual Views**

#### **1. Financial Performance & Movie Reviews**
A comprehensive fiscal accounting view tracking individual movie profitability, production budgets, worldwide box office grosses, gross profit margins, and critical award accolades.
<img width="1227" height="705" alt="Power BI 01" src="https://github.com/user-attachments/assets/95fca1dd-96da-49c6-879c-ea696bd9a969" />


#### **2. Genre Trends & Subgenre Dynamics**
An exploratory view tracking box office trajectory over time, genre performance distributions, scatter-plot profitability matrices (Budget vs. Global Gross), and high-grossing subgenre breakdowns.
<img width="1202" height="672" alt="Power BI 02" src="https://github.com/user-attachments/assets/b81b67c9-a69a-43c7-a91b-99f86bf2b733" />


---

### **Technical Proficiencies & DAX Modeling**

* **Data Modeling:** Star-schema design connecting dimension tables (Films, Genres, Release Dates, Awards) to centralized financial fact tables.
* **DAX Calculations:**
  * Dynamic **ROI %** and **Net Profit** metrics.
  * Conditional formatting KPI measures (e.g., Green/Yellow/Red ROI classifications).
  * Time Intelligence calculations evaluating box office trends across studio release eras.
* **Interactive UI/UX:** Parameterized slicing, synchronized visual filtering, and custom drill-through page tooltips.

---

### **Tools & Data**

| Tool / Resource | Purpose |
| :--- | :--- |
| **Microsoft Power BI Desktop** | Relational data modeling, DAX measure creation, and interactive dashboard authoring. |
| **Power Query** | ETL processes, data cleaning, data type enforcement, and schema shaping. |
| **Source Data** | Comprehensive dataset tracking production budgets, global box office revenue, release dates, genres, and Academy Award records for all Pixar releases. |
