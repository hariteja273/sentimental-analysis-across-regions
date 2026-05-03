# sentimental-analysis-across-regions
# 🇮🇳 Regional Sentiment Analysis Dashboard

## 📌 Project Overview
This project analyzes customer reviews from different regions of India using Natural Language Processing (NLP) and sentiment analysis. The system automatically detects region/city information from the dataset, analyzes customer opinions, and visualizes sentiment differences across regions on an interactive India map.

## 🎯 Problem Statement
Businesses receive customer feedback from multiple regions, but understanding regional sentiment patterns manually is difficult and time-consuming.

This project solves this problem by:
- Automatically analyzing customer reviews
- Identifying positive, negative, and neutral sentiments
- Comparing sentiment differences across regions
- Highlighting trending words in each region
- Visualizing regional sentiment on an interactive map

## 🚀 Features
- Automatic CSV file upload
- Auto detection of region/city column
- NLP-based sentiment analysis
- Interactive India sentiment map
- Region-wise sentiment comparison
- Trending keyword analysis
- Average sentiment score calculation

## 🛠 Technologies Used
- Python
- Pandas
- TextBlob
- Plotly
- Google Colab
- Natural Language Processing (NLP)

## 📂 Dataset Requirements
The CSV file should contain:
- Review column
- City or Region column

Example:

| Review | Region |
|--------|--------|
| Great service | Hyderabad |
| Poor support | Mumbai |
| Product is okay | Delhi |

## 📊 Project Workflow
1. Upload dataset
2. Detect region and review columns
3. Perform sentiment analysis
4. Classify reviews:
   - Positive 😊
   - Neutral 😐
   - Negative 😡
5. Aggregate region-wise results
6. Display India sentiment map
7. Show trending words for selected region

## 📈 Output
The project generates:
- Sentiment score for each review
- Region-wise average sentiment
- Positive/Negative/Neutral counts
- Interactive India map visualization
- Trending words by region

## ▶️ How to Run
1. Clone this repository

```bash
git clone <your-repository-link>
