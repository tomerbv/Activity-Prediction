# Activity Prediction using Wearable Sensor Data

This notebook explores and implements machine learning techniques for classifying physical activities using time-series data collected from wearable fitness devices. The assignment was originally completed during a university course and is now published for educational and portfolio purposes.

## 📊 Dataset

The dataset includes sensor readings from wearable fitness devices, stored in `.dat` files. It contains the following features:

- Timestamp (seconds)
- Activity ID
- Heart Rate (bpm)
- Electrodermal Activity (EDA)
- Temperature (Celsius)
- Accelerometer and Gyroscope (X, Y, Z axes)
- GPS (Latitude, Longitude)

Each row corresponds to a single timestamped sample for a specific user.

## 🔍 Project Overview

The notebook includes:

1. **Data Loading and Preprocessing**
   - Parsing `.dat` files into structured dataframes
   - Handling missing values and feature scaling

2. **Exploratory Data Analysis (EDA)**
   - Visualizing signal distributions and trends
   - Inspecting activity ID distributions

3. **Feature Engineering**
   - Creating time-windowed features
   - Combining data from different sensors

4. **Modeling**
   - Building and training a classification model using deep learning (CNN and/or LSTM)
   - Using Keras/TensorFlow for model definition and training
   - Evaluating performance using accuracy, confusion matrix, and F1 score

5. **Results**
   - Includes final training metrics, model accuracy, and plots from evaluation

## 📈 Results

The notebook includes all intermediate results, model training output, and final evaluation metrics.

## 🛠 Requirements

- Python 3.x
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- tensorflow or keras

To install dependencies:

```bash
pip install -r requirements.txt
