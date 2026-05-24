# CleanFlow: AI-Powered Data Analytics Agent

CleanFlow is an end-to-end data analytics application built with Python and Streamlit. It helps users upload datasets, clean and transform data, store it in a local database, ask natural-language questions, generate SQL-based insights, create interactive visualizations, and export profiling reports.

## Repository Description

AI-powered Streamlit data analytics agent for automated data cleaning, SQL querying, visualization, profiling, and dataset versioning.

## Overview

Data analysis often requires repetitive steps such as uploading files, checking data quality, cleaning missing values, removing duplicates, writing SQL queries, building charts, and generating reports. CleanFlow combines these steps into one interactive workflow.

The app is designed for analysts, students, and data enthusiasts who want a simple tool to explore datasets quickly without manually writing every cleaning or analysis step.

## Key Features

- Upload CSV and XLSX datasets.
- Load data from APIs or database connections.
- Automatically assess missing values, duplicates, type issues, and memory usage.
- Clean missing values, duplicate rows, whitespace, dates, data types, and outliers.
- Save cleaned dataset snapshots with metadata and hashes.
- Store cleaned data in a SQLite database using SQLAlchemy.
- Ask natural-language questions and generate SQL queries.
- Run custom SQL queries directly.
- Create interactive Plotly visualizations.
- Generate data profiling reports using ydata-profiling.
- Export cleaned data and HTML reports.
- Deploy easily on Streamlit Community Cloud.

## Tech Stack

| Category | Technologies |
| --- | --- |
| Programming Language | Python |
| Web Framework | Streamlit |
| Data Processing | Pandas, NumPy |
| Machine Learning Utility | scikit-learn |
| Database | SQLite, SQLAlchemy |
| Visualization | Plotly |
| Profiling | ydata-profiling |
| AI Integration | Hugging Face Inference API |
| Deployment | Streamlit Community Cloud |
| Version Control | Git, GitHub |

## Project Workflow

```text
Upload Dataset
-> Clean and Validate Data
-> Save Version Snapshot
-> Store Data in SQLite
-> Ask Natural-Language Questions
-> Run SQL Queries
-> Generate Visualizations
-> Create Profiling Report
-> Export Results
```

## Project Structure

```text
Data-Analytics-AI-Agent/
├── app.py
├── modules/
│   ├── ai_services.py
│   ├── data_cleaning.py
│   ├── data_ingestion.py
│   ├── database_manager.py
│   ├── profiling.py
│   ├── version_control.py
│   └── visualization.py
├── utils/
│   └── helpers.py
├── .streamlit/
│   ├── config.toml
│   └── secrets.toml.example
├── DEPLOYMENT.md
├── requirements.txt
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/cleanflow-ai-data-analytics-agent.git
cd cleanflow-ai-data-analytics-agent
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the virtual environment on Windows:

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
python -m pip install -r requirements.txt
```

If `pkg_resources` is missing, run:

```bash
python -m pip install "setuptools>=68,<81" --force-reinstall
```

## Run Locally

```bash
python -m streamlit run app.py
```

Then open:

```text
http://localhost:8501
```

## Optional AI Setup

The app works without an API key by using rule-based fallbacks. To enable Hugging Face-powered SQL and insight generation, create this file:

```text
.streamlit/secrets.toml
```

Add:

```toml
HF_API_KEY = "your_huggingface_token_here"
```

## Sample Questions

Use these prompts in the Storage & Queries section:

```text
count rows
```

```text
what is the average salary
```

```text
what is the maximum salary
```

Example custom SQL:

```sql
SELECT department, AVG(salary) AS avg_salary
FROM data_table
GROUP BY department
ORDER BY avg_salary DESC;
```

## Visualization Examples

Use these prompts in the Visualization section:

```text
show salary by department
```

```text
show monthly_sales by city
```

```text
show distribution of performance_score
```

```text
show relationship between training_hours and performance_score
```

## Deployment

This project can be deployed on Streamlit Community Cloud.

1. Push the repository to GitHub.
2. Go to Streamlit Community Cloud.
3. Create a new app.
4. Select this repository.
5. Set the main file path to:

```text
app.py
```

6. Add optional secrets such as `HF_API_KEY`.
7. Deploy the app.

For more details, see [DEPLOYMENT.md](DEPLOYMENT.md).

## Skills Demonstrated

- Python programming
- Data cleaning and preprocessing
- ETL workflow automation
- Exploratory data analysis
- SQL querying
- Natural-language query handling
- Interactive dashboard development
- Data visualization
- Data profiling and reporting
- Streamlit app development
- Cloud deployment
- Git and GitHub project management

## Resume Highlight

Built and deployed CleanFlow, an AI-powered Streamlit data analytics agent that automates data ingestion, ETL cleaning, SQLite storage, natural-language SQL querying, Plotly visualization, profiling report generation, and version-controlled dataset snapshots.

## Author

Anmol Janmejay  
Aspiring Data Analyst | AI-ML Engineer



