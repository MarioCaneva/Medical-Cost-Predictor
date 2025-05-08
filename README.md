# Medical Cost Predictor 🧮💸

A simple TensorFlow regression model that predicts individual medical insurance costs based on personal attributes like age, sex, BMI, smoking habits, and region. This project is based on a classic dataset and demonstrates how to build, train, and evaluate a neural network for real-world data.

---

## 📊 Dataset

The dataset is provided by [freeCodeCamp](https://www.freecodecamp.org/), and includes the following features:

- `age`: Age of the individual
- `sex`: Gender (male/female)
- `bmi`: Body Mass Index
- `children`: Number of children covered by insurance
- `smoker`: Whether the individual smokes
- `region`: Residential area in the US
- `expenses`: Medical insurance cost (target variable)

---

## 🧠 Model

- Built using TensorFlow/Keras
- Normalizes numeric input features
- Encodes categorical variables (`sex`, `smoker`, `region`)
- Dense neural network with ReLU activations
- Includes batch normalization, dropout, and early stopping

---

## 📈 Performance

After training, the model achieved a **Mean Absolute Error (MAE) under 3500**, successfully passing the evaluation criteria.

Example prediction vs. actual output:

Predicted: 13765.22, Actual: 13555.00
Predicted: 9263.78, Actual: 10435.20

---

## 🛠️ How to Run

Clone the repository or Run the notebook: Linear_Regression_Health_Costs_Calculator.ipynb


🧪 Technologies Used
Python 🐍

Pandas & NumPy

TensorFlow / Keras

Matplotlib

scikit-learn


MIT License
