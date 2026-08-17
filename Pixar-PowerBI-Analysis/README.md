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
![Financial Performance and Movie Reviews](financial_performance.png)

#### **2. Genre Trends & Subgenre Dynamics**
An exploratory view tracking box office trajectory over time, genre performance distributions, scatter-plot profitability matrices (Budget vs. Global Gross), and high-grossing subgenre breakdowns.
![Genre Trends and Subgenre Dynamics](genre_trends.png)

#### **3. Custom Tooltip Functionality**
Context-aware, report-page tooltips configured to deliver granular per-film metrics (break-even status, awards summary, and release detail) upon hovering over chart elements.
![Custom Tooltip Functionality](custom_tooltips.png)

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
