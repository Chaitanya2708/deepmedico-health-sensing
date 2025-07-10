# DeepMedico™ Health Sensing

This project focuses on classifying breathing irregularities (Normal, Hypopnea, Obstructive Apnea) from physiological signals (Nasal Airflow, Thoracic Movement, SpO₂) using deep learning models.

## Features
- Signal visualization (`vis.py`)
- Signal cleaning (`clean_signals.py`)
- Dataset creation (`create_dataset.py`)
- Model training with Leave-One-Participant-Out Cross-Validation:
  - 1D CNN
  - 1D Conv-LSTM

## Requirements
Install dependencies:
pip install -r requirements.txt
# Visualize signals
python vis.py --sleep

# Clean signals
python clean_signals.py

# Create dataset
python create_dataset.py

# Train CNN model
python models/cnn_model.py

# Train Conv-LSTM model
python models/conv_lstm_model.py
