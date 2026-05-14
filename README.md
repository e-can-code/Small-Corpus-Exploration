# 📊 Small Corpus Exploration: Twisted Tongues
**Computational Linguistics | Python Data Analysis**

This project explores the statistical properties of a specialized "Tongue Twister" corpus. Using Python, I implemented a custom pipeline for **tokenization**, **normalization**, and **frequency analysis** to investigate how repetitive phonological patterns impact standard linguistic distributions like Zipf's Law.

## 🔬 Research Questions
1. **Frequency Analysis:** Which specific "types" (unique words) yield the highest "token" (occurrence) count in a repetitive corpus?
2. **Hapax Legomena:** How many words appear exactly once, and what does this reveal about the lexical density of tongue twisters?
3. **Zipf’s Law:** Does a corpus designed for phonological difficulty still follow the standard power-law distribution of natural language?

## 🚀 View the Project
* **Interactive Notebook:** [`twistedTongues_ecca4377.ipynb`](./twistedTongues_ecca4377.ipynb)
* **Static HTML Report:** [`twistedTongues_ecca4377.html`](./twistedTongues_ecca4377.html)

---

## 🛠️ Technical Implementation

### Data Pipeline
* **Normalization:** Manual implementation of punctuation removal and case-folding to ensure case-insensitive type counting (e.g., "YOU" and "you" are treated as a single type).
* **Tokenization:** Whitespace-delineated parsing to transform raw strings into processable lists.
* **Statistical Analysis:** Custom functions to calculate raw frequency distributions and identify **Hapax Legomena**.

### Tech Stack
* **Language:** Python 3.11
* **Environment:** Jupyter Notebook (`.ipynb`)
* **Key Logic:** Functional programming using `lambda` for sorting dictionaries by value and iterative filtering for frequency thresholds.

---

## 💡 Key Insights
* **The "Article" Dominance:** In the analyzed sample, the type `"a"` was the most frequent (8 occurrences), confirming that even in specialized corpora, function words often maintain the highest density.
* **Hapax Legomena:** Identified 9 unique hapaxes (e.g., *cautious, careful, corrupt*). Note: Identifying these using **wordforms** versus **lemmas** yields different results; using lemmas would group *corrupt* and *corrupted*, further decreasing the hapax count.
* **Zipf's Law Deviation:** While the corpus demonstrates a general "long tail" distribution, the repetitive nature of tongue twisters leads to a higher-than-average concentration of specific content words compared to standard prose.



---

## 🗺️ Project Roadmap
- [x] Initial Tokenization & Normalization
- [x] Raw Frequency Distribution Logic
- [x] Identification of Hapaxes Legomena
- [ ] Integration of Lemmatization (to group base word forms)
- [ ] Comparison with the Brown Corpus for function vs. content word ratios

---

### 📧 Contact & Submission
**Echo Canaday** ecca4377@colorado.edu
