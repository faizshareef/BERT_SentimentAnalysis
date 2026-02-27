

# 🎬 BERT Sentiment Analysis with FastAPI & Streamlit

## 🚀 Overview

This project implements a sentiment analysis system using BERT fine-tuned on the IMDB movie review dataset.

The application includes:

- Fine-tuning BERT using PyTorch and Hugging Face Transformers
- REST API built with FastAPI
- Interactive frontend built with Streamlit
- End-to-end NLP model deployment pipeline

The system classifies movie reviews as **Positive** or **Negative**.

---

## 🧠 Model Details

- Base Model: bert-base-uncased
- Task: Binary Sentiment Classification
- Dataset: IMDB Movie Reviews (50,000 samples)
- Training Framework: Hugging Face Trainer API
- Optimizer: AdamW
- Loss Function: CrossEntropyLoss

---

## 🏗️ Project Architecture

User Input (Streamlit UI)
        ↓
FastAPI Backend
        ↓
Fine-Tuned BERT Model
        ↓
Sentiment Prediction (Positive / Negative)

---

## 📦 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/bert-sentiment-analysis.git
cd bert-sentiment-analysis
