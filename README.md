# Car-Selling-Price-Prediction 
Trained ai model to predict cars selling price \
tried both linear regression model and LightGBM model


## 📊 Dataset

- **Source:** [Kaggle - Car Details Dataset](https://www.kaggle.com/datasets)
- **Features:**
  - `name`, `year`, `km_driven`, `fuel`, `seller_type`, `transmission`, `owner`
  - `mileage`, `engine`, `max_power`, `seats`, `torque`
  - `selling_price` (target variable)

## 🔧 Preprocessing

- Handled missing values and inconsistent formats
- Extracted numerical values from columns like `torque`, `mileage`, `engine`, and `max_power`
- Encoded categorical variables
- Split torque into `torque_value` and `rpm`

## 🤖 Model

- **Algorithm Used:** Linear Regression (can be extended to Random Forest, XGBoost, etc.)
- **Evaluation Metrics:**
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score
