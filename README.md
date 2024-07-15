# RainPredictorML

## Project Overview
The RainPredictorML project aims to predict the probability of next-day rain in Australia using a variety of machine learning techniques. This project explores the application of Logistic Regression, Convolutional Neural Networks (CNN), Gradient Boosting Trees (XGBoost), Support Vector Classifier (SVC), and Decision Tree Classifiers (DTC) to address the challenge of rain forecasting.

## Motivation
Accurate weather predictions can significantly impact both daily life and broader economic activities. By using various machine learning techniques, this project aims to enhance the predictive accuracy of meteorological forecasts, focusing on rain prediction.

##  Key Findings
- **Logistic Regression** displayed conservative predictions for next day rain, likely due to the class imbalance where instances of no rain were more common.
- **CNNs** faced challenges with the imbalanced dataset, leading to suboptimal performance.
- **XGBoost** demonstrated high recall on the training set but experienced difficulties in generalizing to unseen data.
- **SVC** showed consistent performance with both default settings and SMOTE-enhanced techniques.
- **Decision Trees** when coupled with SMOTE for addressing class imbalance, achieved the highest recall rates.
- **Scability Challenges** Conducting extensive hyperparameter tuning via grid search cross-validation was limited by the dataset's considerable size, pointing to scalability and computational efficiency as areas for further improvement.


## Technologies Used
- **Programming Language:** Python 3.x
- **Libraries:** NumPy, Pandas, Scikit-Learn, XGBoost, TensorFlow/Keras
- **Data handling and visualization:** Matplotlib, Seaborn
