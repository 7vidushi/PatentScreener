# PatentScreener

AI-powered patentability screener for AI-oncology inventions 
under Indian Patent Law.

---

## What it does

PatentScreener analyses an AI-oncology invention description 
and returns:

- Section 3(k), 3(i), and 3(c) risk assessment
- Top 4 closest prior art patents from a coded database
- Innovation white space score
- Jurisdiction recommendation with real grant rates

---

## The Research Behind It

This tool was built as part of a 6-month research internship 
on the global patent landscape of AI-driven cancer diagnostics.

Key finding from the research:
- India filed 392 AI-oncology patents between 2018 and 2026
- India granted zero of them — 0% grant rate
- South Korea granted 48% in the same period
- United States granted 34.4%

This asymmetry is the problem PatentScreener tries to address.

---

## Dataset

The tool is powered by an original research dataset of:

- 2,834 patents collected from Espacenet, Google Patents, 
  Lens.org, and InPASS
- 500 patents manually coded for Indian patent law risk 
  under Sections 3(k), 3(i), and 3(c)
- Coverage: 2018 to 2026
- Focus: AI techniques applied to cancer diagnostics, 
  prognostics, genomics, and therapeutics

---

## How to Use

1. Open PatentScreener.html in any browser
2. Enter your invention title and description
3. Select AI technique, cancer type, and category
4. Click Analyse Patentability
5. Review risk scores, prior art, and filing recommendations

No installation needed. No internet connection required 
after the file loads. Everything runs locally in the browser.

---

## Technology

- HTML — page structure
- CSS — visual design and dark theme
- JavaScript — risk algorithm, prior art matching, 
  white space calculation
- Chart.js — dashboard visualisations
- No frameworks, no server, no database

---

## Research Context

This tool was developed to address a gap identified in the 
research — no tool exists that assesses Indian Patent Law 
Section 3 risk specifically for AI-oncology inventions.

The dataset of 500 manually coded patents is original 
primary research. The risk algorithm maps directly to 
provisions of the Indian Patents Act 1970.

---

## Author

Research Intern — AI-Oncology Patent Landscape Study  
2025–2026# PatentScreener
AI-powered patentability screener for AI-oncology inventions under Indian Patent Law — built on a dataset of 2,834 patents with Section 3 risk analysis
