# 📊 Stack Overflow Developer Survey — Technology Trends & Insights

> **IBM Data Analyst Capstone Project**
> An end-to-end analysis of the Stack Overflow Developer Survey exploring global technology adoption, salary benchmarks, and emerging skill demand.

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Key Findings](#-key-findings)
- [Tech Stack](#️-tech-stack)
- [Data Sources](#-data-sources)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Dashboard](#-dashboard)
- [Author](#-author)

---

## 🎯 Overview

This project analyzes the Stack Overflow Developer Survey to uncover trends in:

- 🧑‍💻 **Programming languages** — current usage and future demand
- 🗄️ **Databases** — leaders, challengers, and emerging tools
- ☁️ **Cloud platforms & web frameworks** — adoption patterns
- 💰 **Salary benchmarks** by language
- 👥 **Developer demographics** — age, education, geography

**Target audience:** HR professionals, hiring managers, technology strategists, and analytics stakeholders seeking data-driven insight on workforce and technology planning.

---

## ✨ Key Findings

| 🏆 Finding | Insight |
|---|---|
| **JavaScript reigns** | Most widely used language (14,943 respondents) and most desired for the year ahead |
| **PostgreSQL dominates** | Top database in both current (11,514) and desired (12,193) use |
| **AWS leads the cloud** | Far ahead of Azure and Google Cloud in current adoption |
| **C tops job postings** | 13,498 listings — nearly 5× Java (2,609); Python ranks 3rd (1,173) |
| **Swift earns most** | $130,801 average annual salary, followed by Python ($114,383) |
| **Go & Rust on the rise** | Both enter the desired top 10 for next year |
| **Young workforce** | 41.3% of developers are 25–34; most hold a Bachelor's degree |

---

## 🛠️ Tech Stack

- **Python** — `pandas`, `numpy`, `matplotlib`, `seaborn`, `requests`, `BeautifulSoup`
- **Jupyter Notebook** — exploratory analysis and data wrangling
- **Google Looker Studio** — interactive dashboards
- **Excel** — supplementary data formatting

---

## 📂 Data Sources

| File | Description |
|---|---|
| `survey-data.csv.zip` | Raw Stack Overflow Developer Survey data |
| `survey_data_updated.csv.zip` | Cleaned and processed survey data used in all analyses |
| `popular-languages.csv` | Average salary by language (web-scraped) |
| `job-postings-by-technology.xlsx` | Job postings count per technology (via Jobs API) |

> ⚠️ **Unzip the `.csv.zip` files before running the notebooks.**
> They were compressed to fit GitHub's 25 MB upload limit.

---

## 📁 Project Structure

```
.
├── Reports/
│   ├── Data Analyst Capstone Project Report.pdf
│   └── Data Analyst Capstone Project Report.pptx
│
├── Notebooks/
│   ├── Jobs_API.ipynb                       # Jobs API data collection
│   ├── Lab 1  — Review Of Accessing APIs
│   ├── Lab 10 — Normalizing Data
│   ├── Lab 11 — Data Wrangling
│   ├── Lab 12 — Exploratory Data Analysis
│   ├── Lab 13 — Distribution Analysis
│   ├── Lab 14 — Finding Outliers
│   ├── Lab 15 — Finding Correlation
│   ├── Lab 16 — Data Visualization
│   ├── Lab 17 — Histograms
│   └── Lab 18 — Box Plots
│
└── Data/
    ├── DatabaseHaveWorkedWith_top10.csv
    ├── DatabaseWantToWorkWith_top10.csv
    ├── survey-data.csv.zip
    └── survey_data_updated.csv.zip
```

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook or JupyterLab

### Setup

```bash
# 1. Clone this repository
git clone https://github.com/ihoney93/stack-overflow-developer-survey-analysis-capstone-project.git
cd stack-overflow-developer-survey-analysis-capstone-project

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn requests beautifulsoup4 jupyter

# 3. Unzip the data files
unzip survey-data.csv.zip
unzip survey_data_updated.csv.zip

# 4. Launch Jupyter
jupyter notebook
```

---

## 📊 Dashboard

Three interactive Looker Studio dashboard tabs accompany this analysis:

1. **Current Technology Usage** — what developers use today
2. **Future Technology Trends** — what they want next year
3. **Demographics** — age, education, and country breakdown

> 📌 *Add your Looker Studio link here once published.*

---

## 👤 Author

**Hanieh Asghari Oskoei** (Hannah)
🎓 IBM Data Analyst Capstone Project — May 2026
🌐 GitHub: [@ihoney93](https://github.com/ihoney93)

---

## 🙏 Acknowledgments

- **Stack Overflow** — for publishing the annual Developer Survey
- **IBM Skills Network & Coursera** — for the Data Analyst Professional Certificate program

---

⭐ *If you found this project useful or interesting, please consider giving it a star!*
