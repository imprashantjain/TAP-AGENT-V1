# 🚀 TAP Research Agent

An AI-powered research tool designed to automate **CSR prospect screening** and **deep research** for organizations like **The Apprentice Project (TAP)**.

---

## 📌 Overview

TAP Research Agent helps teams identify and analyze companies for **CSR partnerships** with a focus on **education initiatives**.  
It reduces manual effort by automating research, scoring, and report generation.

---

## ✨ Features

- 🔍 **Prospect Screening**
  - Identify CSR-active companies
  - Filter based on education focus

- 🧠 **Deep Research**
  - Collect verified company data
  - Analyze CSR activities

- 📊 **Scoring System**
  - Rule-based scoring using YAML config
  - Fully customizable

- 📄 **Automated Reports**
  - Structured research summaries
  - Export to DOCX format

- 🌐 **Web Scraping**
  - Extract real-time data from web sources
  - Reduce manual research effort

- 🎯 **Streamlit UI**
  - Simple and interactive interface

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **BeautifulSoup / Requests**
- **YAML**
- **Custom Scoring Engine**

---

## 📁 Project Structure
working_prashant/
│── app.py
│── scraper.py
│── parser.py
│── scorer.py
│── reporter.py
│── docx_reporter.py
│── config.yaml
│── utils.py
│── requirements.txt
│── README.md
│── .gitignore
│
├── data/
│   └── (scraped / temp data)
│
├── reports/
│   └── (generated reports .docx)
│
├── assets/
│   └── (images / UI files if any)
│
└── .streamlit/
    └── config.toml
---



---

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone <your-repo-link>

# Navigate to project folder
cd working_prashant

# Install dependencies
pip install -r requirements.txt
