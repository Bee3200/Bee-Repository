# ITAI 2373 – NewsBot Intelligence System (Midterm)

**Student:** Bryan Tzorin (solo)  
**Course:** ITAI 2373 – Natural Language Processing  
**Environment:** Google Colab (free tier)

[![Open in Colab](https://img.shields.io/badge/Run_in-Colab-brightgreen?logo=googlecolab)](https://colab.research.google.com/github/Bee3200/Bee-Repository/blob/main/ITAI2373-NewsBot-Midterm/ITAI2373_NewsBot_Midterm.ipynb)

---

## How to run (instructor quick start)

1. Click the **Open in Colab** badge above.  
2. In Colab: **Runtime → Run all**.  
3. The notebook downloads the dataset (BBC set or local copy), preprocesses, trains multi-class models, runs POS/NER/sentiment, and prints/plots results.

> **If a path differs** (e.g., if you renamed the notebook), update the link above and re-commit.

---

## Deliverables

- **Notebook:** [`ITAI2373_NewsBot_Midterm.ipynb`](ITAI2373_NewsBot_Midterm.ipynb)  
- **Reflection (PDF):** [`../docs/NewsBot-Reflection-Solo-Bryan-Tzorin-ITAI-2373.pdf`](../docs/NewsBot-Reflection-Solo-Bryan-Tzorin-ITAI-2373.pdf)

---

## What this system does

- End-to-end NLP pipeline integrating **Modules 1–8**:
  - Text cleaning & normalization
  - TF–IDF feature extraction + analysis
  - POS tagging, dependency parsing, semantic patterns
  - Sentiment & emotion analysis
  - Named entity recognition (PERSON, ORG, GPE, DATE, MONEY)
  - Multi-class article classification (model comparison + metrics)
- Produces instructor-facing plots/tables and a brief business-value narrative.

---

## Dataset

- **BBC News Classification** (recommended set in the instructions).  
- Loaded in-notebook. If Kaggle/API is rate-limited, the notebook falls back to manual upload instructions.

---

## Grading Checklist (for instructor)

- [x] **Integration:** Modules 1–8 combined into one working system  
- [x] **Technical:** Preprocessing, TF–IDF, POS/Parsing/Semantics, Sentiment/Emotion, NER, Multi-class classification  
- [x] **Analysis:** Visualizations + interpretation (feature importance, distributions, errors)  
- [x] **Docs:** This `README.md` + Reflection PDF in `/docs`  
- [x] **Reproducibility:** Runs clean in Colab free tier

---

## Notes

- All code cells are annotated; key hyperparameters are documented inline.
- Random seeds are set for reproducibility where applicable.
