# 💱 Forex Price Prediction using Linear Regression

This Jupyter Notebook project predicts the next day's **Forex closing price** using historical price data. It uses basic features like `Open`, `High`, `Low`, and `Volume`, and applies a **Linear Regression** model for forecasting.

---

## 🧠 Objective

- Predict the **next day's closing price** of a selected Forex pair.
- Use historical features to train a **Linear Regression** model.
- Visualize and evaluate model performance.

---

## 🧰 Technologies Used

- Python 3.x
- Jupyter Notebook
- pandas
- yfinance (for live Forex data)
- scikit-learn (for model training & evaluation)
- matplotlib (for visualization)

---

## 📊 Dataset Overview

Historical Forex data was fetched using the [`yfinance`](https://pypi.org/project/yfinance/) API.

**Used Columns:**
- `Open`
- `High`
- `Low`
- `Volume`
- `Close` (used to derive `Target`: next day's Close)

---
