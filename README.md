"# web-scraping-playwright" 

# 💼 TimesJobs Web Scraper

A Python web scraping project that extracts job listings from **TimesJobs** using **Requests, BeautifulSoup, Pandas, and Playwright**.

The project focuses on collecting job-related information, handling pagination, and preparing the scraped data for further analysis.

## 🛠️ Tech Stack

* **Python**
* **Requests** – HTTP requests
* **BeautifulSoup** – HTML parsing
* **Pandas** – Data cleaning and processing
* **Playwright** – Browser automation and dynamic content

## 📊 Data Collected

The scraper extracts information such as:

* Job Title
* Company Name
* Location
* Experience
* Skills
* Job Description
* Posting Date

## 🔄 Workflow

```text
TimesJobs
    ↓
Requests / Playwright
    ↓
BeautifulSoup
    ↓
Extract Job Listings
    ↓
Pandas
    ↓
Clean & Store Data
```

## 📂 Project Structure

```text
timesjobs-web-scraper/
│
├── data/
│   └── timesjobs_jobs.csv
├── notebooks/
│   └── timesjobs_scraper.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/timesjobs-web-scraper.git
cd timesjobs-web-scraper
```

Install dependencies:

```bash
pip install -r requirements.txt
```

For Playwright:

```bash
playwright install
```

## 🎯 Key Features

* Scrapes multiple job listings
* Supports pagination
* Handles missing data
* Extracts structured job information
* Processes data using Pandas
* Can be extended for different job searches

## 👨‍💻 Author

**Waqar Aamir**

⭐ Feel free to explore, improve, and contribute to the project.
