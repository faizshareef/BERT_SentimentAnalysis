

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

## 🛠️ Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- FastAPI
- Streamlit
- Uvicorn

## Install Dependencies
 
 -pip install torch transformers datasets fastapi uvicorn streamlit requests

---
 
## Project Outputs

<img width="1024" height="615" alt="sent_output1" src="https://github.com/user-attachments/assets/4ace3284-c501-43a8-8c0a-c620bb8a94dc" />

<img width="1009" height="560" alt="sent_output2" src="https://github.com/user-attachments/assets/fe9320c9-6fa5-49de-b6d7-2d6ae1bc1868" />



