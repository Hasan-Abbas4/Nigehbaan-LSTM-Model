#  Nigehbaan ML Model (LSTM+CNN)

##  Overview

This repository contains the machine learning model used in the Nigehbaan mobile safety application. The model is based on Long Short-Term Memory (LSTM) networks and is designed to detect crash events and abnormal activities using smartphone sensor data such as accelerometer readings.

---

##  Features

* LSTM-based sequence learning model
* Detects crash and abnormal motion patterns
* Uses time-series sensor data (accelerometer)
* Designed for integration with Android applications
* Supports real-time inference using TensorFlow Lite

---

##  Dataset

* Sensor data including:

  * Accelerometer (X, Y, Z)
* Data is preprocessed into sliding windows
* Labels include:

  * Normal activity
  * Crash / abnormal activity

---

## Model Details

* Model Type: LSTM (Recurrent Neural Network)
* Input: Time-series sensor data
* Output: Classification (Normal / Crash)
* Framework: TensorFlow / Keras

---

## How to Run

1. Open the notebook in Google Colab or Jupyter
2. Install dependencies:

```bash
pip install tensorflow numpy pandas
```

3. Run all cells to train the model

---

## Output

* Trained model exported as `.tflite` for Android integration
* Normalization constants saved in JSON

---

##  Integration

The trained model is used in the Nigehbaan Android app for real-time safety monitoring and emergency detection.

---

##  Future Improvements

* Add more activity classes (theft, fall, drowning)
* Improve dataset diversity
* Optimize model for edge devices

---

##  Author

Hasan Abbas
