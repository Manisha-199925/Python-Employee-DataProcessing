# Python-Employee-DataProcessing-Python(Pandas)
  
  This project demonstrates an end-to-end data cleaning and preparation workflow in Python. It simulates real-world datasets for a company’s projects, employees, and seniority levels, then processes them for analysis.

The workflow includes:

1. Data Creation

Three datasets are created from scratch using Python dictionaries:

- Project Data – Contains project IDs, names, costs, and statuses.
- Employee Data – Includes employee details such as name, gender, city, and age.
- Seniority Level Data – Maps employee IDs to their designation levels.
  
2. Data Cleaning & Handling Missing Values

  Loaded Project.csv and checked for missing values in the Cost column. Applied a running average method by Replacing missing cost values with the average of all previous non-missing values. If no previous values, used 0.
  
3. Data Merging & Transformation

  Merged all three datasets into a master table. Performed various data transformations:

   - Added calculated fields like project bonus.
   - Adjusted designation levels based on project status and employee age.
   - Applied string formatting (e.g., added Mr./Mrs. based on gender).
   - Filtered data (e.g., cities containing the letter “o”).

4. Final Output

    Cleaned and enriched data ready for analysis.

Created a final aggregated report showing total project costs per employee.

Exported the final cleaned dataset for further use in BI tools or reporting.

  
