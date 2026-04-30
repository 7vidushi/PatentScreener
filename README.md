# PatentScreener

**AI-Oncology Patent Intelligence Tool**  
Preliminary patentability assessment under Indian Patent Law

PatentScreener is a research prototype for screening AI-oncology inventions under key exclusions in the Indian Patents Act, especially Sections 3(k), 3(i), and 3(c). The project started as a rule-based JavaScript tool and now includes a browser-based machine learning prototype.

---

## Live Links

**ML prototype for viva/demo:**  
https://7vidushi.github.io/PatentScreener/PatentScreener_ML.html

**Original online version:**  
https://7vidushi.github.io/PatentScreener/PatentScreener.html

**Offline version:**  
https://7vidushi.github.io/PatentScreener/PatentScreener_Offline.html

---

## What It Does

PatentScreener analyses an AI-oncology invention and provides:

- Section 3(k), 3(i), and 3(c) risk assessment under Indian Patent Law
- ML-based risk prediction for Low, Moderate, and High risk categories
- Probability scores for each Section 3 risk class
- Prior-art and patent landscape support in the original tool
- Innovation white space and jurisdiction-oriented research insights
- Dashboard and explorer views based on the patent landscape study

The ML demo runs directly in the browser using exported model weights, so it can be hosted permanently on GitHub Pages without a backend server.

---

## Machine Learning Prototype

The ML version uses three supervised classifiers:

- **Section 3(k)** - algorithm / software patentability risk
- **Section 3(i)** - medical treatment or diagnostic method risk
- **Section 3(c)** - discovery or natural phenomenon risk

The models were trained in Python using TF-IDF text features and logistic regression. The trained model weights were exported to:

```text
patent_screener_models.json
```

The GitHub Pages interface loads this JSON file and performs prediction client-side in JavaScript.

Future scope includes:

- Python/FastAPI backend deployment
- Larger transformer or patent-domain language models
- Semantic prior-art search using embeddings
- Live patent database updates
- LLM-assisted legal explanation generation

---

## Research Behind It

This project was built as part of a 6-month research internship studying the global patent landscape of AI-driven cancer diagnostics, with a focus on India's intellectual property challenges.

Key finding:

- India filed 392 AI-oncology patents between 2018 and 2026
- India granted zero, resulting in a 0% grant rate
- South Korea granted 48% in the same period
- The United States granted 34.4%

This asymmetry is the problem PatentScreener addresses.

---

## Dataset

The research dataset includes:

- 2,834 patents collected from Espacenet, Google Patents, Lens.org, and InPASS
- 1,298 labeled foreign patent records with abstracts used for the ML prototype
- 500 manually coded patent records for Indian Patent Law risk analysis
- Coverage from 2018 to 2026
- Focus on AI techniques applied to cancer diagnostics, prognostics, genomics, imaging, screening, and therapeutics

Risk labels cover:

- Section 3(k)
- Section 3(i)
- Section 3(c)

---

## How To Use

1. Open the ML prototype link.
2. Enter the invention title and abstract or description.
3. Select the AI technique, cancer type, and application domain.
4. Add an IPC code if available.
5. Click **Analyze Patentability**.
6. Review the predicted risk level and probability scores for Sections 3(k), 3(i), and 3(c).

The original online version can also be used for rule-based screening, prior-art matching, dashboard charts, and patent explorer views.

---

## Files In This Repository

| File | Description |
| --- | --- |
| `PatentScreener_ML.html` | ML prototype web interface hosted on GitHub Pages |
| `patent_screener_models.json` | Exported browser-readable ML model weights |
| `PatentScreener.html` | Original online web tool |
| `PatentScreener_Offline.html` | Offline version that can be opened locally |
| `PatentScreener_Analysis.ipynb` | Python analysis notebook for patent landscape charts |
| `PatentScreener_MLClassifier.ipynb` | Python notebook for training the ML classifier |
| `README.md` | Project description |

---

## Technology

- HTML and CSS for the web interface
- JavaScript for browser-side prediction and interactivity
- Python for data analysis and model training
- scikit-learn for TF-IDF and logistic regression models
- Chart.js for dashboard visualizations in the original tool
- GitHub Pages for static deployment

Current deployment does not require a backend, database, login system, or API server.

---

## Research Context

No dedicated tool existed for preliminary assessment of Indian Patent Law Section 3 risk specifically for AI-oncology inventions. PatentScreener addresses this gap by combining patent landscape research, curated legal-risk coding, and a lightweight ML screening prototype.

The tool is a research and educational prototype. It is not legal advice.

---

## Author

Research Intern - AI-Oncology Patent Landscape Study  
2025-2026  
GitHub: https://github.com/7vidushi

```
Update README with both live links and full description
