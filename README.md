
# Spoken Grammar Scoring System 🎤📊

This project builds an automated grammar scoring system for spoken audio responses as part of the **SHL Intern Hiring Assessment 2025**.

## 🔍 Problem Statement
Given spoken audio responses, predict a grammar score reflecting grammatical correctness and fluency.

## 🧠 Approach
1. Transcribed audio using OpenAI Whisper (ASR)
2. Extracted interpretable grammar features:
   - Grammar error count
   - Word count
   - Error rate
3. Trained a Random Forest regression model
4. Evaluated using RMSE and Pearson correlation

## 🛠 Tech Stack
- Python
- Hugging Face Transformers
- Whisper ASR
- LanguageTool (grammar analysis)
- Scikit-learn

## 📊 Results
- Robust pipeline with defensive handling for malformed audio
- Clear interpretability of grammar-based features
- End-to-end reproducible workflow

## 🚀 How to Run
This project is designed to run on Kaggle due to dataset availability.

