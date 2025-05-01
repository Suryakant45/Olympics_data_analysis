# olympics-data-analysis

Project Overview

This project is an interactive Streamlit web application that performs insightful analysis on historical Olympic data. It allows users to explore trends, medal tallies, country-specific performance, and athlete-wise statistics across different editions of the Summer Olympics. The app is ideal for data visualization, storytelling, and dashboard creation using Python.

How It Works

Data Loading & Preprocessing:

preprocessor.py loads and merges athlete and NOC datasets.

Filters data to include only Summer Olympics.

Creates a clean, ready-to-use dataframe.

Streamlit Interface (app.py):

Uses a sidebar menu to let users choose from:

Medal Tally

Overall Analysis

Country-wise Analysis

Athlete-wise Analysis

Each section uses functions from helper.py to compute and display data.

Visualizations:

matplotlib and seaborn are used to generate plots like line graphs, bar charts, and heatmaps.

Results are rendered directly in the Streamlit web interface.

Deployment Ready:

Comes with Procfile and setup.sh to easily deploy on platforms like Heroku or Streamlit Cloud.

✅ Strengths
Modular Design: Separate scripts for preprocessing, analysis logic, and frontend make it easy to manage and extend.

Interactive: Real-time filtering and chart updates through Streamlit UI.

Deployable: Includes deployment scripts for hosting the app online.

Educational: Ideal for learning pandas, visualization, and web app development.

Reusable: Can be adapted for similar datasets or sports analytics projects.

streamlit run app.py