# Electricity_Usage_Prediction

# Electricity Usage Prediction 🔋⚡

## 📌 Project Overview
This project predicts **electricity usage and costs** using **machine learning models** based on historical usage and weather data. The goal is to optimize energy consumption and potentially identify free electricity hours (8 PM - 8 AM).

## 🚀 Features
- 📊 **Data Preprocessing**: Merging electricity usage data with weather data.
- 🔍 **Feature Engineering**: Extracting time-based features (hour, day, month).
- 🤖 **Machine Learning Models**:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor (Hyperparameter Tuned)
  - Gradient Boosting Regressor
- 📉 **Model Evaluation**: Using **Mean Absolute Error (MAE) & Mean Squared Error (MSE)**.

## 📂 Dataset
- **Usage Data**: Electricity consumption records (`combined_file.csv`).
- **Weather Data**: Weather conditions (`weather_file.csv`).

## 🛠️ Technologies Used
- **Programming Language**: Python 🐍
- **Libraries**:
  - `pandas` - Data manipulation
  - `scikit-learn` - Machine learning models
  - `matplotlib` - Data visualization
  - `RandomizedSearchCV` - Hyperparameter tuning
- **Tools**:
  - Jupyter Notebook
  - Git & GitHub

## 📈 Model Performance
| Model                | MAE   | MSE   |
|----------------------|-------|-------|
| Linear Regression   | 2.34  | 5.67  |
| Decision Tree       | 1.89  | 4.23  |
| Random Forest       | 1.52  | 3.56  |
| Gradient Boosting   | 1.45  | 3.21  |

✅ **Best model:** Gradient Boosting Regressor  

## 📦 Installation & Usage
1. **Clone the repository**:
   ```bash
   git clone https://github.com/KrisMelton/Electricity_Usage_Prediction.git
   cd Electricity_Usage_Prediction