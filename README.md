# Sentiment Analysis for Leisure Industry

This repository contains hotel review datasets from TripAdvisor alongside notebooks for scraping and analyzing the text data.

## Datasets

The root folder includes CSV and XLSX files grouped by hotel star ratings (2–5 stars) and by review period:

- **Pre-COVID reviews**: `2star precovid*`, `3star precovid*`, `4star precovid*`, `5star precovid*`
- **Post-COVID reviews**: `2star postcovid*`, `3star postcovid*`, `4star postcovid*`, `5star postcovid*`

Each group contains both `.csv` and `.xlsx` versions of the scraped TripAdvisor reviews.

## Notebooks

- **`scrape_tripadvisor_reviews.ipynb`** (`TRIP ADVISOR FINALyyy.ipynb`)
  - Demonstrates how the review data was collected from TripAdvisor using `requests_html` and `BeautifulSoup`.
- **Topic modeling notebook** (`Topic Modelling_Bitcoin(1)-Copy1.ipynb`)
  - Performs preprocessing and Latent Dirichlet Allocation (LDA) topic modeling on the review text to discover common themes.

## Setup

1. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

2. Launch Jupyter and open the notebooks:

   ```bash
   jupyter notebook
   ```

The notebooks assume the dataset files remain in the repository root.
