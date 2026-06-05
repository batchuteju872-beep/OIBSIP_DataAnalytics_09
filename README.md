# OIBSIP_DataAnalytics_09: Autocomplete and Autocorrect Data Analytics

This repository contains the practical implementation of an Autocomplete and Autocorrect system developed during my Data Analytics Internship at **Oasis Infobyte**.

## Project Objective
The goal is to explore the efficiency, latency, and accuracy of Natural Language Processing (NLP) text prediction algorithms. The system cleans custom raw corpora, establishes vocabulary metrics, handles prefix string matches, and fixes spelling errors using probabilistic minimum edit-distance logic.

## Key Concepts Implemented
* **NLP Preprocessing:** Lowercasing, tokenization, and filtering text using regular expressions (`re`).
* **Autocorrect Feature:** Built an algorithmic pipeline mapping misspelled inputs to vocabulary targets using 1-edit and 2-edit structural mutations (Inserts, Deletes, Swaps, Replaces).
* **Autocomplete Feature:** Implemented efficient lookup arrays matching input prefixes to real-time dictionary distributions.
* **Data Analytics Metrics:** Measured algorithmic latency execution and visualized top vocabulary frequencies utilizing `Matplotlib` and `Seaborn`.

## Tools & Libraries Used
* **Language:** Python 3
* **Environments:** Google Colab / Jupyter Notebook
* **Packages:** `nltk`, `pandas`, `matplotlib`, `seaborn`, `collections`, `time`
