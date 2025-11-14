# AgriInsightQnA — Intelligent Crop Production & Rainfall Query System

An interactive, data-driven Q&A system built to deliver fast, actionable insights from agricultural datasets (1997–2014). The project integrates a cleaned and merged analytical dataset, exploratory visualizations, and a rule-based natural-language query engine deployed through a Gradio interface. Designed in Jupyter Notebook with a modular pipeline for scalability.

# 📌 Key Features

End-to-end pipeline: cleaning → merging → visualization → Q&A system

Rule-based natural language query engine

Insights on crop yield, production, rainfall patterns, and district-level metrics

Gradio UI for real-time conversational analytics

Reproducible workflow suitable for academic and industry analytics projects

# 📂 Project Roadmap

This workflow ensures a clean, traceable, and production-ready analytical pipeline.

Full Project Roadmap — Crop Production vs Rainfall
Step	Phase	Objective	Tool / Output
Step 1	Data Loading	Upload and preview both datasets (crop_production_cleaned.csv, rainfall_data_cleaned.csv)	Python (Pandas)
Step 2	Pre-Merge EDA	Inspect structure, datatypes, missing values, and naming inconsistencies	Python
Step 3	Data Cleaning & Merge Preparation	Standardize column names (state, year), resolve inconsistent spellings (e.g., Andaman & Nicobar → Andaman and Nicobar Islands), align years & states, and merge datasets	Python
Step 4	Visual EDA (Post-Merge)	Generate charts such as rainfall trends, yield distribution, district-wise production using merged_crop_rainfall.csv	Tableau
Step 5	Insight Generation / Modeling (Optional)	Perform correlation analysis, regression, or rainfall-based yield prediction	Python
Step 6	Build Q&A System	Develop rule-based logic to answer questions about crop performance and rainfall	Python
Step 7	Deploy Interactive Interface	Integrate with Gradio to answer user queries in natural language	Gradio

# 🛠️ Tech Stack

Python (Pandas, NumPy, Matplotlib)

Gradio (Interactive Q&A interface)

Tableau (EDA dashboards)

Jupyter Notebook

GitHub (Version control)

# 🚀 How It Works
1. Upload and Preview Data

Load both datasets and verify structure, null values, and data types.

2. Clean and Standardize

Fix inconsistencies in state names, unify year formats, and normalize categorical fields.

3. Merge Data

Combine crop production and rainfall datasets using a state-year key.

4. Conduct Visual EDA

Create Tableau charts to identify patterns such as:

rainfall trends

production efficiency

district-wise output

yield distribution

5. Build Rule-Based Q&A Engine

Logic handles queries such as:

Which year had the highest rainfall?

Top yielding crops in 2008?

Which district produced the most rice in 2012?

6. Deploy Gradio App

A user can type natural-language queries and get instant insights.

# ▶️ Example Queries

“Which year had the highest average rainfall?”

“Show top yielding crops in 2008.”

“Which district had highest production overall?”

“What is the rainfall trend over the years?”

# 📁 Repository Structure
├── data/
│   ├── crop_production_cleaned.csv
│   ├── rainfall_data_cleaned.csv
│   └── merged_crop_rainfall.csv
├── notebooks/
│   └── crop_rainfall_qna.ipynb
├── app/
│   └── gradio_interface.py
├── README.md
└── visuals/
    └── tableau_dashboards/

# 📈 Future Enhancements

ML model for rainfall-based yield prediction

Deployment on HuggingFace Spaces

API endpoint for programmatic access

# 📜 License

This project is released under the MIT License.
