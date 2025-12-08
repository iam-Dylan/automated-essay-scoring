# 📝 Automated Essay Scoring 2.0  
A machine learning & NLP project for automatically evaluating essay quality using traditional ML models, deep learning, and large language models.

## 🚀 Overview
This project aims to build an end-to-end **Automated Essay Scoring (AES)** pipeline that can score essays automatically using multiple modeling approaches:

- Exploratory Data Analysis (EDA)
- Machine Learning baseline models
- Deep learning neural networks
- Transformer-based models (DeBERTa)
- Prompt engineering for LLM-based scoring

The project follows the Learning Agency Lab – **Automated Essay Scoring 2.0** challenge.

---

## 📁 Project Structure

```

automated-essay-scoring-main/
│
├── README.md                    # Project description
├── eda.ipynb                    # Data exploration & insights (EDA)
├── model.ipynb                  # ML baseline & deep learning models
├── sub-model.ipynb              # Additional model experiments
├── deberta.ipynb                # Fine-tuning DeBERTa for AES
└── promt-engineering.ipynb      # Prompt engineering for LLM scoring

````

---

## 📊 Features

### 🔍 Exploratory Data Analysis
- Distribution of essay lengths  
- Vocabulary richness  
- Text statistics  
- Label distribution  
- Outlier detection  

### 🤖 Machine Learning Models
Implemented classical ML methods:
- XGBoost  
- LightGBM  
- Random Forest  
- Linear Regression variants  

### 🧠 Deep Learning
- Simple feed-forward neural networks  
- Custom embedding processing  
- Regularization strategies  

### 🔥 Transformer-based Modeling
**DeBERTa** fine-tuned for essay scoring:
- Large transformer backbone  
- Regression head  
- Training with MSE / Smooth L1 loss  

### 💬 LLM Prompt Engineering
Using structured prompts to:
- Evaluate clarity, coherence, grammar  
- Estimate rubric-based scores  
- Compare different prompting strategies

---

## 📦 Installation

```bash
git clone <this-repo>
cd automated-essay-scoring-main
pip install -r requirements.txt
````

(You may create a `requirements.txt` with the dependencies inside notebooks.)

---

## ▶️ Usage

Open the notebooks in order:

1. **eda.ipynb** — Understand the dataset
2. **model.ipynb** — Classical ML + deep learning models
3. **sub-model.ipynb** — Additional experiments
4. **deberta.ipynb** — Fine-tune transformer model
5. **promt-engineering.ipynb** — LLM-based scoring

