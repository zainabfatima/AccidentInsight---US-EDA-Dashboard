🚗 US Accidents EDA & Dashboard
A data-driven exploration and visualization project focused on traffic accidents in the United States using an extensive dataset. The goal is to derive meaningful insights, highlight patterns, and build an interactive dashboard for stakeholders.

📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on a dataset of over 2.8 million US accidents. It uses data visualization tools to uncover insights about:

Accident severity distribution

Geographic patterns

Weather-related impact

Temporal patterns (hour, day, month, etc.)

Road and visibility conditions

Interactive dashboard for exploration

🚀 Features
📊 EDA on 2.8M+ accident records across the US

🌦 Analysis of weather, visibility, temperature, and humidity

🕓 Time-based trend analysis

🗺 Geo-visualizations by state and city

📍 Map-based location clustering

📈 Seaborn, Plotly, and Matplotlib visualizations

📉 Severity prediction insights

🧭 Interactive dashboard using Plotly Dash

📁 Project Structure
graphql
Copy
Edit
us-accidents-eda/
├── README.md                           # Project overview and documentation
├── US ACCIDENTS EDA AND DASHBOARD.ipynb  # Full EDA and dashboard code
├── eda pdf.pdf                         # Exported notebook as PDF
└── video.mp4                           # Demo of interactive dashboard (optional)



🧠 How It Works
Loads large CSV of US accident data (from Kaggle US Accidents Dataset)

Performs:

Missing value analysis

Severity distribution

City/state-based counts

Weather and temperature impact

Time trends (hours, weekdays, months)

Visualizes using:

Seaborn and Matplotlib for static plots

Plotly for interactive graphs

Optionally deploys an interactive dashboard

📤 Input
US Accidents dataset (US_Accidents_Dec21_updated.csv)

Contains: severity, timestamp, location, weather, visibility, road details

📈 Output
Visual trends and correlation analysis

Heatmaps and bar plots of accidents by hour/state

Distribution of severity by weather and visibility

Interactive dashboard with user-driven exploration

📚 Example Insights
Most accidents happen between 6–9 AM and 3–6 PM

Visibility and humidity show correlation with accident severity

California, Florida, and Texas have the highest incident counts
