# 🧠 AI Generated Text Detection using Deep Learning

This project detects whether a given text is **AI-generated** or **human-written** using deep learning models.  
It leverages NLP techniques, text embeddings, and classification models to analyze input text and predict its origin.

---

## 🚀 Features
- Classifies text as **AI-written** or **Human-written**.
- Uses **TensorFlow/Keras** with LSTM and Conv1D layers for sequence modeling.
- Implemented both CNN + BiLSTM and DistilBERT-based transformer models for comparison.
- Integrates **sentence-transformers** for advanced text embeddings.
- Evaluation metrics include accuracy, confusion matrix, and classification report.

---

## 🛠 Tech Stack
- **Languages:** Python 3  
- **Libraries:** TensorFlow, Keras, TensorFlow Text, Sentence Transformers, Pandas, NumPy  
- **Dataset:** AI vs Human-written essays dataset (Kaggle-based sources)

---

## ⚙️ Installation
Clone the repository and install required dependencies:

```bash
git clone https://github.com/your-username/ai-text-detector.git
cd ai-text-detector
pip install -r requirements.txt

