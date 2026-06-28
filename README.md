# Thai Financial News Sentiment Analysis with Explainability (SHAP)

A Thai NLP project that fine-tunes WangchanBERTa on financial news to classify sentiment (positive/negative/neutral) and explains predictions using SHAP.

## Project Overview

This project analyzes Thai financial news sentiment using a fine-tuned transformer model, then applies SHAP (SHapley Additive exPlanations) to interpret which words influence the model's predictions.

## Results

| Metric | Score |
|--------|-------|
| Test Accuracy | 95.38% |
| Test F1-Score | 95.36% |
| Training Data | 21,190 samples |

## Tech Stack

- **Model**: WangchanBERTa (`airesearch/wangchanberta-base-att-spm-uncased`)
- **Framework**: HuggingFace Transformers, PyTorch
- **Explainability**: SHAP
- **Data Collection**: feedparser, yfinance
- **Language**: Python (Google Colab)

## Project Structure
