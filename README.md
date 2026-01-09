# 🧠 Next Word Prediction using Deep Learning (NWP)

This project implements a Next Word Prediction (NWP) system using Deep Learning (LSTM-based model).
Given a sequence of words as input, the model predicts the most likely next word(s) based on learned language patterns.

## 📌 Project Overview

Next Word Prediction is a fundamental Natural Language Processing (NLP) task used in:

- Text auto-completion
- Chatbots
- Search engines
- Language models

In this project:

- A large text dataset is tokenized and converted into word sequences
- An LSTM-based neural network is trained to learn word dependencies
- The trained model predicts the next word for a given input sentence

## 📂 Dataset Information

- Dataset Type: Plain text (.txt)
- Source: Public domain literature (Project Gutenberg)
- Book Used: “The Adventures of Sherlock Holmes” by Sir Arthur Conan Doyle
- Content: Large English text corpus (used for language modeling)
- Purpose: Learn word patterns and contextual relationships

#### ⚠️ Dataset is NOT included in this repository to keep the repo lightweight.

## 🔗 Download Dataset from Kaggle

### 👉 Kaggle Notebook & Dataset Link:
https://www.kaggle.com/code/krishna7504/next-word-prediction

You can download the dataset from the Kaggle notebook and place it inside a data/ folder if running locally.

## 🛠️ Technologies Used

- Python
- TensorFlow & Keras
- NumPy
- Natural Language Processing (NLP)
- LSTM (Long Short-Term Memory

##🧪 Model Workflow

1. Load and clean text data
2. Tokenize text into word sequences
3. Create fixed-length input sequences
4. Train LSTM-based deep learning model
5. Predict next possible word(s) for user input

## 📊 Model Output

- Takes a partial sentence as input
- Predicts top-k most probable next words
- Output improves with higher training epochs

## 📁 Repository Structure
```
├── next_word_prediction.ipynb
├── README.md
├── requirements.txt
├── .gitignore
```

## ▶️ How to Run

1. Clone the repository
2. Install dependencies: pip install -r requirements.txt
3. Download dataset from Kaggle and place it in data/
4. Run the notebook to train or test the model

## 🎯 Future Improvements

- Improve prediction accuracy with larger datasets
- Add Beam Search for better word suggestions
- Build a simple Streamlit UI
