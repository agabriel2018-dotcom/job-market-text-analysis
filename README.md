# job-market-text-analysis
Example workflow for LLM-assisted classification of job posting text in Python. Uses pandas and the OpenAI API to structure, categorize, and analyze unstructured job data, with environment-based secrets management and public-repo best practices.

# Job Posting Analysis Notebook (Sanitized)

This repository contains a sanitized Jupyter notebook that demonstrates an end-to-end workflow for:
- Loading and preprocessing job posting data
- Standardizing / extracting fields (e.g., location, salary)
- Using an LLM (OpenAI API) for structured extraction where needed
- Producing analysis-ready variables for downstream reporting

> Note: This repo is **sanitized** and does not include private datasets or credentials.

## Contents
- `analysis_sanitized.ipynb` — main notebook with setup + preprocessing + extraction logic

## Requirements
- Python 3.10+ (recommended)
- Jupyter Notebook / JupyterLab

Suggested packages (install what you need based on your environment):
- `pandas`, `numpy`
- `openai` (if running LLM-assisted steps)
- any other packages referenced in the notebook

## Setup

### 1) Create an environment (optional but recommended)
```bash
python -m venv .venv
source .venv/bin/activate  # macOS/Linux
# .venv\Scripts\activate   # Windows
pip install -U pip
