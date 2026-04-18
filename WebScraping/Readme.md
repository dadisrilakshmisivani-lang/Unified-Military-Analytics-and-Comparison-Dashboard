# 🌐 Web Scraping Module

This folder contains scripts and notebooks used to collect military data for the **Unified Military Analytics and Comparison Dashboard** project.

---

## 📌 Files

### 📓 Google Colab Notebook

Access the web scraping notebook here:

👉 https://colab.research.google.com/drive/1WYeyRtUlf2EsADEKnPcbKT7GNliZEO8m

---

### 📄 colab_link.txt

Contains the direct link to the notebook for quick access.

---

## ⚙️ Technologies Used

* Python
* requests
* BeautifulSoup
* pandas

---

## 🔄 Workflow

1. Load URLs from `links for military data.txt`
2. Send HTTP requests to fetch webpage data
3. Parse HTML using BeautifulSoup
4. Extract military metrics (aircraft, tanks, manpower, etc.)
5. Store structured data into CSV files

---

## 📊 Output

* `military_raw_data.csv`
* Stored in: `data/raw/`

---

## 📝 Notes

* Covers 140+ countries
* Data sourced from GlobalFirepower.com
* Includes error handling for failed requests
