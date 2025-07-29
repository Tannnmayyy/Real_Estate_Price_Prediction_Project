# Real Estate Price Prediction using Machine Learning

This project predicts real estate prices using machine learning algorithms. The pipeline includes data preprocessing, outlier removal, feature engineering, encoding, model training, evaluation, and optimization.

---

## Project Overview

- Developed a regression model to predict house prices using features like area, number of bedrooms, bathrooms, and location.
- Handled missing values, removed outliers, and engineered relevant features for improved model performance.
- Tested and compared multiple regression algorithms to select the best-performing model using evaluation metrics and cross-validation. 
- **Libraries**: pandas, numpy, matplotlib, scikit-learn

---

## Data Preprocessing & Feature Engineering

- **Missing Values**: Cleaned or dropped missing data appropriately.
- **Outlier Removal**: Used the **Z-Score method** to eliminate extreme values in numerical columns such as square footage and price.
- **Feature Engineering**:
  - Extracted `bhk` from the `size` column.
  - Created `price_per_sqft` feature.
- **Categorical Encoding**: Applied **One Hot Encoding** for columns like `location` and `availability`.

---

##  Model Optimization

- **K-Fold Cross Validation** used to ensure model generalization.
- **GridSearchCV** for hyperparameter tuning on models like Linear Reg, Ridge, Lasso, and Random Forest.

---

