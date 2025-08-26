# 🏠 House Price Prediction

This project predicts house prices using the **Kaggle House Prices - Advanced Regression Techniques** dataset.

## 📂 Files in this repository
- **house_price_prediction.ipynb** → Jupyter/Colab notebook with all code and steps.
- **house_price_model.pkl** → Trained Linear Regression model (ready to load and use).
- **README.md** → Project description.

## 📊 Steps followed
1. Downloaded dataset from Kaggle.
2. Loaded data into Pandas.
3. Selected key features: `GrLivArea`, `BedroomAbvGr`, `FullBath`.
4. Split data into training (80%) and testing (20%).
5. Trained a **Linear Regression** model using scikit-learn.
6. Evaluated using R² Score and RMSE.
7. Visualized **Actual vs Predicted** prices.
8. Saved trained model using Joblib.

## 🚀 How to use
1. Clone/download this repository.
2. Install dependencies:
   ```bash
   pip install pandas scikit-learn matplotlib joblib
