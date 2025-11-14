# AgroInsight-Q-A-System
An interactive Q&amp;A system that extracts actionable insights from agricultural data (1997–2014). It combines efficient EDA, a rule-based query engine, and a Gradio interface to answer questions on crop yields, rainfall, and production. Built in Jupyter Notebook with a modular, extensible pipeline.

# Overview

AgroInsight Q&A System transforms raw agricultural data into instant, insight-driven responses. The system performs data cleaning, merging, and exploratory analysis, followed by a rule-based natural language query engine exposed through a Gradio interface. Users can ask domain-specific questions related to crop yield, rainfall patterns, and production volumes.

# Features

Automated data preprocessing and merging (1997–2014 dataset).

Exploratory descriptive analysis across yield, rainfall, and production.

Rule-based Q&A engine for answering structured agricultural questions.

Interactive Gradio UI for seamless user interaction.

Modular workflow built entirely in Jupyter Notebook.

Tech Stack

Python

Pandas

Regular Expressions

Gradio

Jupyter Notebook

# How It Works

Load and preprocess the core agricultural datasets.

Execute EDA to understand distributions and patterns.

Pass user queries to the rule-based logic layer.

Generate validated responses based on structured conditions.

Serve the output through an interactive browser UI using Gradio.

# Example Queries

Which year had the highest rainfall?

Top yielding crop in 2008

What is the total production of wheat in 2010?

# Project Structure
AgroInsight/
│── data/
│── notebook.ipynb
│── app.py (optional if you export)
│── README.md

# How to Run

Install requirements:

pip install pandas gradio


Open the Jupyter Notebook and execute all cells.

Launch the Gradio app and start asking questions.

# Future Enhancements

Expand to ML-driven question interpretation

Add trend charts on demand

Deploy via Hugging Face or Streamlit Cloud
