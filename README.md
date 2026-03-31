🇱🇻 Latvia Payment Landscape Analysis (2000–2024)
A Data Engineering & Fintech Impact Study

📌 Project Overview
This repository contains an end-to-end data analytics pipeline examining 25 years of Latvian Credit Transfer data. The project specifically highlights the structural shift in payment volumes following the regional adoption of the ISO 20022 messaging standard.

🛠️ The Tech Stack
Language: Python 3.10 

Libraries: Pandas (Data Manipulation), NumPy (Numerical Analysis) 

Environment: Google Colab 

BI Tool: Google Looker Studio (Financial Dashboarding) 

📈 Key Financial Insights
The ISO 20022 Spike: The analysis identified a massive 27.27% surge in transaction value in 2023, totaling over €543 Billion.

Exponential Growth: By 2024, the total credit transfer value surpassed €1 Trillion, representing a historical peak for the Latvian infrastructure.

Stability Period: Data confirms a period of market "plateau" between 2013 and 2021 before the recent technological modernization triggered growth.

📂 Repository Contents
Latvia_Payment_Analysis_Clean.ipynb: The Python script used for renaming columns, handling null values, and calculating growth percentages.

latvia_clean_final.csv: The refined dataset used for the final visualization.

Latvia_Payment_Analysis_2024.pdf: The final executive dashboard exported from Looker Studio.

⚙️ Data Pipeline Process
Extraction: Sourced raw payment data from the European Central Bank (ECB).

Transformation: Used Python to map complex system codes (e.g., B010) into human-readable financial metrics (Value_Millions).

Analysis: Calculated Year-over-Year (YoY) growth to isolate the impact of recent fintech regulations.

Visualization: Built a time-series dashboard to communicate findings to stakeholders.
