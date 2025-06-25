## 🏗️ Construction Project Data Analysis & Automation

This Python project automates the cleaning, analysis, and reporting of construction project data using **pandas**. It delivers actionable insights into material costs, labour utilisation, monthly trends, and project status. The script runs from start to finish and generates a ready-to-share Excel report with all results clearly organised.

---

## 🔍 Project Overview

This script automates the following steps:

### 1. Data Cleaning
- Renames inconsistent column headers
- Removes duplicate rows (by `Project_ID` and `Report_Date`)
- Fills missing values in `Material_Cost` and `Labor_Hours` with mean values
- Converts `Report_Date` to datetime and `Project_Progress` to numeric
- Standardises text fields (e.g. `Project_Status`)

2. **Data Analysis**
   - It identifies site locations with highest and lowest average material cost
   - It checks the correlation between labour hours and project progress
   - It tracks monthly totals for material cost and labour usage
   - It counts projects per status (e.g., Completed, In Progress, Delayed)
   - It calculates the total cost proxy to identify top and bottom 5 most expensive projects

3. **Excel Report Export**
   All results are exported to a multi-sheet Excel file:  
📄 `cleaned_construction_data.xlsx`

With the following sheets:
- **Cleaned_Data** – Fully cleaned dataset
- **Analysis_Insights** – Key insights, monthly trends, and project counts
- **Top_Bottom_Projects** – Top 5 and bottom 5 projects based on estimated total cost

---

## 🧰 Tools Used

- Python 3.x
- pandas
- matplotlib
- seaborn
- XlsxWriter (Excel export engine)

---

## 📁 File Structure
📦 construction-data-analysis
├── construction_data_analysis.py     # Main Python script with cleaning & analysis
├── sample_construction_data.csv      # Sample data (optional or anonymised)
├── cleaned_construction_data.xlsx    # Output Excel report (auto-generated)
└── README.md                         # Project documentation

---

## 📬 Contact

**Chibuzor Michael Mathias**  
Data Analyst & Python Automation Specialist  
🔗 🔗 [GitHub Profile](https://github.com/chi-matty)
🔗 [LinkedIn Profile](https://www.linkedin.com/in/michael-matty)
📧 mathiasmichael2@gmail.com