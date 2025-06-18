# 🚖 Uber Data Analytics | Modern Data Engineering GCP Project

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![GCP](https://img.shields.io/badge/Google%20Cloud-Platform-blue?logo=googlecloud)
![MageAI](https://img.shields.io/badge/Mage%20AI-Data%20Pipelines-orange?logo=github)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Overview

This project demonstrates how to build a scalable, end-to-end data analytics pipeline using **Google Cloud Platform (GCP)** and **Mage AI**. It performs analysis on Uber trip data to derive business insights and visualize key metrics using **Looker Studio**.

---

## 🚀 Features

- Scalable ingestion of NYC Taxi trip data
- Data transformation using Mage AI pipelines
- Analytical querying with BigQuery
- Fully interactive Looker Studio dashboards
- Cloud-native architecture with Python & GCP

---


## 🛠️ Technologies Used

| Category       | Tools & Services                                   |
|----------------|----------------------------------------------------|
| Language       | ![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python) |
| Data Pipeline  | [Mage AI](https://github.com/mage-ai/mage-ai)     |
| Cloud Platform | GCP: Storage, Compute Engine, BigQuery, Looker Studio |
| Dashboarding   | [Looker Studio](https://lookerstudio.google.com/) |

---

## 📊 Dataset Used

**Source:** [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)  
This dataset includes records of yellow and green taxi trips with fields such as:

- Pick-up and drop-off timestamps and locations  
- Trip distance and fare details  
- Payment type and rate codes  
- Passenger counts  

📚 [Data Dictionary](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf)

---

## 📂 Project Workflow

1. **Data Ingestion**  
   Load trip data files into **Google Cloud Storage**.

2. **Data Processing**  
   Use **Mage AI** pipelines for data cleaning, transformation, and schema validation.

3. **Data Analysis**  
   Load the processed data into **BigQuery** and write SQL queries for insights.

4. **Data Visualization**  
   Build **interactive dashboards** in **Looker Studio** to explore trends and KPIs.

---

## 📈 Dashboard Preview


![Dashboard](./dash-board/dash-board-1.jpg "Dashboard Image")

---

## 📦 Getting Started

### ✅ Prerequisites

- Google Cloud account with Storage, BigQuery, and Looker Studio enabled
- Python 3.10+
- Mage AI installed

### 🛠 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/uber-data-analytics-gcp.git
cd uber-data-analytics-gcp

# Install dependencies
pip install -r requirements.txt

# Start Mage AI
mage start your_project_name
