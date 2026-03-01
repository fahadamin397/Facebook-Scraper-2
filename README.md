# 📘 Facebook Scraper 2

A Python command-line application to scrape Facebook user data.

This project uses **Selenium** and **Python** to automate Facebook login and extract information such as friend lists or other user-related content.

---

## 🚀 Features

- Automated Facebook login
- Dynamic content scrolling
- HTML, JSON, or CSV export support
- Configurable through command-line options
- Reusable script setup via `setup.py`

---

## 🛠 Built With

This project is implemented using:

- Python 3
- Selenium WebDriver
- Firefox (GeckoDriver)
- BeautifulSoup (optional depending on use)
- argparse for CLI integration

---

## 📦 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/fahadamin397/Facebook-Scraper-2.git
cd Facebook-Scraper-2
```

---

### 2️⃣ Install dependencies

Install required Python libraries:

```bash
pip install selenium
```

Ensure you also have:
- Firefox browser installed
- GeckoDriver in your system PATH

---

### 3️⃣ Run the scraper

You can execute the main Python script:

```bash
python main.py
```

You may be prompted to enter your Facebook credentials.

---

## ⚙ Command Line Arguments

You can provide common options at runtime:

| Option | Description |
|--------|-------------|
| `--headless` | Run browser in headless mode |
| `--json` | Export data in JSON |
| `--csv` | Export data in CSV |
| `--html` | Save raw HTML |
| `--timeout` | Custom wait timeout for page load |

> Refer to the `main.py` code for exact available CLI flags if they differ.

---

## ⚠️ Legal & Ethical Notice

This project is intended **only for educational purposes** and for interactions with **your own Facebook account only**.  
Scraping data from Facebook without explicit permission or outside platform rules **may violate terms of service** and local laws.

Please use this tool responsibly.

---

## 🛠 Future Improvements

- Add robust error handling
- Improve headless automation support
- Add Docker container for easier setup
- Add automated tests

---

## 👤 Author

**Muhammad Fahid Amin**  
SQA Automation Engineer | Python & Automation Enthusiast

---

If you want, I can also tailor this README further with usage examples and screenshots, or generate a GitHub repo description and topic tags!
::contentReference[oaicite:1]{index=1}
