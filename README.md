🦠 COVID-19 Global Data Tracker
📌 Project Description
This project is designed to build a data analysis and reporting notebook (or app) that monitors global COVID-19 trends. It will analyze cases, deaths, recoveries, and vaccinations across countries and over time.

You will:

Work with real-world datasets.

Clean and prepare data.

Perform exploratory data analysis (EDA).

Visualize patterns and trends.

Communicate insights through narrative storytelling.

The final output will be a polished Jupyter Notebook (or PDF report) suitable for presentation or publication.

🎯 Project Objectives
✅ Import and clean COVID-19 global data.

✅ Analyze time trends (cases, deaths, vaccinations).

✅ Compare key metrics across countries/regions.

✅ Visualize trends using charts and maps.

✅ Communicate findings with clear visuals and written insights.

🗂️ Project Segments (Step-by-Step Guide)
1️⃣ Data Collection
Goal: Obtain a reliable COVID-19 dataset.

Recommended Source:

Our World in Data (OWID) COVID-19 Dataset
(CSV format: owid-covid-data.csv)

Action:

Download owid-covid-data.csv.

Save in your working folder.

2️⃣ Data Loading & Exploration
Goal: Load and inspect the dataset.

Tasks:

Load using pandas.read_csv().

Inspect structure: df.columns, df.head().

Identify missing data: df.isnull().sum().

Key Columns:

date, location, total_cases, total_deaths, new_cases, total_vaccinations, etc.

Tool: pandas

3️⃣ Data Cleaning
Goal: Prepare data for meaningful analysis.

Tasks:

Filter countries (e.g., Kenya, USA, India).

Drop rows with missing dates/critical metrics.

Convert date column using pd.to_datetime().

Handle nulls with fillna() or interpolate().

Tool: pandas

4️⃣ Exploratory Data Analysis (EDA)
Goal: Discover trends and generate statistics.

Tasks:

Plot total and daily cases over time.

Compare death rates: total_deaths / total_cases.

Highlight differences between countries.

Visualizations:

Line charts (cases, deaths).

Bar charts (top countries).

Optional: Heatmaps (correlation).

Tools: matplotlib, seaborn

5️⃣ Visualizing Vaccination Progress
Goal: Examine global vaccination rollouts.

Tasks:

Plot cumulative vaccinations over time.

Compare percentage vaccinated across countries.

Charts:

Line charts

Optional: Pie charts (vaccinated vs unvaccinated)

Tools: matplotlib, seaborn

6️⃣ (Optional) Build a Choropleth Map
Goal: Show country-level data on a world map.

Tools:

plotly.express (easy)

geopandas (advanced)

Tasks:

Create a dataframe with iso_code, total_cases, or vaccination_rate.

Plot a choropleth for visual distribution.

7️⃣ Insights & Reporting
Goal: Summarize and communicate key findings.

Tasks:

Write 3–5 insightful observations.

Note trends, anomalies, outliers.

Add markdown cells for clear explanations.

Deliverables:

✅ Jupyter Notebook with:

Code

Clean visualizations

Narrative analysis

📤 Optional: Export to PDF or PowerPoint.

🛠️ Recommended Tools
Jupyter Notebook / VS Code with Jupyter

pandas

matplotlib & seaborn

Optional: plotly, geopandas
