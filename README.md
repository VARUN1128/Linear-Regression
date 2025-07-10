# 🧠 Linear Regression: Predicting Weight from Height

A simple yet powerful deep learning project demonstrating the fundamentals of supervised learning using **Linear Regression**. This project predicts a person's weight based on their height using a clean dataset and a custom-built deep learning model.

> 🚀 Built with TensorFlow & Keras | 📊 Ideal for beginners in AI/ML | 💡 Demonstrates real-world regression use-case

---

## 📌 Project Overview

This project showcases how a basic linear regression model can be implemented from scratch using TensorFlow/Keras. Despite its simplicity, it covers the essential workflow of a deep learning regression pipeline including:

- Data preprocessing and visualization
- Building a neural network with a single dense layer
- Compiling and training the model
- Visualizing loss curves
- Evaluating predictions

---

## 📁 Dataset

We used a publicly available dataset with features:

- `Height (inches)`
- `Weight (pounds)`

### Sample:
| Height | Weight |
|--------|--------|
| 60.2   | 115.1  |
| 65.1   | 130.6  |
| 70.4   | 155.3  |

---

## 🧪 Technologies Used

- Python 3.x
- TensorFlow / Keras
- NumPy
- Matplotlib
- Pandas
- Scikit-learn

---

## 🛠️ How It Works

1. **Data Loading & Cleaning**  
   Dataset is loaded and normalized for better model performance.

2. **Model Architecture**  
   A minimal neural network with:
   ```python
   tf.keras.Sequential([
       tf.keras.layers.Dense(1, input_shape=[1])
   ])
