# 📱 Nigehbaan ML Model (LSTM+CNN)

##  Overview

This repository contains the complete machine learning pipeline used in the Nigehbaan mobile safety application. It includes data cleaning, preprocessing, merging of datasets, and training of a Long Short-Term Memory (LSTM) model to detect crash events and abnormal activities using smartphone sensor data.

---

##  Features

* End-to-end ML pipeline (data → preprocessing → model training)
* Data cleaning and preprocessing of raw sensor data
* Merging multiple datasets for improved training quality
* LSTM-based sequence learning model
* Detects crash and abnormal motion patterns
* Designed for real-time mobile safety applications
* Supports TensorFlow Lite conversion for Android integration

---

##  Dataset Processing

The project includes:

* Cleaning raw sensor data (handling noise, missing values)
* Merging multiple datasets into a unified format
* Feature selection (accelerometer X, Y, Z)
* Sliding window technique for time-series data
* Label encoding for classification

---

##  Model Details

* Model Type: LSTM (Recurrent Neural Network)
* Input: Time-series accelerometer data
* Output: Classification (Normal / Crash / Abnormal Activity)
* Framework: TensorFlow / Keras

---

##  How to Run

1. Open the notebook in Google Colab or Jupyter
2. Install dependencies:

```bash
pip install tensorflow numpy pandas
```

3. Run all cells step-by-step:

   * Data cleaning
   * Dataset merging
   * Preprocessing
   * Model training

---

##  Output

* Trained model exported as `.tflite` for Android integration
* Processed dataset ready for training
* Normalization constants saved in JSON

---

##  Integration

The trained model is integrated into the Nigehbaan Android application for real-time crash detection and safety monitoring using smartphone sensors.

---

##  Future Improvements

* Add more activity classes (theft, fall, drowning)
* Improve dataset diversity and balance
* Apply model optimization (quantization/pruning)
* Real-time streaming data pipeline

---

##  Author

Hasan Abbas

