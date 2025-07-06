# 🏡 SVR-Based House Price Prediction (California Housing)

This mini-project uses **Support Vector Regression (SVR)** to predict house prices using real-world data from California.

## 📊 Dataset
- Source: `sklearn.datasets.fetch_california_housing`
- Features: 8 (we used `MedInc` for this demo)
- Target: Median House Price

## 🧠 Model Details
- Algorithm: SVR (RBF kernel)
- Feature Used: Median Income (`MedInc`)
- Feature Scaling: `StandardScaler`
- Hyperparameters: C=100, epsilon=0.1

## 📈 Evaluation
- **R² Score**: 0.443
- **Mean Squared Error**:  0.730


This shows ~44% of house price variance is explained by income alone — solid for a single-feature model.

## 📉 Output Visualization

![SVR Prediction Plot](images/result_plot.png)

## 🧪 How to Run

```bash
# Install dependencies
pip install -r requirements.txt

# Open notebook
notebooks/svr_model.ipynb
