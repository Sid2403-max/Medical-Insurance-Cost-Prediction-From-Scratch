# Medical Insurance Cost Prediction (R²: 0.8653)

### 🚀 Overview
A Multiple Linear Regression model built from scratch using the **Normal Equation** to predict individual medical insurance charges based on demographic and health indicators.

### 🧠 The Math Behind the Model
Unlike standard library calls, this implementation uses the **Normal Equation**:
$$\beta = (X^T X)^{-1} X^T y$$
This approach avoids iterative gradients and provides an exact analytical solution for the weights.

### 🛠 Key Features & Engineering
* **Interaction Terms:** Implemented `BMI * Smoker` logic to capture synergistic health risks, boosting accuracy from 0.78 to 0.86.
* **Categorical Encoding:** Handled 'Region' and 'Sex' using One-Hot and Binary encoding.
* **Matrix Optimization:** Forced float64 precision to ensure matrix invertibility during the Normal Equation process.

### 📊 Results
* **R² Score:** 0.8653

