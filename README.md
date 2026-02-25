# X (Twitter) Historical Data Scraper

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat&logo=selenium&logoColor=white)
![Status](https://img.shields.io/badge/Status-Research_Tool-informational.svg)

This project is a Python-based web scraper designed to collect historical data from X (formerly Twitter) using **Selenium**. It was specifically developed to gather tweets related to the **2023 Turkey-Syria Earthquake** for academic research and sentiment analysis purposes.

## 📌 Project Purpose
Social media data is vital for understanding public response during natural disasters. This tool automates the process of:
1. Navigating through X's login authentication.
2. Executing advanced search queries (e.g., specific keywords and date ranges).
3. Scraping tweet content through automated scrolling.
4. Saving collected data into a structured `.txt` format for further NLP (Natural Language Processing) analysis.

---

## 🛠️ Technical Workflow
* **Automation:** Uses Selenium WebDriver to simulate human-like interactions (scrolling, clicking, typing).
* **Search Query:** Utilizes X's advanced search filters (`until:YYYY-MM-DD since:YYYY-MM-DD`).
* **Dynamic Loading:** Implements `PAGE_DOWN` simulation and implicit waits to handle lazily-loaded content.
* **Data Deduplication:** Ensures each tweet is captured only once during the session.

---
