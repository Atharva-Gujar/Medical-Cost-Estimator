# Medical Cost Estimator
 We preprocessed the data by handling missing values, encoding categorical variables, and scaling features. We then engineered features using PolynomialFeatures, trained a Random Forest model, optimized hyperparameters with GridSearchCV, and evaluated the model's performance, achieving an R2 score of 0.878.

Data Preprocessing:

Loaded and explored the dataset.

Handled missing values and outliers.

Converted categorical variables using One-Hot Encoding.

Scaled the features using StandardScaler.

Feature Engineering:

Applied PolynomialFeatures to create interaction terms.

Generated new features and ensured data was prepared for model training.

Modeling:

Built and trained a baseline Random Forest model.

Evaluated performance using Mean Squared Error (MSE) and R2 score.

Hyperparameter Tuning with GridSearchCV:

Performed hyperparameter optimization to find the best Random Forest settings.

Addressed errors related to invalid parameters (e.g., "max_features" set to 'auto').

Model Performance Evaluation:

Evaluated the model using MSE and R2 after hyperparameter tuning.

Achieved an optimized Random Forest model with an R2 score of 0.878.

Model Exporting:

Prepared to save the optimized model using joblib for future use or deployment.

