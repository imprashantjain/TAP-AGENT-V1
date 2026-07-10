#  TAP Research Agent

An AI-powered research tool designed to automate **CSR prospect screening** and **deep research** for organizations like The Apprentice Project (TAP).

---

##  Features

-  Prospect Screening (CSR-focused companies)
- Deep Research Reports
- Intelligent Scoring System (configurable via YAML)
-  Automated Report Generation
-  Web Scraping for Verified Data
-  Streamlit UI for interaction

---

##  Tech Stack

- Python
- Streamlit
- Web Scraping (Requests / BeautifulSoup)
- YAML Configuration
- Custom Scoring Engine

---

##  Project Structure
working_prashant/
│── app.py # Main Streamlit app
│── scraper.py # Data collection
│── parser.py # Data parsing
│── scorer.py # Scoring logic
│── reporter.py # Report generation
│── docx_reporter.py # DOCX export
│── config.yaml # Configurable rules
│── utils.py # Helper functions
│── requirements.txt # Dependencies
│── .gitignore # Ignored files
 

## git add README.md


```bash
git clone <your-repo-link>
cd working_prashant
pip install -r requirements.txt
