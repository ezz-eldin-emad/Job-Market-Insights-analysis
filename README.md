# Job Market Insights Analysis

🚀 **Live Demo:** [Job Market Insights Analysis](https://job-market-insights-analysis.streamlit.app)

---

## 📑 **Project Overview**

This project provides comprehensive insights into the job markets of **Egypt** and **Saudi Arabia** using data analysis and visualization tools. It allows users to explore various aspects of the job market, including job distribution, top employers, industry trends, and experience requirements. Built with **Streamlit**, **Pandas**, **Plotly** and **Seaborn**, this application offers an interactive, user-friendly experience for professionals, job seekers, and data enthusiasts.

| Item | Value |
| --- | --- |
| Source | Bayt.com job listings (scraped with `requests` + BeautifulSoup) |
| Listings collected | 481 result pages — 4,009 Egypt + 5,505 Saudi Arabia after cleaning |
| Storage | SQLite database + processed CSV tables |
| Analyses | 12 visualizations per market, plus a cross-market comparison |
| Interface | Streamlit multipage app with cached per-page views |

## 🎯 **Key Features**

* **Data Cleaning and Transformation:** In-depth preprocessing of job listings for accurate analysis.
* **Interactive Visualizations:** 12 key plots for each market, including:

  * Job Distribution by City
  * Jobs by Company
  * Top Job Titles
  * Work Type Distribution
  * Job Levels and Experience
* **Market Comparison:** Side-by-side analysis of Egypt and Saudi Arabia job markets.
* **Team Profiles:** Meet the project contributors.

## 🚀 **Getting Started**

### Prerequisites

* Python 3.10+
* Streamlit
* Pandas, Plotly, Seaborn
* `requests` + BeautifulSoup (for re-scraping, optional)

### Installation

Clone the repository:

```bash
git clone https://github.com/ezz-eldin-emad/Job-Market-Insights-analysis.git
cd Job-Market-Insights-analysis
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the app locally:

```bash
streamlit run streamlit_app.py
```

## 🛠️ **Modules and Functions**

### **Data Processing (scripts/preprocessing.py)**

* Data cleaning, feature engineering, and transformation.

### **Analysis Functions (scripts/analysis.py)**

* Plotting and data exploration functions.

## 📊 **Visualizations Included**

* Job Distribution by City
* Jobs by Company
* Top Job Titles
* Jobs by Work Type
* Jobs by Gender
* Jobs by Job Level
* Job Trend Over Time
* Job Postings by Industry
* Job Type Distribution
* Experience Requirements
* Heatmap by City and Job Level
* Top Job Titles Word Cloud

## 📢 **Contributors**

* **Ezz Al-Din Emad** - Data Scientist
  - `Data Cleaning`
* **Abdallah Mohamed** - Data Scientist
  - `Data Cleaning`
* **Ali Ahmed** - Data Scientist
  - `Data Analysis`
* **Adel Maher** - Data Analyst
  - `Data Analysis`



## 🌐 **Links**

* **Live App:** [Job Market Insights Analysis](https://job-market-insights-analysis.streamlit.app)
* **Team Portfolio:** [DataMentes Team](https://team-portfolio.streamlit.app)
* **GitHub Repository:** [https://github.com/ezz-eldin-emad/Job-Market-Insights-analysis](https://github.com/ezz-eldin-emad/Job-Market-Insights-analysis)

