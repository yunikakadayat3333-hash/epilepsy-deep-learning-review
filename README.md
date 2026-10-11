# Three Decades of Deep Learning for Epileptic Seizure 
# Detection and Prediction (1990–2025)

## About
This repository contains the analysis code and data for a PRISMA-compliant
systematic bibliometric review of 2,474 papers on deep learning for EEG-based
epileptic seizure detection and prediction.

## Contents
epilepsy_review_analysis.ipynb` — full pipeline: OpenAlex query, three-stage filter, BERTopic, figures
- `corpus_filtered.csv` — 2,474 papers (titles, abstracts, authors, affiliations, years, citations, keywords)
- `stage_a_papers.csv` to `stage_d_papers.csv` — per-stage paper subsets
- `papers_with_topics.csv` — corpus with BERTopic assignments (38 topics)
- `bertopic_model.pkl` — fitted BERTopic model
- `requirements.txt` — package versions used

## How to reproduce
1. Open `epilepsy_review_analysis.ipynb` in Google Colab
2. Mount your Google Drive
3. Update paths in early cells to your environment
4. Run cells sequentially ( on T4 GPU)

## Methodology
Detailed in Section 2 of the paper. The corpus was identified 
through a three-stage regex filter on OpenAlex requiring 
explicit mention of epilepsy, deep learning, and EEG terms.
## Data source
All records are bibliometric metadata from OpenAlex.
No patient or human-subject data are included.

## License
MIT License

## Author
Yunika Kadayat, Vijay Singh, Parul Madan, Preeti Narooka
