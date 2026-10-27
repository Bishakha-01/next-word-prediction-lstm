# Next Word Prediction using LSTM

## Overview
This project uses a Long Short-Term Memory (LSTM) neural network to predict the next word in a given text sequence. The model was trained in Google Colab and integrated into an interactive Streamlit web application.

## Features
- Predicts the next word from user-provided text.
- Uses a trained LSTM model for sequence-based language prediction.
- Converts text into numerical sequences using a saved tokenizer.
- Provides a simple interface built with Streamlit.

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Streamlit

## Project Structure
- `app.py` — Streamlit application and prediction logic.
- `lstm_model.h5` — Trained LSTM model.
- `tokenizer.pkl` — Saved tokenizer.
- `max_len.pkl` — Stored sequence-length parameter.
- `requirements.txt` — Python dependencies.

## Run Locally

1. Install Python.
2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Start the application:

   ```bash
   streamlit run app.py
   ```

## Limitations
Predictions depend on the model's training data and vocabulary. The model may produce unexpected results for unfamiliar or incomplete text.

## Author
Bishakha Prasad