# 📊 Twitter Sentiment Analysis using LSTM + CNN

This project implements a hybrid deep learning model combining *LSTM* and *CNN* for *binary sentiment classification* (positive/negative) of Twitter data. The model is trained on the widely-used [Sentiment140](http://help.sentiment140.com/home) dataset and includes end-to-end preprocessing, tokenization, model building, training, evaluation, and visualization.

---

## 📁 Dataset

- *Source*: [Sentiment140](http://help.sentiment140.com/home)
- *File*: training.1600000.processed.noemoticon.csv
- *Columns Used*:
  - sentiment — (0 = negative, 4 = positive) → mapped to (0, 1)
  - text — tweet content

---

## 🔧 Project Structure

```bash
📦 Twitter-Sentiment-LSTM-CNN/
├── data/
│   └── training.1600000.processed.noemoticon.csv
├── notebooks/
│   └── sentiment_model_lstm_cnn.ipynb
├── drive/
│   ├── tokenizer_cnn.pkl
│   ├── lstm_cnn_model.h5
│   └── history_cnn.pkl
├── outputs/
│   └── plots/  # Accuracy, Loss, Confusion Matrix, Error graphs
├── README.md
