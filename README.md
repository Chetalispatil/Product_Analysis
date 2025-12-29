### Product_Analysis

An end-to-end AI-powered Product Review Analysis system that scrapes e-commerce reviews, performs BERT-based sentiment analysis, extracts aspect-level opinions, generates visual insights, and exposes functionality through a FastAPI REST API.

## Project Description

This project analyzes customer product reviews to understand:

Overall customer sentiment

Aspect-wise feedback (quality, price, delivery, performance, etc.)

Confidence scores using Transformer models

Actionable business insights through analytics and visualizations

It supports both batch analysis of product reviews and real-time API-based review analysis.

## Features

# Amazon Review Scraper

Automatically detects platform

Uses demo data if scraping fails

# BERT-Based Sentiment Analysis

Uses nlptown/bert-base-multilingual-uncased-sentiment

Predicts sentiment, star rating & confidence

# Aspect-Based Sentiment Analysis

Extracts opinions on:

Quality

Price

Delivery

Performance

Design

Customer Service

Features

# Data Visualization Dashboard

Sentiment distribution

Rating vs sentiment

Aspect frequency

Confidence score distribution

Positive & negative word clouds

# Analytics & Insights

Overall statistics

Key strengths and weaknesses

Actionable recommendations

# Export Results

CSV

JSON

Text summary report


# Output Files
File Name	Description
review_analysis.csv	Review-level results
review_analysis.json	Detailed structured data
summary_report.txt	Human-readable summary

# Insights Generated

Overall sentiment distribution

Most discussed product aspects

Key strengths and weaknesses

Customer satisfaction trends

Improvement recommendations


# Author
Chetali Patil
B.Tech – Computer Science
