---

# 🌦️ Weather Forecasting with TensorFlow 🌦️

### A Collaborative Project by **Nima Jafari** & **Stepan Karapetyan**

---

Welcome to **Weather_Nostradamus**, our deep learning project that harnesses the power of Artificial Neural Networks (ANNs) to predict the weather with impressive accuracy, solely based on historical forecast data.

## 🌟 Project Overview

**Weather_Nostradamus** is more than just a model—it's a digital oracle designed to foresee weather patterns using the knowledge of the past. By analyzing historical weather data, this ANN model learns to make precise predictions for future conditions.

## 🛠️ Getting Started

Ready to let **Weather_Nostradamus** guide your forecasts? Here's how you can get started:

### 1. Save the Model

Download the model from our repository and save it locally on your machine. You'll find it under the `notebooks/` directory, aptly named:

```bash
Weather_Nostradamus.keras
```

### 2. Load the Model

To start predicting, simply load the saved model in your TensorFlow / Jupyter Notebook environment:

```python
import tensorflow as tf

# Load Weather_Nostradamus model
loaded_model = tf.keras.models.load_model('path_to_save/Weather_Nostradamus.keras')
```

And voilà! You’re all set.

## 🎯 Key Features

- **Simplicity:** A straightforward ANN model that’s easy to use and integrate.
- **Accuracy:** Built on robust historical data to ensure reliable forecasts.
- **Portability:** Save and load the model effortlessly, anywhere, anytime.

## 📂 Project Structure

- **notebooks/**: Contains the trained model `Weather_Nostradamus.keras` and Jupyter notebooks with our development and testing processes.
- **data/**: Historical weather data used for training and validation.
- **src/**: Core source code for preprocessing, training, and evaluation.
- If you want even more accurate or extended future predictions, you can import your own historical forecast data in .csv format and retrain the model. Just load your data, run the training script, and use the newly trained model.

---

Thank you for exploring our project!

Happy Forecasting! ☁️☀️🌧️

---

