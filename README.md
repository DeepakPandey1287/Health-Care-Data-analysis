📁 Overview
This project involves a comprehensive analysis of a hospital database using SQL and Python (Jupyter Notebook). The primary objective is to extract meaningful insights from healthcare data that includes patients, encounters, procedures, and payers.

📊 Data Description
The analysis is based on a relational database consisting of the following main tables:

patients: Contains demographic details of patients including gender, city, and birthdate.

encounters: Medical encounter data like encounter type, cost, and duration.

procedures: Medical procedures with associated base costs.

payers: Entities responsible for claim payments.

🧮 Key SQL Analyses
The data.sql file includes a rich set of queries, such as:

📅 Time-Based Insights
Number of encounters per year.

Average yearly claim cost.

Cost categorization of encounters (Low, Medium, High).

Duration analysis (Over/Under 24 hours).

🧍‍♂️ Patient Demographics
Gender distribution.

City-wise patient counts.

Age group classification: Young Adult, Adult, Senior.

Patients with more than 3 encounters.

💰 Cost & Claims
Average claim cost across all encounters.

Top 5 most expensive procedures.

Procedure cost summaries by city and patient.

🔄 Procedure & Encounter Stats
Total and average costs.

Top procedures by frequency and cost.

Encounter types and their proportions.

Zero-payer encounter analysis.

🤝 Payer Analysis
Total encounters per payer.

Average claim cost per payer.

 Healthcare Data Analysis Project using python.
 
🔍 Key Questions Explored
👥 What is the distribution of patients by gender, age group, and race?

🏥 What are the most common reasons for medical encounters?

💉 Which procedures are most frequently performed and what do they cost?

💳 Which insurance payers are most commonly used?

📅 How do encounter types vary over time (inpatient, outpatient, emergency)?

📈 What trends can be observed in procedure volume and payer distribution?

📊 Planned Visualizations & Insights
Insight Type	Visualization
Patient demographic breakdown	Pie chart / Bar chart
Monthly encounters trend	Line chart
Top 10 procedures by volume	Horizontal bar chart
Cost distribution per procedure	Box plot or histogram
Encounter type vs age	Stacked bar chart or heatmap
Payer usage breakdown	Donut or bar chart

🛠 Tools & Libraries
Python: Data cleaning and exploration

Pandas: Data manipulation

Seaborn / Matplotlib: Visualizations
