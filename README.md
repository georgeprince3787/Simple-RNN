# IMDB Sentiment Analysis using Simple RNN

This project is a Deep Learning Natural Language Processing (NLP) application that classifies IMDB movie reviews as **Positive** or **Negative**. It uses a Simple Recurrent Neural Network (RNN) built with TensorFlow/Keras and includes an interactive Streamlit web app for live predictions.

## 📌 Features
- **Simple RNN Architecture**: Built using TensorFlow/Keras.
- **IMDB Dataset**: Trained on the classic IMDB movie review dataset.
- **Streamlit Web App**: An interactive UI (`main.py`) where users can input a movie review and get an instant sentiment prediction.
- **Model Saving**: The trained model is saved as `simple_rnn_imdb.h5` for quick inference without retraining.

## 📂 Project Structure
- `main.py`: The Streamlit web application code.
- `simpleRNN.ipynb`: Jupyter Notebook containing the model training and evaluation code.
- `embedding.ipynb`: Notebook exploring word embeddings.
- `simple_rnn_imdb.h5`: The saved trained model weights.
- `.venv/`: Virtual environment (Ignored by Git).

## 🚀 How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/georgep3787/simple-rnn.git
cd simple-rnn
