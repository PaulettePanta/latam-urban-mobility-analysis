# latam-urban-mobility-analysis
Python analysis exploring the correlation between urban traffic congestion (TomTom Index) and economic productivity (OECD Data) in Latin American cities (2024)

Urban Mobility & Economic Productivity in LATAM Cities
Project Role: Data Analyst at Latin American Development Bank

📌 Project Overview
This project investigates the relationship between urban mobility (congestion levels, travel times) and economic productivity (GDP per capita, unemployment) across major Latin American cities. The goal is to identify high-impact infrastructure investment opportunities.

📊 Datasets Used
TomTom Traffic Index: Real-time traffic congestion data (Jams delay, Traffic Index, Travel Times).

OECD Cities: Annual economic indicators (GDP per capita, Unemployment %, Population).

🛠️ Tech Stack
Python: Pandas & NumPy (Data Cleaning and Merging).

Visualization: Matplotlib & Seaborn.

Environment: Jupyter Notebook.

🚀 Key Objectives & Methodology
Data Harmonization: Standardized city and country names across two heterogeneous sources.

Feature Engineering: Extracted 2024 data and calculated aggregated traffic averages per city.

Exploratory Data Analysis (EDA): Identified cities with high congestion but low productivity (investment targets).

Correlation Analysis: Measured the strength of the relationship between travel delays and GDP.

💡 Business Questions Addressed

How is wealth (GDP per Capita) distributed among the analyzed LATAM cities? - Key Insight: The histogram shows a near-normal distribution with an average GDP per capita of $132,536 USD. It identifies that most cities fall within the middle-income range, with few extreme cases.

Histogram: GDP per Capita.png

Are there significant outliers in traffic congestion levels across the region? - Key Insight: While the regional average delay is 629.52 minutes, the boxplot highlights a specific outlier reaching nearly 3,000 minutes. This indicates a unique case of extreme congestion that deviates from the regional norm.

Boxplot: traffic congestion.png

What is the comparative scale between economic productivity and traffic delays per city? -Key Insight: This visualization allows for a direct comparison of scales. It highlights that cities like Montevideo and Mexico City lead in GDP per capita, while also visualizing the relative impact of traffic jams in each specific urban center.

Grouped Bar Chart: economic productivity and traffic delays.png

💡Analysis & Findings:

Distribution: Most cities analyzed maintain a stable economic output, suggesting a consistent market for infrastructure investment.

Congestion Anomalies: The presence of a high-value outlier in traffic delays suggests that specific localized factors are causing massive bottlenecks that require targeted policy interventions.

Regional Leaders: Montevideo stands out as the highest-performing city in terms of GDP, providing a benchmark for the rest of the LATAM dataset.
