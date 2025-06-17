# 🧠 Lead Scraper

This Python tool scrapes business lead info from Google Maps (via the Places API) and saves the results into a formatted Excel spreadsheet.

---

## ✨ Features

- Prompt-based input for:
  - Business type (e.g. “window blinds”)
  - Area/location (e.g. “Manchester, UK”)
  - Search radius (in metres)
- Extracts:
  - Name
  - Phone number
  - Website
  - Email address (scraped from homepage)
  - Google Maps link
  - Ratings / review count
- Outputs to styled `.xlsx` spreadsheet with hyperlinks

---

## 🚀 How to Use

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Set your API key

Create a `.env` file in the project root:

```
GOOGLE_MAPS_API_KEY=your_key_here
```

Or set it manually in your shell:

```bash
set GOOGLE_MAPS_API_KEY=your_key_here
```

### 3. Run the script

```bash
python leadscrape.py
```

---

## ⚠️ Important Notes

- Do **not** commit your `.env` or real API key to GitHub.
- The Google Maps API has usage quotas — costs may apply after your free tier.
- This tool is for personal/business lead generation use — don’t use it to mass-harvest or resell Google data.

---

## 📝 License

MIT
