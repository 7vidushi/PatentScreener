# PatentScreener

**AI-Oncology Patent Intelligence Tool**  
Preliminary patentability assessment under Indian Patent Law

---

## Live Links

**Online version (recommended):**  
https://7vidushi.github.io/PatentScreener/PatentScreener.html

**Offline version (download and open locally — no internet needed):**  
https://7vidushi.github.io/PatentScreener/PatentScreener_Offline.html

---

## What it does

PatentScreener analyses an AI-oncology invention and returns:

- Section 3(k), 3(i), and 3(c) risk assessment under Indian Patent Law
- Top 4 closest prior art patents from the research database
- Innovation white space score — how crowded the invention zone is
- Jurisdiction recommendation with real grant rates
- Dashboard with 6 charts from the patent landscape research
- Explorer — searchable and filterable patent database

---

## The Research Behind It

Built as part of a 6-month research internship studying the global 
patent landscape of AI-driven cancer diagnostics with focus on 
India's intellectual property challenges.

**Key finding:**
- India filed 392 AI-oncology patents between 2018–2026
- India granted zero — 0% grant rate
- South Korea granted 48% in the same period
- United States granted 34.4%

This asymmetry is the problem PatentScreener addresses.

---

## Dataset

- 2,834 patents collected from Espacenet, Google Patents, 
  Lens.org, and InPASS
- 500 patents manually coded for Indian patent law risk 
  under Sections 3(k), 3(i), and 3(c)
- Coverage: 2018 to 2026
- Focus: AI techniques applied to cancer diagnostics, 
  prognostics, genomics, and therapeutics

---

## How to Use

1. Open the live link above in any browser
2. Enter your invention title and description
3. Select AI technique, cancer type, and category
4. Click Analyse Patentability
5. Review risk scores, prior art, and filing recommendations

No installation needed. Works on mobile and desktop.

---

## Files in this Repository

| File | Description |
|------|-------------|
| PatentScreener.html | Online web tool — opens in any browser |
| PatentScreener_Offline.html | Offline version — no internet needed |
| PatentScreener_Analysis.ipynb | Python analysis notebook — 9 charts from 2,834 patents |
| README.md | Project description |


## Technology

- HTML — structure
- CSS — dark theme design
- JavaScript — risk algorithm, prior art matching, white space
- Chart.js — dashboard charts
- No frameworks · No server · No database · No login required

---

## Research Context

No tool existed that assesses Indian Patent Law Section 3 risk 
specifically for AI-oncology inventions. PatentScreener fills 
that gap using an original dataset of 500 manually coded patents.

---

## Author

Research Intern — AI-Oncology Patent Landscape Study  
2025–2026  
GitHub: https://github.com/7vidushi
```

---

Scroll down, click **Commit changes**, add message:
```
Update README with both live links and full description
