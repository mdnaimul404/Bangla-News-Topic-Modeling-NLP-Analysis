# 📰 Bangla-News-Topic-Modeling-NLP-Analysis

> **An end-to-end R-based system that scrapes Bangla news articles from NTV Bangladesh, performs text preprocessing, visualization, and applies LDA topic modeling to uncover hidden themes and insights.**

---

## 📌 Project Overview

This project demonstrates a complete **Natural Language Processing (NLP)** pipeline on real-world Bangla news data.
It automatically collects articles from **NTV Bangladesh**, cleans and processes Bangla text, performs frequency analysis, and applies **Latent Dirichlet Allocation (LDA)** to discover major discussion topics.

### This project is suitable for:

* Bangla NLP research
* Media and news analysis
* Topic modeling and data science applications
* Academic and portfolio projects

---

## 🛠️ Technologies & Libraries

**Language:** R

**Core Libraries:**

* `rvest` – Web scraping
* `dplyr`, `tidyr`, `purrr`, `stringr` – Data processing
* `tm`, `tokenizers`, `tidytext` – Text mining
* `wordcloud`, `RColorBrewer`, `ggplot2` – Visualization
* `topicmodels` – LDA topic modeling

---

## ⚙️ System Workflow

1. **Web Scraping** – Collects article links and titles from NTV Bangladesh
2. **Article Extraction** – Visits each article link and extracts Bangla news text
3. **Text Preprocessing** – Removes punctuation, numbers, English words, and Bangla stopwords
4. **Text Analysis & Visualization** – Creates document-term matrix, frequency analysis, and plots
5. **Topic Modeling** – Applies LDA with 5 topics and analyzes topic-wise word distributions

---

## 📂 Output Files

| File                                        | Description                      |
| ------------------------------------------- | -------------------------------- |
| `ntv_links_with_labels.csv`                 | Scraped article links            |
| `ntv_article_texts.csv`                     | Extracted article text           |
| `wordcloud.png`                             | Word cloud visualization         |
| `top_words_plot.png`                        | Top 20 frequent words            |
| `barplot_topic1.png` – `barplot_topic5.png` | Topic-wise word distributions    |
| `Document–Topic Distribution.png`           | Document-topic probability chart |

---

## 🚀 How to Run the Project

### Step 1: Install Dependencies

```r
install.packages(c("rvest","readr","dplyr","purrr","tidyr","stringr",
                   "tm","tokenizers","wordcloud","RColorBrewer",
                   "topicmodels","tidytext","ggplot2"))
```

### Step 2: Run the Script

```r
source("Group02_FinaltermProjectScript.R")
```

All data files and outputs will be generated automatically.

---

## 🎯 Applications

* Bangla language processing
* News and media analytics
* Topic discovery and trend analysis
* Data science and NLP research
* Academic and professional portfolios


---

## ⭐ Repository Topics

`r` `nlp` `bangla-nlp` `topic-modeling` `web-scraping` `text-mining` `lda` `data-science`

---
