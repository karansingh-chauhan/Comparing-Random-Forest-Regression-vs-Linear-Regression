# Comparing-Random-Forest-Regression-vs-Linear-Regression
This project predicts house prices using two machine learning models: **Linear Regression** and **Random Forest Regression**. The dataset contains various features like number of bedrooms, bathrooms, living area, location, and more.

---

## 📁 Dataset

The dataset includes features such as:
- `bedrooms`, `bathrooms`, `sqft_living`, `floors`
- `condition`, `view`, `waterfront`
- Location features: `street`, `city`, `statezip`
- Target: `price`

---

## 🔧 How the Code Works

1. **Data Loading**
   - The dataset is loaded into a pandas DataFrame.

2. **Preprocessing**
   - Categorical columns (`street`, `city`, `statezip`) are label encoded.
   - Numeric features are scaled using **MinMaxScaler**.
   - The target variable `price` is kept in its original form.

3. **Modeling**
   - Two models are trained:
     - **Linear Regression**
     - **Random Forest Regression**
   - The dataset is split into training and testing sets.

4. **Evaluation**
   - Each model's performance is evaluated using:
     - R² Score (explained variance)
     - RMSE (optional)
   - Model predictions are compared to actual house prices.

---

## 📈 Example Output

```text
Linear Regression R²: 0.19  
Random Forest R²: 0.85
****
