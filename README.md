# uber-ride-cancellation-predictor
A data analysis and machine learning pipeline to identify factors driving Uber ride cancellations and predict future booking failures.

# Uber Rides Analysis & Cancellation Prediction

A Python project focused on analyzing Uber ride data and developing a machine learning model to predict ride cancellations.

## 🤖 Introduction

This repository contains a Python project analyzing Uber rides data and building a model to predict ride cancellations. The project includes data cleaning, exploratory data analysis (EDA), feature engineering, and a machine learning pipeline using scikit-learn. The goal is to identify key factors driving cancellations and provide a predictive tool for operational insights.

## 📂 Repository Contents

- uber_rides_2024.csv (Not included – link to original data below)
- [clean_uber_rides_2024.csv](https://github.com/Srija-Ghosh-05/uber-ride-cancellation-predictor/blob/main/clean_uber_rides_2024.csv) (Cleaned dataset used for modeling)
- [uber-cancellation_prediction_model.ipynb](https://github.com/Srija-Ghosh-05/uber-ride-cancellation-predictor/blob/main/uber-cancellation_prediction_model.ipynb) (Jupyter Notebook with full analysis, plots, and model training)
- [requirements.txt](https://github.com/Srija-Ghosh-05/uber-ride-cancellation-predictor/blob/main/requirements.txt) (Python dependencies)
- [README.md](https://github.com/Srija-Ghosh-05/uber-ride-cancellation-predictor/blob/main/README.md) (This file)

## 📝 Project Overview

### Data Cleaning

- Handles missing values, nulls, and unnecessary columns.
- Creates a target variable is_cancelled.
- Generates features like hour_of_day for modeling.

### Exploratory Data Analysis (EDA)

- Visualizes ride distributions, cancellation reasons, peak cancellation hours, and vehicle-specific patterns.

### Machine Learning Pipeline
- Trains a Decision Tree Classifier to predict if a ride will be cancelled.
- Handles categorical features using one-hot encoding.
- Provides sample predictions with probabilities.

## 📊 Visualizations

Plots are generated inline during notebook execution:

- Distribution of rides by hour.
- Booking status distribution (Cancelled vs Completed).
- Cancellations by vehicle type.
- Peak cancellation hours.

Note: All plots are rendered in the notebook and will appear directly below their corresponding analysis functions.

## 🎯 Key Findings (Executive Summary)

Based on the analysis and model training, the following key trends were identified:

- Cancellations peak sharply between 4 PM and 6 PM (evening rush hour), suggesting that external factors like traffic or driver availability heavily influence ride completion.

- Vehicle type 'A' has a 15% higher cancellation rate than the average across all other vehicle types, indicating a potential issue with routing, pricing, or driver assignment for that category.

## ⚠️ Dataset Notice

The original dataset is not included due to privacy and file size constraints.
The original dataset, Uber Ride Analytics Dashboard, is sourced from the [Kaggle website](https://www.kaggle.com/datasets/yashdevladdha/uber-ride-analytics-dashboard).

The cleaned dataset (clean_uber_rides_2024.csv) is included and can be used for EDA and modeling. If you have access to the original data, you can run the full pipeline starting from clean_and_save_data().

## 📦 Requirements

Install the required Python packages:

<pre> pip install -r requirements.txt </pre>

### Key packages used:

- `pandas` **(v2.1.0)**
- `numpy` **(v1.26.0)**
- `matplotlib` **(v3.8.0)**
- `scikit-learn` **(v1.3.0)**

## 🚀 How to Run

1. Open uber-cancellation_prediction_model.ipynb in Jupyter Notebook or JupyterLab.
2. Run cells sequentially: Data Cleaning $\rightarrow$ EDA $\rightarrow$ Model Training & Prediction.
3. Visualizations will appear directly under their respective function calls.
4. You can test predictions using the sample ride at the end of the notebook.

## 🔗 References

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/user_guide.html)

## ⚖️ License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/Srija-Ghosh-05/uber-ride-cancellation-predictor/blob/main/LICENSE) file in the repository for full details.

## 🤝 Contributing

Collaborations, bug reports, and feature requests are always welcome! This project is open to suggestions on model improvement, feature engineering, and visualization enhancements. Please feel free to open an Issue or submit a Pull Request.

## 📚 Learning Journey
This project was developed as a comprehensive, end-to-end machine learning exercise completed during the CodeChef Machine Learning Course. It served as a practical application of core data science skills, including data cleaning, exploratory analysis, model selection, and performance evaluation.

## 👤 Author

Srija Ghosh

GitHub: [Srija-Ghosh-05](https://github.com/Srija-Ghosh-05)
