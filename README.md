# AI Research Trends from arXiv 📈🤖

This project explores the evolving landscape of Artificial Intelligence (AI) research by analyzing metadata from the arXiv repository. Using Natural Language Processing (NLP) and data visualization, it uncovers key trends, popular topics, and publication patterns in AI-related domains.

---

## 📌 Project Objective

To answer the question: **"What are the key trends driving AI research?"**

We achieve this by:

- Collecting metadata from arXiv categories such as `cs.AI`, `cs.LG`, `cs.CL`, `cs.CV`, and `stat.ML`
- Analyzing paper abstracts, titles, and submission dates
- Visualizing trends and applying topic modeling to identify research focus areas over time

---

## 🧪 Features

- 📥 Scrape AI-related paper metadata using the arXiv API
- 🧹 Preprocess and clean abstracts and titles
- 🔍 Perform topic modeling with NLP techniques (LDA, BERTopic)
- 📊 Visualize trends over time (top keywords, categories, yearly paper count)
- 🧠 Discover shifts in AI research focus (e.g., from CNNs to Transformers to LLMs)

---

## 🧰 Tech Stack

- **Python**
- **arxiv** (for fetching paper metadata)
- **pandas**, **matplotlib**, **seaborn** (data handling and visualization)
- **spaCy / NLTK** (text preprocessing)
- **scikit-learn / BERTopic / Gensim** (topic modeling)

---

## 📂 Folder Structure

```text
ai-research-trends-arxiv/
├── data/               # Cached or preprocessed metadata (CSV, JSON, etc.)
├── notebooks/          # Jupyter notebooks for data exploration and modeling
├── scripts/            # Python scripts for data collection, cleaning, and preprocessing
├── visualizations/     # Output charts, graphs, and other visual assets
├── .txt    # Python dependencies for the project
└── READMrequirementsE.md           # Project overview and documentation
```

## 📈 Sample Visuals (Coming Soon)

- Trends in research volume over time
- Word clouds of dominant terms per year
- Topic frequency plots
- Co-authorship or keyword networks

---

## 🚀 Getting Started

1. Clone the repo:

   ```bash
   git clone https://github.com/ab3lT/ai-research-trends-arxiv.git
   cd ai-research-trends-arxiv
