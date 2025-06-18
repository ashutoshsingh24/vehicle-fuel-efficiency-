# 🚗 Vehicle Fuel Efficiency Prediction

This project uses **linear regression** to predict the **fuel economy (MPG)** of vehicles based on **horsepower**. It also classifies vehicles as **efficient** or **not efficient**, and evaluates the model using **accuracy** and **F1 score**.

---

## 📊 Dataset

- **Source**: `FuelEconomy.csv`
- **Columns**:
  - `Horse Power` — the power output of the engine.
  - `Fuel Economy (MPG)` — actual miles per gallon of the vehicle.

---

## 🔍 Features

- Trains a **Linear Regression** model using scikit-learn.
- Converts regression output into classification (`Efficient` if MPG ≥ 25).
- Calculates:
  - 📉 Mean Squared Error
  - ✅ Accuracy
  - 🎯 F1 Score
- Accepts **user input** to check vehicle info by index.

---

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fuel-efficiency-regression.git
   cd fuel-efficiency-regression
