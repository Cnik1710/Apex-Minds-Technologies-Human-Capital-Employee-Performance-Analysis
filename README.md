# Apex Minds Technologies - Human Capital & Employee Performance Analysis
## 🎯 Objective
To analyze employee distribution and performance metrics across departments, experience, and career levels — and uncover insights driving salary patterns and workforce structure.
### **Project Purpose:**
   * Understand workforce demographics, experience, and pay distribution.
   * Identify key factors influencing salary and performance ratings.
   * Support HR and management in workforce planning and compensation decisions.
### **Key KPIs:**
   * Total Employees: 372
   * Total Departments: 8
   * Average Age: 38.2 yrs
   * Average Experience: 11.6 yrs
   * Average Salary: 3.12M
   * Total Salary Expense: 1Bn
### **Deliverables:**
   * Interactive Power BI dashboards with:
      * Headcount & Distribution Analysis
      * Salary & Performance Analysis
---

## 📘 Project Overview 
### **Context Highlights:**
   * ApexMinds Technologies Pvt. Ltd. is a growing tech enterprise with a diverse employee base across multiple departments such as R&D, Finance, Sales, Operations, and HR. The organization sought to build a data-driven understanding of its workforce distribution, experience composition, and salary dynamics to support strategic HR decisions.
   * This project leverages Power BI to visualize and analyze employee data holistically—enabling the management team to track headcount trends, salary distribution, and performance alignment.By transforming raw employee records into actionable insights, the analysis provides a 360° view of how factors like experience, rating, career level, and department influence compensation and workforce balance.
   * The dashboards are designed to:
      * Improve transparency in HR and salary-related analytics.
      * Support fair pay structures and promotion planning.
      * Enable better resource allocation across departments.
      * Serve as a baseline for future workforce forecasting and talent strategy.
---

## 🗂️ Data Overview & Schema
### **Data Source:**
   * Source: Fictionalized Human Resource Management dataset (inspired by open educational datasets).
   * Data Type: Structured employee master records with demographic and job details.
   * Time Period: Snapshot of workforce data for a specific financial year.
### **Data Structure & Metrics:**
   * Key Index Type: Employee ID (unique identifier for all records).
   * Total Rows: ~372 Employees across 8 Departments.
   * Categories: 15+ columns grouped under the following:
      * Demographics: Age, Gender, Joining Year
      * Employment Details: Department Code, Rating, Experience (Years), Career Level
      * Compensation Data: Salary, Pay Scale
      * Derived Columns (Calculated):
        * Career Level Hierarchy (Young Talent → Senior Professional)
        * Age Group (19–28, 29–38, 39–48, 49+)
        * Experience Buckets (0–5, 6–10, etc.)
   * **Calculated Metrics:**
       * Average, Median, Min, Max Salary
       * Total Salary Expense by Department, Rating, and Experience
       * Employee Count per Segment
---

## 💻 Tech Stack    
### **Tools:**
   * **Excel**
      * Data cleaning & preprocessing
   * **PowerQuery** 
      * ETL transformations
   * **PowerBI**
      * Visualization, DAX measures & dashboard design
      * DAX – Calculated measures and time intelligence
    * **PowerPoint**
      * Presentation and final dashboard snapshots
---

## 📈 Methodology & Analysis  
### **Preparation, Process & Analytical Approach:** 
   * **Data Preparation & Cleaning:**
       * Imported and validated the HR dataset in Power BI.
       * Checked for missing or inconsistent salary, department, and rating entries.
       * Ensured numeric fields (Experience, Salary) were properly typed and formatted.
       * Removed redundant columns and standardized categorical labels (Department Codes, Pay Scales).
   * **Data Modeling & Integration:**
       * Defined relationships among core fields (Employee → Department → Career Level).
       * Added calculated columns using DAX SWITCH() for Career Hierarchy Labeling.
       * Created measures for Average, Median, and Total Salary across key dimensions.
       * Integrated slicers and hierarchies (Age, Experience, Rating, Pay Scale).
   * **Feature Engineering:**
       * Grouped employees into Age Brackets and Experience Buckets for trend clarity.
       * Derived Total Salary Expense and Average Salary by Rating metrics dynamically.
   * **Visualization Design:**
       * Built two interactive dashboards:
         * Headcount & Distributions
         * Salary & Performance
       * Integrated interactive slicers for quick segmentation analysis.
   * **Validation & Formatting:**
       * Cross-verified total employees, salary sums, and averages across visuals.
       * Standardized labels, axis titles, and tooltips.
---

## ❓ Problem Statement
Understanding workforce structure and pay dynamics is crucial for Apex Minds to ensure fair compensation, efficient talent utilization, and cost optimization.
### Key Questions:
   * How is the workforce distributed across departments and career levels?
   * How do experience and rating impact salary outcomes?
   * What is the relationship between experience, age, and salary?
   * Which departments incur the highest total salary expense?
   * What is the salary growth trend across hierarchical levels?
---

## 💡 Key Insights      
### **Top Findings:** 
   * Majority of workforce concentrated at Senior Professional level (133 employees)
   * Average Salary increases steadily up to Established Professional level (3.4M)
   * R&D and Finance have the highest total salary expenses
   * Age 29–38 group forms the largest segment (~28% of total employees)
   * Salary growth aligns closely with both Experience and Rating patterns

### **Supporting Metrics:**
   * Lowest Salary: 362K, Highest: 6M
   * Rating-wise salary spread consistent (0.22–0.25Bn each)
   * Clear upward trend in total expense with experience years until 15+
---

## 📍 Conclusion
### **Summary:**
   * The analysis highlights Apex Minds’ balanced workforce distribution with gradual salary progression across experience and hierarchy levels.Insights enable HR to refine pay scale structures, recognize high-cost departments, and plan targeted upskilling and retention strategies.
   
   * Strong correlation between experience and salary growth up to mid-level professionals.
   
   * R&D and Finance departments contribute the most to salary expenditure.
   
   * Senior Professionals form the largest segment (133 employees), reflecting a matured workforce structure.
   
   * Rating-based salary variation remains steady, suggesting balanced performance-linked pay.
   
   * Age group 29–38 years dominates both in count and compensation level.
   
   * Overall, the dashboards empower HR leaders to make data-informed decisions in promotions, hiring, and budgeting — marking a significant step toward analytics-driven workforce management.
---

## 🖥️ Dashboard Overview
### Headcount & Distribution
![image_alt]()

### Salary & Performance
![image_alt]()

---

## ✅ Business Impact & Use Cases   
  * HR Planning: Identify gaps in experience and career level balance.

  * Compensation Strategy: Adjust salary structures per role hierarchy.

  * Performance Management: Link ratings to pay equity.

  * Departmental Costing: Track total expense per function for budgeting.
---

## 🙏 Acknowledgements & Contact 
### Project Analyst: Anik Chakraborty	
   📧 Email: anikc1710@gmail.com  
### Special Thanks To: 
   * Coding Ninjas – for project framework and guidance  
