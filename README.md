# CleanFlow: AI-Powered Data Analytics Agent

🎥 Demo Video: [https://youtu.be/eusLKrHddEo](https://youtu.be/eusLKrHddEo)

📂 GitHub Repository: [https://github.com/anmol-janmejay/CleanFlow
](https://github.com/anmol-janmejay?tab=repositories)
---

## Overview

CleanFlow is an AI-powered Data Analytics Agent that automates the complete analytics workflow from data ingestion and cleaning to SQL querying, visualization, profiling, and reporting.

Built using Python, Streamlit, SQLAlchemy, and Hugging Face APIs, the platform enables users to upload datasets, clean and transform data, generate insights using natural language, create interactive dashboards, and export analytical reports without writing extensive code.

The application is designed for Data Analysts, Business Analysts, students, and decision-makers who need rapid insights from structured datasets.

---

## Demo Video

Watch the project in action:

## 🎥 Demo Video

[![Watch Demo](imagesdemo-thumbnail.jpg)](https://youtu.be/eusLKrHddEo)

---

## Key Highlights

- Automated data quality assessment and cleaning workflows
- Natural Language to SQL query generation
- Interactive business intelligence dashboards
- Dataset versioning and snapshot management
- SQLite-powered analytics engine
- Automated profiling and reporting
- API and database data ingestion support
- Cloud deployment using Streamlit

---

## Business Problem

Data analysis often requires multiple disconnected tools for:

- Data ingestion
- Cleaning and preprocessing
- SQL analysis
- Dashboard creation
- Profiling and reporting

CleanFlow consolidates these tasks into a single AI-powered analytics platform, reducing manual effort and accelerating insight generation.

---

## Core Features

### Data Ingestion

- Upload CSV files
- Upload Excel files
- Load data from APIs
- Connect to databases

### Data Quality Assessment

Automatically detects:

- Missing values
- Duplicate records
- Data type inconsistencies
- Memory inefficiencies
- Potential outliers

### Automated Data Cleaning

Supports:

- Missing value handling
- Duplicate removal
- Date formatting
- Data type conversion
- Whitespace cleanup
- Outlier treatment

### Natural Language Analytics

Users can ask:

```text
What is the average salary?
Show top performing departments.
Which region generated highest revenue?
```

The system automatically generates and executes SQL queries.

### Interactive Visualization

Generate:

- Bar Charts
- Pie Charts
- Histograms
- Scatter Plots
- Trend Analysis Visualizations

using Plotly.

### Data Profiling

Generate automated profiling reports containing:

- Dataset overview
- Missing value analysis
- Correlation analysis
- Statistical summaries
- Distribution insights

### Dataset Versioning

- Snapshot management
- Hash-based dataset tracking
- Metadata storage
- Version history support

---

## System Architecture

```text
Dataset Upload
        │
        ▼
Data Quality Assessment
        │
        ▼
Automated Cleaning Engine
        │
        ▼
Version Snapshot Storage
        │
        ▼
SQLite Database
        │
 ┌──────┼──────┐
 ▼      ▼      ▼
AI SQL  Charts Profiling
Engine         Report
 │
 ▼
Business Insights
```

---

## Technology Stack

| Category | Technologies |
|----------|-------------|
| Language | Python |
| Frontend | Streamlit |
| Data Processing | Pandas, NumPy |
| Machine Learning Utilities | Scikit-Learn |
| Database | SQLite, SQLAlchemy |
| Visualization | Plotly |
| Profiling | ydata-profiling |
| AI Integration | Hugging Face Inference API |
| Deployment | Streamlit Community Cloud |
| Version Control | Git, GitHub |

---

## Skills Demonstrated

### Data Analytics

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Profiling
- Business Intelligence

### Data Engineering

- ETL Pipelines
- Data Transformation
- Data Validation
- SQLite Database Design
- SQL Querying

### AI & Automation

- Natural Language Query Processing
- AI-Assisted SQL Generation
- Hugging Face API Integration
- Workflow Automation

### Tools & Technologies

- Python
- Streamlit
- Pandas
- NumPy
- Plotly
- SQLAlchemy
- SQLite
- Git
- GitHub

---

## Project Workflow

```text
Upload Dataset
      ↓
Validate Dataset
      ↓
Clean & Transform Data
      ↓
Store in SQLite
      ↓
Generate Insights
      ↓
Run SQL Queries
      ↓
Create Visualizations
      ↓
Generate Profiling Reports
      ↓
Export Results
```

---

## Sample Natural Language Queries

```text
Count rows in the dataset
```

```text
What is the average salary?
```

```text
Which department has the highest salary?
```

```text
Show revenue by city
```

```text
Find top performing employees
```

---

## Example SQL Query

```sql
SELECT department,
AVG(salary) AS average_salary
FROM data_table
GROUP BY department
ORDER BY average_salary DESC;
```

---

## Results & Impact

- Automated repetitive data preparation tasks
- Reduced manual cleaning effort through workflow automation
- Enabled SQL analysis using natural language queries
- Accelerated exploratory analysis through interactive dashboards
- Simplified report generation using automated profiling

---

## Installation

### Clone Repository

```bash
git clone https://github.com/anmol-janmejay/CleanFlow.git
cd CleanFlow
```

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Environment

Windows:

```bash
.venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
streamlit run app.py
```

---

## Future Improvements

- LLM-powered insight explanations
- Predictive analytics modules
- Dashboard sharing capabilities
- Multi-user authentication
- Cloud database integration

---

## Resume Description

Developed and deployed an AI-powered Data Analytics Agent that automated ETL workflows, dataset cleaning, SQL-based insight generation, visualization, profiling, and version-controlled data management using Python, Streamlit, SQLite, and Hugging Face APIs.

---

## Author

### Anmol Janmejay

Aspiring Data Analyst | Business Intelligence Enthusiast | AI & Data Analytics

LinkedIn: [https://www.linkedin.com/in/anmol-janmejay/](https://www.linkedin.com/in/anmol-janmejayyy/)

GitHub: https://github.com/anmol-janmejay
