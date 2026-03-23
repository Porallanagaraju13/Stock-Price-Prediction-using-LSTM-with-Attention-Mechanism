# 📈 Stock Price Prediction using LSTM + Attention Mechanism

> Predict future stock closing prices with high accuracy using deep learning — LSTM combined with an Attention Mechanism.

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat&logo=python)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red?style=flat&logo=keras)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

---

## 🧠 Overview

This project predicts the **future closing price of stocks** based on historical stock data using a combination of:

- **LSTM (Long Short-Term Memory)** — captures temporal patterns in time-series data
- **Attention Mechanism** — helps the model focus on the most relevant time steps for prediction

This approach significantly improves prediction accuracy over standard LSTM models alone.

---

## 🚀 Features

- 📊 Fetches and preprocesses historical stock data
- 🔁 Implements LSTM + Attention architecture from scratch
- 📉 Visualizes predicted vs actual stock prices
- 📁 Includes project report (PDF) and presentation (PPTX)
- ✅ Requirements file for easy environment setup

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python 3.8+ |
| Deep Learning | TensorFlow / Keras |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Environment | Jupyter Notebook |

---

## 📂 Project Structure

```
Stock-Price-Prediction-using-LSTM-with-Attention-Mechanism/
│
├── Stock_Price_Prediction_using_LSTM_+_Attention.ipynb  # Main notebook
├── requirements.txt                                      # Python dependencies
├── 📄 Project Abstract.txt                               # Project abstract
├── MS AINSI.pdf                                          # Project report
├── MS AINSI.pptx                                         # Presentation slides
└── README.md
```

---

## ⚙️ Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Porallanagaraju13/Stock-Price-Prediction-using-LSTM-with-Attention-Mechanism.git
cd Stock-Price-Prediction-using-LSTM-with-Attention-Mechanism
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Notebook
Open `Stock_Price_Prediction_using_LSTM_+_Attention.ipynb` in Jupyter Notebook or JupyterLab and run all cells.

---

## 📊 How It Works

1. **Data Collection** — Historical stock price data is loaded (Open, High, Low, Close, Volume)
2. **Preprocessing** — Data is normalized using MinMaxScaler and split into train/test sets
3. **Model Architecture** — LSTM layers followed by an Attention layer and Dense output
4. **Training** — Model is trained on historical sequences to predict the next closing price
5. **Evaluation** — Predicted vs actual prices are plotted and RMSE is computed

---

## 📈 Results

The LSTM + Attention model captures stock price trends with improved accuracy over baseline LSTM, producing close-fitting predictions on the test set.

---

## 👤 Author

**Poralla Nagaraju**
- 🎓 B.Tech CSE (AI & ML), JNTUH — 2025
- 📍 Hyderabad, India
- 🔗 [GitHub Profile](https://github.com/Porallanagaraju13)

---

## 📝 License

This project is licensed under the MIT License.
