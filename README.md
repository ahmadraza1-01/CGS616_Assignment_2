# CGS616_Assignment_2

# Fake Review Detection – Analytical Approach
## Introduction

Online reviews influence consumer decisions but can be manipulated through fake reviews.
This project develops a systematic approach to detect fake reviews in the Amazon Reviews 2023 dataset using EDA, NLP, and rule-based filtering techniques.

## Dataset

Source: Amazon Reviews 2023

Used: ~0.8M appliance product reviews (subset of ~2M)

Features: review text, title, rating, sentiment, timestamp, user ID

## Installation

Clone this repo and install the required dependencies:

git clone https://github.com/yourusername/fake-review-detection.git
cd fake-review-detection
pip install -r requirements.txt

## Tools & Libraries

pandas, numpy – data handling

nltk, TextBlob, VADER – NLP + sentiment analysis

matplotlib, seaborn – visualization

re – regex for text cleaning

## Usage

Run the Jupyter notebook or script:

python detect_fake_reviews.py


## Main steps:

EDA & Cleaning (remove nulls, non-alphabetic text)

Fake Review Detection

Duplicate text detection

Sentiment–rating mismatch

Suspicious user activity (>20 reviews)

Final consistency checks

Analytics & Visualization

## Results

~10% reviews flagged as fake (mostly duplicates or sentiment mismatches).

Price alone not predictive (R² ~0).

KDE analysis suggests expensive products attract more fake reviews.

## Authors

* Ahmad Raza (220088): Report writing (65%), 2 criteria, part coding
* Harsh Agrawal (220425): Report writing (35%), 2 criteria, majority coding
