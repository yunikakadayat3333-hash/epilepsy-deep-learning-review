# Three Decades of Deep Learning for Epileptic Seizure 
# Detection and Prediction (1990–2025)

## About
This repository contains the analysis code and data for 
a PRISMA-compliant systematic bibliometric review of 2,474 
papers on deep learning for EEG-based epileptic seizure 
detection and prediction.

## Contents
- `epilepsy_review_analysis.ipynb` — Main analysis notebook
- `corpus_filtered.csv` — 2,474 papers filtered from OpenAlex
- Additional CSVs — Per-stage paper analyses

## How to reproduce
1. Open `epilepsy_review_analysis.ipynb` in Google Colab
2. Mount your Google Drive
3. Update paths in early cells to your environment
4. Run cells sequentially (~10 min on T4 GPU)

## Methodology
Detailed in Section 2 of the paper. The corpus was identified 
through a three-stage regex filter on OpenAlex requiring 
explicit mention of epilepsy, deep learning, and EEG terms.

## License
MIT License

## Author
Yunika Kadayat, Vijay Singh, Parul Madan, Preeti Narooka
