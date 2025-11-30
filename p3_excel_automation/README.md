# Excel Automation Using Python and Openpyxl
## Project Overview
This project automates the monthly sales reporting workflow by merging multiple Excel files, cleaning the data, generating summary insights, and producing a consolidated, ready-to-share Excel report. It eliminates 2–3 hours of manual work every month.

## Folder Structure
project<br>
│── input_files<br>
│── excel_automation_python.py<br>
│── README.md

## Features
- Automatically reads and merges 10–20 Excel files
- Removes duplicates and handles missing values
- Adds calculated fields (e.g., Total Sales = Units × Price)
- Generates pivot-table style summaries
- Saves final polished report as Automated_Sales_Report.xlsx
- Ensures consistent formatting using OpenPyXL

## Technologies Used
- Python
- Pandas
- Openpyxl
- Matplotlib

## How to Run the Project
1. Place all monthly Excel files into the input_files/ folder.
2. Install dependencies:
>pip install pandas openpyxl matplotlib
3. Run the script:
>python excel_automation_python.py
4. Open the generated file:
>Automated_Sales_Report.xlsx

## Sample Output
To be added

## Future Improvements
- Add Automatic Chart generation
- Add GUI using Tkinter
- Schedule monthly automation using cron
- Add email auto-delivery of the report
- Convert output to PDF
- Add dashboard using Streamlit

## About the Client Problem
The client spends hours every month merging files, verifying totals, and preparing sales summaries. The automation reduces manual work, improves accuracy, and produces a clean, standardized report in seconds.
