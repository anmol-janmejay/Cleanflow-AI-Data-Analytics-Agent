# Deployment Guide

This project is a Streamlit application. The fastest resume-ready deployment path is Streamlit Community Cloud.

## Deploy on Streamlit Community Cloud

1. Push this repository to GitHub.
2. Go to https://share.streamlit.io and choose **New app**.
3. Select the repository, branch, and set the main file path to `app.py`.
4. Keep the Python dependency file as `requirements.txt`.
5. Optional: add a Hugging Face token in **Advanced settings -> Secrets**:

```toml
HF_API_KEY = "hf_your_token_here"
```

6. Deploy the app.

The app still works without `HF_API_KEY` using rule-based SQL, visualization, and insight fallbacks.

## Local Run

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Resume Summary

**CleanFlow - AI Data Analytics Agent**: Built and deployed a Streamlit analytics application that ingests CSV/XLSX/API/database data, performs automated cleaning, stores datasets in SQLite, converts natural-language questions into SQL, generates Plotly visualizations, exports cleaned data, and produces profiling reports.

Suggested resume bullets:

- Built a modular Python and Streamlit data analytics agent with ingestion, ETL cleaning, SQL querying, visualization, profiling, and version snapshot workflows.
- Integrated Hugging Face-powered natural-language SQL generation with rule-based fallbacks so the app remains usable without paid API keys.
- Added deployment-ready Streamlit configuration and cloud secret support for public demos.
