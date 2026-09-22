# 🧠 Next Word Prediction (LSTM)

An interactive web application built with **Streamlit** and **TensorFlow / Keras** that predicts the next word in a sequence using a trained Long Short-Term Memory (LSTM) recurrent neural network.

---

## 📌 Features

- **LSTM Deep Learning Model**: Trained to understand sequence context and predict upcoming words.
- **Streamlit Interactive UI**: Fast, responsive web interface for testing text predictions.
- **Includes Notebooks**: Contains Jupyter notebooks with model exploration and training implementations.

---

## 📂 Project Structure

```
Next_word_prediction/
├── app.py                     # Streamlit frontend & prediction logic
├── RNNimplementation.ipynb    # Model exploration and RNN training notebook
├── codefile.ipynb             # Data preprocessing and sequence generation notebook
├── lstm_model (1).h5          # Trained LSTM Keras model weights
├── tokenizer.pkl              # Pickled Keras Tokenizer
├── max_len.pkl                # Pickled maximum sequence length
├── qoute_dataset.csv          # Quotes dataset used for training
├── requirements.txt           # Python dependencies
└── .gitignore                 # Files and folders ignored by Git
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/sakshisingh71/Next_word_prediction.git
cd Next_word_prediction
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit application
```bash
streamlit run app.py
```

---

## 🛠️ Tech Stack

- **Python 3**
- **TensorFlow / Keras**
- **Streamlit**
- **NumPy & Pandas**
