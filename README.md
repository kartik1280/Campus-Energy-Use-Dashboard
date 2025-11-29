# Campus Energy-Use Dashboard

**Course:** Programming for Problem Solving using Python  
**Assignment:** End-to-End Energy Consumption Analysis and Visualization  
**Student:** Kartik Sharma 

---

## Project Overview

This project analyzes electricity consumption data from multiple campus buildings to identify energy usage patterns and provide actionable insights to the facilities team. It involves reading raw meter data CSV files, performing data cleaning and validation, aggregating usage statistics, modeling buildings and meter readings using object-oriented programming, and generating a multi-chart dashboard visualization along with summary reports.

---

## Folder Structure

campus-energy-dashboard
├── main.py # Main Python script implementing all tasks
├── data/ # Contains raw CSV files (one per building)
│ ├── building_a_jan.csv
│ ├── building_b_jan.csv
├── output/ # Generated outputs (created by script)
│ ├── cleaned_energy_data.csv
│ ├── building_summary.csv
│ ├── summary.txt
│ └── dashboard.png
└── README.md # This documentation file

---

## Getting Started

### Prerequisites

- Python 3.x
- Libraries: pandas, matplotlib

Install required libraries with:
pip install pandas matplotlib

### Running the Program

From the root directory (where `main.py` exists), run: python main.py


This will:

- Load and validate CSV data from the `data/` folder
- Perform daily and weekly aggregations
- Generate OOP-based building reports
- Create a multi-chart energy dashboard `output/dashboard.png`
- Export cleaned data and summary CSVs to `output/`
- Write an executive summary text to `output/summary.txt`

---

## Project Features

- Automatic ingestion and cleaning of multiple building CSV files
- Time-series aggregation for daily and weekly electricity totals
- Building-wise energy consumption summaries using custom classes
- Multi-chart visualization with trend lines, bar charts, and scatter plots
- Export of clean data, summary stats, visual dashboard, and text report
- Robust handling of missing or corrupt data files

---

## Sample Data Format

CSV files in `/data/` should have at least these columns:

- `timestamp` (e.g., 2025-01-01 00:00)
- `kwh` (electricity consumed)
- Optional: `building` name; if missing, inferred from filename

---

## Insights and Usage

The generated dashboard and reports help facility managers identify:

- Which buildings consume the most energy
- Peak hours and daily/weekly usage trends
- Opportunities for targeted energy-saving interventions

---

## License

This project is submitted for academic coursework purposes. All code is original and authored by Kartik Sharma.

## License
<img width="715" height="297" alt="{2101C649-BC83-46FD-91DB-B55283565954}" src="https://github.com/user-attachments/assets/a50f8554-35ae-4488-8ad7-f6cb67f0bbec" />

<img width="198" height="228" alt="{366A66F2-953D-4D3C-9D1B-15C7439A3AED}" src="https://github.com/user-attachments/assets/c11b1c7f-5500-4492-b4a5-9b43ca5fa951" />

<img width="369" height="148" alt="{35E7DF74-55BC-4DCD-BE33-3140C2E92B3D}" src="https://github.com/user-attachments/assets/a0923906-3b33-43ae-bf3c-42cf2287a094" />

<img width="793" height="397" alt="{6EE331FD-EB63-402F-8434-7D01CEF8026B}" src="https://github.com/user-attachments/assets/a051f051-6d38-487b-bc4c-dcc4c56d6da2" />

<img width="792" height="392" alt="{D1BBEFB5-F168-4F29-A6B1-9F6821428A50}" src="https://github.com/user-attachments/assets/7c229342-197e-4d2f-8b56-9085a5d461ca" />

<img width="790" height="225" alt="{B84B864F-F864-4281-8AFA-8C50DBDC9143}" src="https://github.com/user-attachments/assets/16ddaebb-dacf-4a54-b3ba-b0c5889ff9a5" />

