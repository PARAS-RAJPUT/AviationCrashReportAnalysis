# AviationCrashReportAnalysis

✈️ Aviation Accident Data Analysis (2004–2023)

This project presents a detailed exploratory and statistical analysis of aviation accidents in the United States between 2004 and 2023 using data from the National Transportation Safety Board (NTSB). The analysis is structured around five key objectives and implemented in a Jupyter Notebook.
📁 Dataset

    Source: NTSB Aviation Accident Database

    Format: Excel (.xlsx)

    Timeframe: 2004–2023

    Total Records: ~85,000+ accident entries

    Features: Date, Aircraft Make, Flight Regulation, Purpose of Flight, Severity Level, State, etc.

📌 Objectives

    Analyze yearly trends in aviation accidents over time

    Perform geospatial profiling of accident risk by U.S. states

    Investigate aircraft type and severity relationships

    Assess impact of flight regulation and flight purpose on outcomes

    Identify key factors correlated with fatal injury outcomes

🧪 Project Workflow

    Data Cleaning: Removed nulls, formatted dates, standardized text

    Exploratory Data Analysis (EDA): Plots, heatmaps, distributions

    Statistical Analysis: Correlation, chi-square tests

    Visualizations: Seaborn, Matplotlib bar charts, line plots, stacked graphs

    Target Variable: Created binary classification for fatal vs non-fatal accidents

📊 Key Findings

    Most accidents occurred under Part 91 (general aviation)

    Fatalities were more common in personal or instructional flights

    Certain aircraft makes (e.g., Cessna, Piper) were more frequent in incidents, but not necessarily more fatal

    Some states (e.g., California, Texas) had higher accident volumes due to air traffic density

🧰 Tech Stack

    Python 3.10+

    Jupyter Notebook (.ipynb)

    pandas, numpy, seaborn, matplotlib

    scipy (for statistical tests)


📈 Sample Visuals

    Year-wise accident trends (line chart)

    Fatal injury distribution (histogram)

    Top states with highest incidents (bar chart)

    Severity breakdown by aircraft category (stacked chart)

📚 Future Scope

    Build a predictive model (e.g., decision tree classifier)

    Create a Streamlit or Dash dashboard

    Geospatial US map visualization using GeoPandas or Plotly

