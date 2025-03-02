# 🏡 House Price Prediction using Gradient Boosting

This repository presents a **Proof of Concept (PoC)** for predicting **house prices** using the **Gradient Boosting Regressor (GBR)**. The dataset is **synthetically generated** to demonstrate how machine learning can model real-world price prediction problems.

## 🚀 Project Overview
This PoC uses **Gradient Boosting**, a powerful ensemble learning method, to predict house prices based on various factors such as:

- **House Size (m²)**
- **Number of Bedrooms**
- **Number of Garage Spaces**
- **House Age**
- **Location (Big City or Not)**

The model is evaluated using:
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **Relative MSE (% of the average price)**
- **R² Score (Coefficient of Determination)**

## 📌 Dataset (Synthetic Data)
Since this is a PoC, the dataset is **generated randomly** but follows logical pricing patterns:

- **Larger houses** tend to have higher prices.
- **More bedrooms and garage spaces** increase house value.
- **Older houses** tend to be cheaper.
- **Houses in big cities** have a price premium.

## 🛠️ Installation
To run this project, install the required dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## 📜 Code Implementation

- Check in notebook (Colab): ()


## 📊 Model Performance
Expected results:

- **MSE**: ~3.6 billion (due to high-value pricing)
- **RMSE**: ~R$60,000 (average error per house)
- **Relative MSE**: ~0.4% (very low, indicating great accuracy)
- **R² Score**: ~0.97 (97% of price variation is explained by the model)

## 🔍 Observations
✅ The model successfully learns patterns between house attributes and pricing.  
✅ The **low RMSE and high R² score** indicate a very precise model.  
✅ The **relative MSE is very small**, meaning errors are minimal.  
✅ **Big cities significantly increase house prices**, as expected.  

## 🔧 Possible Improvements
🔹 **Include more features**, like property type, location rating, or nearby schools.  
🔹 **Optimize hyperparameters**, such as increasing `n_estimators` or reducing `learning_rate`.  
🔹 **Compare with other models**, such as **XGBoost** or **Random Forest**.  
🔹 **Use real-world data**, such as datasets from Kaggle or open-source repositories.  

## 📜 License
This project is licensed under the **MIT License**. Feel free to use and modify it.

## 🤝 Contributing
If you'd like to contribute, feel free to **fork the repo** and submit a **pull request**. Let's improve this PoC together! 🚀

---
**Developed by [Mike Niner Bravog](https://github.com/mikeninerbravog)**  
