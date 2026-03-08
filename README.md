# 🏠 House Price Prediction using Linear Regression (From Scratch)

A simple Machine Learning project that implements **Linear Regression from scratch using Python** to predict house prices based on house size.

This project was built to understand the **core mathematics behind machine learning**, including gradient descent and cost optimization.

---

## 🚀 Project Overview

The goal of this project is to predict the **price of a house based on its size (in square feet)** using a Linear Regression model implemented **without using ML libraries** like `scikit-learn`.

Instead, the algorithm is implemented manually using:

* Hypothesis function
* Mean Squared Error cost function
* Gradient Descent optimization

This helps build a **strong conceptual understanding of how ML algorithms work internally**.

---

## 🧠 Machine Learning Concepts Used

This project covers the fundamental concepts behind Linear Regression:

* Hypothesis Function
* Cost Function (Mean Squared Error)
* Gradient Descent
* Parameter Optimization
* Model Training
* Prediction on new data

---

## 📊 Dataset

A small sample dataset was used for demonstration.

| House Size (sqft) | Price (lakhs) |
| ----------------- | ------------- |
| 500               | 50            |
| 700               | 65            |
| 900               | 80            |
| 1100              | 95            |
| 1300              | 115           |
| 1500              | 130           |

---

## 📈 Model

The Linear Regression model follows the equation:

**ŷ = w ⋅ x + b**

Where:

* **x** → house size
* **w** → weight (slope)
* **b** → bias (intercept)
* **ŷ** → predicted price

The parameters **w** and **b** are optimized using **Gradient Descent**.

---

## ⚙️ Technologies Used

* Python 🐍
* NumPy
* Matplotlib
* Jupyter Notebook

---

## 📉 Training Visualization

During training, the model learns by **minimizing the cost function over multiple iterations**.

The project also includes a graph showing:

* **Cost vs Iterations**
* **Regression Line fitting the data**

---

## 🔮 Example Prediction

Example prediction using the trained model:

```
House Size: 1200 sqft
Predicted Price: ~105.94 lakhs
```

---

## 📂 Project Structure

```
linear-regression-from-scratch
│
├── linear_regression_from_scratch.ipynb
└── README.md
```

---

## 🎯 Key Learning Outcomes

This project helped understand:

* How Linear Regression works internally
* How Gradient Descent updates model parameters
* Why cost functions are important
* How machine learning models learn patterns from data

---

## 📌 Future Improvements

Possible future improvements:

* Add multiple features (bedrooms, bathrooms, location)
* Use real-world housing datasets
* Implement feature scaling
* Convert the model into a web application

---

## ⭐ Acknowledgment

This project was inspired by concepts taught in Machine Learning courses by **Andrew Ng** and implemented as a hands-on learning exercise.

---

## 📬 Author

**Hemanth M**

Computer Science Student | Machine Learning Enthusiast
