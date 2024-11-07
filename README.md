# Used-Car-Price-Prediction

This project employs advanced machine learning techniques, including Extra Trees and Random Forest Regressors, to accurately estimate the prices of used cars. It aims to improve decision-making in the automotive industry by providing precise price predictions, which are valuable for both buyers and sellers in the pre-owned vehicle market.

🔑 Key Features:
* Price Prediction: The system provides an accurate price estimate for used cars, leveraging historical data on various car attributes.
* Feature Importance Analysis: Identifies the main factors that influence a vehicle's resale value, such as age, mileage, fuel type, and transmission.
* High Predictive Accuracy: The model achieves an impressive R² score of 0.92, indicating strong performance in capturing price trends.

🚀 Applications:
* Automotive Sales: Helps dealerships and individual sellers determine competitive pricing for used vehicles.
* Insurance: Assists insurance providers in evaluating depreciation for coverage pricing.
* Financial Services: Supports lenders in making informed loan approvals by providing accurate asset valuation.
   
📊 Dataset:
The dataset used for this project is a comprehensive set of automotive records sourced from Kaggle, with features including car model, year, selling price, current price, mileage, fuel type, transmission, and more.

**Dataset Features:**
* Number of Attributes: 9, including age, mileage, and price.
* Preprocessing Steps: Data cleaning (removal of null and duplicate values), conversion of categorical data into numerical form, and extraction of car age from the year.

🛠️ Technologies and Tools:
* Python: Core language for model development and data processing.
* Scikit-Learn: Used to build and train the machine learning models.
* Pandas & NumPy: For data manipulation and analysis.
* Matplotlib/Seaborn: For visualizing data distributions, model performance, and feature importance.
  
📈 Model Architecture and Training:
The project uses two primary models to predict used car prices:
1. Extra Trees Regressor: Identifies key factors that influence the selling price.
2. Random Forest Regressor: Provides robust and accurate price predictions by averaging multiple decision trees, reducing overfitting.

Key components include:
  * Hyperparameter Tuning: Parameters such as n_estimators, max_depth, min_samples_split, and min_samples_leaf were fine-tuned to optimize model performance.
  * Feature Selection: Key attributes like current price, car age, fuel type, and transmission type were identified as significant predictors.

**Loss Functions:**
The models were evaluated using Mean Absolute Error (MAE) and Mean Squared Error (MSE) to ensure accurate predictions.

🎯 Performance Metrics:
* R² Score: 0.92, indicating high model accuracy.
* Mean Absolute Error (MAE): 1.02, ensuring predictions are close to actual values.
* Error Rate:
  Extra Tree Regressor: 8.14%
  Random Forest Regressor: 2.13%
  
📝 Future Enhancements:
* Deep Learning Models: Experiment with neural network architectures to further improve accuracy.
* Expanded Features: Incorporate additional attributes, such as car condition, location, and market trends, to enhance predictions.
* Web Deployment: Build a user-friendly interface using Flask or FastAPI for real-time price predictions and analysis.
