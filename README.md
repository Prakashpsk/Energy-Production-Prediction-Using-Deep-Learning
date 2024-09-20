# 🌞 Energy Production Prediction Using Deep Learning

## 📖 Introduction
This project aims to predict hourly energy production based on various features such as weather conditions, time, and energy source (e.g., solar) using a deep learning approach. The insights gained from this analysis can drive more efficient energy management and forecasting.

## 🛠️ Skills/Concepts Developed
- Data Preprocessing and Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Deep Learning Techniques (LSTM, GRU)
- Model Evaluation Metrics (MSE, MAE, R²)
- Hyperparameter Tuning

## ❓ Problem Statement
The challenge was to develop a model that accurately predicts energy production based on temporal and meteorological features, facilitating better decision-making in energy management.

## 🌍 Impact of Your Work
The model provides actionable insights into energy production trends, allowing for improved planning and utilization of renewable energy sources. This work can contribute to optimizing energy distribution and enhancing sustainability efforts.

## 🏗️ Modeling
### Steps
1. **Data Preprocessing:**
   - Handled missing values.
   - Converted date-related columns into proper datetime objects.
   - Created additional time-based features.
   - Normalized production values.

2. **Exploratory Data Analysis (EDA):**
   - Visualized production trends based on time features.
   - Investigated relationships between energy source and production.
   - Identified seasonality patterns.

3. **Model Selection and Building:**
   - **Baseline Model:**  Developed a linear regression model and a Random Forest Regressor model.
   - **Deep Learning Model:** Built an LSTM model with:
     - Dense layers for feature processing.
     - Dropout layers for regularization.
     - ReLU activation for hidden layers.
     - Final output layer predicting hourly energy production.

4. **Model Training and Evaluation:**
   - Split data into training and testing sets.
   - Evaluated using MSE, MAE, and R².
   - Monitored training and validation losses to prevent overfitting.

5. **Hyperparameter Tuning:**
   - Tuned hyperparameters using RandomSearchCV.
   - Compared performance before and after tuning.

## 📊 Visualization
- Produced insightful visualizations to illustrate trends and relationships in the data.
- Created box plots to showcase peak production times relative to temperature.

## 🏁 Conclusion
- The Random Forest Regressor outperformed other models, achieving the highest accuracy in predicting energy production.
- Energy production is influenced by seasonal patterns, with significant variations observed throughout the year.
- The model provides reliable predictions that can support energy management efforts.

## 📋 Recommendations
- Further explore advanced deep learning architectures to enhance prediction accuracy.
- Investigate additional features such as humidity and wind speed for better modeling.
- Consider real-time data integration for dynamic energy forecasting.

## 👥 Credits
- Dataset: [intermittent-renewables-production-france.csv](link_to_dataset)
- Special thanks to contributors and mentors.

## 👤 About the Author
[Prakash P.](mailto:prakash2822001@gmail.com) is a Data Scientist with expertise in modeling and machine learning. Feel free to reach out for any questions or collaborations!
