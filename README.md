# Type-1-Diabetes-BG-Prediction-XGBoost

Predicting blood glucose levels in Type 1 diabetes (T1D) is of utmost importance due to its direct impact on patient safety, long-term health, and overall quality of life. Maintaining blood sugar within a safe range is critical for preventing life-threatening complications and improving daily diabetes management. One of the most immediate concerns in T1D is preventing hypoglycemia (low blood sugar) and hyperglycemia (high blood sugar). Predicting glucose levels enables timely interventions, such as consuming carbohydrates to prevent a sugar crash or adjusting insulin doses to avoid dangerous spikes.

Accurate blood glucose prediction in Type 1 diabetes is essential for preventing long-term complications such as nerve damage, kidney failure, heart disease, and blindness by maintaining better glycemic control.

Since glucose levels are influenced by multiple factors like diet, stress, and exercise, predictive models help reduce the mental and physical burden on patients and caregivers by providing automated assistance.

## ♨️XGBOOST

XGBoost is a gradient boosting algorithm, which builds an ensemble of decision trees in a sequential manner to predict a target variable (in this case, glucose levels). It is widely used for regression and classification tasks. It works by combining multiple weak learners (typically decision trees) to create a strong model.Each tree in the model corrects the errors made by the previous tree, which helps the model learn from its mistakes and improve its performance. In the context of blood glucose prediction, the objective is to develop a model that can accurately predict the glucose levels based on input features. It works particularly well when the relationships between the input features are non-linear or complex.

The model is configured with hyperparameters like the number of trees(n_estimators=100), learning rate(learning_rate=0.1), and the maximum depth
(max_depth=6) of each tree to control the complexity and performance of the model.

## 🚀 Features
- **Machine Learning-Based Prediction** – Uses XGBoost for high-performance blood glucose forecasting.
- **Data Preprocessing & Feature Engineering** – Handles missing values, normalizes data, and selects important features.
- **Hyperparameter Tuning** – Optimizes model parameters for improved accuracy.
- **Performance Evaluation** – Assesses accuracy using **Mean Absolute Error (MAE) & RMSE**.
- **Scalability** – Can be extended for larger datasets and real-time monitoring.

## ⚙️ Requirements
To run this project, install the following dependencies:

### 📌 Required Libraries
- Python 3.8+
- NumPy
- Pandas
- XGBoost
- Scikit-learn
- Matplotlib
- Seaborn
- 
**📊About The Dataset : HUPA-UCM DIABETES DATASET**

The dataset consists of multiple CSV files, each named with an identifier (e.g., "HUPA0001P.csv" to "HUPA0028P.csv"). These represent individual patient records or data segments.

**Summary of the Data:**

- Time-based dataset: Each row represents a timestamped health measurement.
- Glucose levels: Monitors blood glucose over time.
- Physical activity: Tracks calories burned and steps taken.
- Heart rate: Records fluctuations in heart rate.
- Insulin management: Captures basal insulin rate and bolus insulin delivery.
- Dietary intake: Logs carbohydrate consumption.

## 🙌 Acknowledgments

- This project is inspired by ongoing research in **blood glucose prediction** for Type-1 Diabetes management.  
- Special thanks to **researchers and healthcare professionals** working on improving diabetes forecasting and treatment strategies.  
- Gratitude to the **open-source community** for providing essential libraries such as **TensorFlow, Pandas, Scikit-learn, and Keras**, which made this project possible. 
- Thanks to all contributors who helped refine the model, optimize hyperparameters, and improve performance.  
- Appreciation for **academic research papers and datasets** that provided insights into feature selection and model enhancement.  
- Acknowledgment to the developers of **Jupyter Notebook and Google Colab**, which facilitated interactive model development and experimentation.  

