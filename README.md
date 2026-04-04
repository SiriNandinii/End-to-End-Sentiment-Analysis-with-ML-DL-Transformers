# 📊 Sentiment Analysis of Glassdoor Reviews

A complete end-to-end NLP project that performs sentiment analysis on Glassdoor job reviews using Classical Machine Learning, Deep Learning, and Transformer-based models.

---

## 🧠 Overview

This project analyzes employee reviews and classifies them as positive or negative sentiment. It compares multiple modeling approaches to understand their effectiveness on large-scale, real-world text data.

The pipeline covers:
- Data preprocessing
- Feature engineering
- Model training
- Evaluation using multiple metrics
- Visual comparison of results

---

## 📂 Dataset

- **Source:** Glassdoor Job Reviews Dataset (Kaggle)
- **Size:** 800,000+ reviews
- **Key fields used:**
  - `headline`
  - `pros`
  - `cons`
  - `overall_rating` (used to derive binary sentiment labels)

---

## ⚙️ Project Pipeline

### 🔹 Phase 1: Setup
- Google Drive integration
- Folder structure creation

### 🔹 Phase 2: Data Loading
- Load dataset from Kaggle
- Initial inspection and cleaning

### 🔹 Phase 3: Preprocessing
- Text cleaning and normalization
- Binary sentiment conversion from `overall_rating`
- Train-test split

### 🔹 Phase 4: Feature Engineering
- TF-IDF vectorization for classical ML models
- Integer tokenization for deep learning models
- WordPiece/BPE tokenization for transformer models

### 🔹 Phase 5: Classical ML Models
- Naïve Bayes
- Logistic Regression
- Linear SVM

### 🔹 Phase 6: Deep Learning Models
- CNN
- LSTM
- GRU

### 🔹 Phase 7: Transformer Models
- BERT
- RoBERTa
- DistilBERT

### 🔹 Phase 8: Model Comparison
- Visual comparison of all models
- Performance ranking
- Heatmaps and grouped bar charts

---

## 🤖 Models Used

### 🔹 Classical Machine Learning
- Naïve Bayes
- Logistic Regression
- Linear SVM

### 🔹 Deep Learning
- Convolutional Neural Network (CNN)
- Long Short-Term Memory (LSTM)
- Gated Recurrent Unit (GRU)

### 🔹 Transformers
- BERT
- RoBERTa
- DistilBERT

---

## 📊 Evaluation Metrics

Each model is evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score

---

## 📈 Visualizations

The project includes clean and informative visual comparisons:
- Metric-wise bar graphs
- Grouped model comparison charts
- Performance heatmap

These help in understanding model strengths and trade-offs.

---

## 🏆 Results

- Transformer models achieved the highest performance overall
- Deep learning models performed competitively
- Classical models provided strong baselines with significantly faster training times

Final rankings are saved and visualized for easy comparison.

---

## 📁 Project Structure

```
NLP_Project/
│
├── datasets/
├── models/
├── results/
└── source code.ipynb
```

---

## 🚀 How to Run

1. Open the notebook in Google Colab
2. Mount Google Drive
3. Run each phase sequentially
4. Outputs will be saved automatically to Drive

---

## 💡 Key Highlights

- Handles a large-scale, real-world dataset (800K+ reviews)
- Covers the full NLP pipeline from raw text to model evaluation
- Benchmarks 9 models across 3 distinct paradigms
- Includes advanced visualization techniques
- Designed to be modular and restart-safe for long Colab sessions

---

## 📌 Future Improvements

- Hyperparameter tuning
- Ensemble models
- Real-time deployment via REST API
- UI dashboard for live sentiment predictions

---

## 👨‍💻 Author

**Siri Nandini Alanka**

---

## ⭐ Acknowledgements

- [Kaggle](https://www.kaggle.com) — Glassdoor Reviews Dataset
- [Hugging Face](https://huggingface.co) — Transformer models and tokenizers
- [Scikit-learn](https://scikit-learn.org) — Classical ML and evaluation metrics
- [PyTorch](https://pytorch.org) — Deep learning framework
