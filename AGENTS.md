# AGENTS.md — scrap

## What this is
Python web scraping tool using BeautifulSoup and Selenium to extract content from websites.

## Stack
- Python 3.12
- BeautifulSoup4
- Selenium

## Build
```bash
python3.12 -m venv env
. env/bin/activate
pip install -r requirements.txt
```

## Run
```bash
python main.py
```

## Structure
- `main.py` — main scraping script
- `requirements.txt` — Python dependencies (beautifulsoup4, selenium)

## Conventions
- No comments in code unless asked.
- Verify: `python -m py_compile main.py`
