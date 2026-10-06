Google Play Store Reviews Analysis & Sentiment Modeling

A data science project focused on scraping, analyzing, and building machine learning models for user reviews collected from the Google Play Store.

📌 Project Overview

This repository contains end-to-end workflows for:

Scraping user reviews from Google Play Store apps.

Performing Exploratory Data Analysis (EDA) and text preprocessing.

Building sentiment analysis and topic modeling pipelines to extract user insights and feedback trends.

📁 Repository Structure

.
├── data/                  # Raw and processed datasets
│   ├── raw/               # Scraped review datasets
│   └── processed/         # Cleaned and engineered feature datasets
├── notebooks/             # Jupyter Notebooks for analysis
│   └── 01_scraping.ipynb  # Google Play Store review scraping module
├── src/                   # Source code and helper scripts
├── .gitignore             # Standard Git ignore rules
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation


📊 Dataset Summary

The dataset scraped in notebooks/01_scraping.ipynb contains Google Play Store app reviews with the following specifications:

Total Reviews: 144,000 entries

Total Features: 11 columns

Key Features:

reviewId: Unique review identifier

userName: Reviewer's display name

content: Review text content

score: Star rating (1 to 5)

thumbsUpCount: Number of helpful votes

at: Timestamp of review submission

reviewCreatedVersion / appVersion: App version installed at review time

replyContent & repliedAt: Developer response content and timestamp

🚀 Getting Started

Prerequisites

Python 3.8 or higher

pip package manager

Installation

Clone the repository:

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name


Create a virtual environment (optional but recommended):

python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate


Install dependencies:

pip install -r requirements.txt


🛠️ Usage

Open the Jupyter Notebook environment to run the scripts:

jupyter notebook


Navigate to notebooks/01_scraping.ipynb to inspect or run the scraping script.