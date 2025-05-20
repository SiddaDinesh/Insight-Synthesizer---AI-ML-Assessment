# 📊  Insight Synthesizer - AI/ML Assessment

# 🧠 Project Overview

This project is a Python-based Insight Synthesizer designed for the Outlaw AI/ML assessment. It analyzes raw user survey feedback and extracts structured insights using NLP techniques. The goal is to automatically group responses into meaningful themes with supporting quotes and sentiment labels.

# 🎯 Objective

Given a list of short-form survey responses, generate a list of Insight Cards:

theme: A concise summary of the feedback topic

quotes: 1–12 feedback quotes supporting that theme

sentiment: An overall tone (positive, neutral, negative)

# 🧰 Tech Stack

Python 3.8+

Hugging Face Transformers

facebook/bart-large-mnli for zero-shot classification

distilbert-base-uncased-finetuned-sst-2-english for sentiment analysis

Jupyter Notebook (or Google Colab compatible)

# 🚀 Features

Zero-Shot Topic Classification using pre-defined themes

Sentiment Analysis per feedback and aggregated per theme

Customizable Confidence Threshold for multi-theme assignment

Formatted Output in JSON structure suitable for Insight Cards

