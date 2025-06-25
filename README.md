## 🏗️ Construction Project Data Analysis & Automation

This Python project cleans, analyzes, and automates the reporting of construction project data using **pandas**. It is designed to help stakeholders gain insights into project costs, labour utilisation, progress tracking, and monthly trends — all exported into a neatly organised Excel report.

---

## 🔍 Project Overview

This script automates the following steps:

1. **Data Cleaning**
   - Renames inconsistent column headers
   - Drops duplicate entries
   - Fills missing values with column means
   - Converts text to standard formats and correct data types

2. **Data Analysis**
   - Identifies site locations with highest and lowest average material cost
   - Checks correlation between labour hours and project progress
   - Tracks monthly totals for material cost and labour usage
   - Counts projects per status (e.g., Completed, In Progress, Delayed)
   - Calculates total cost proxy to identify top and bottom 5 most expensive projects

3. **Excel Report Export**
   - Outputs a multi-sheet Excel file named `cleaned_construction_data.xlsx` containing:
     - **Cleaned_Data**: Full cleaned dataset
     - **Analysis_Insights**: Cost insights, monthly trends, and status counts
     - **Top_Bottom_Projects**: Top 5 and bottom 5 projects based on cost metric

---

## 🧰 Tools Used

- Python 3.x
- pandas
- matplotlib
- seaborn
- XlsxWriter (Excel export engine)

---

## 📁 File Structure
