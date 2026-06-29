# 🏠 Airbnb Price Prediction

## Overview
Airbnb Price Prediction is an end-to-end Machine Learning project that predicts the rental price of Airbnb listings based on various property features. The application enables users to enter listing details through a web interface and receive an estimated price instantly. This project demonstrates the complete machine learning lifecycle, including data preprocessing, model training, evaluation, and deployment using Flask.

---

## Features
- Predict Airbnb rental prices
- Data preprocessing and feature engineering
- Exploratory Data Analysis (EDA)
- Multiple regression model training
- Model evaluation and selection
- Interactive Flask web application
- User-friendly interface
- Deployment-ready project structure

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- CatBoost
- XGBoost
- Flask
- HTML
- CSS
- Git

---

## Project Structure

```
Airbnb-Price-Prediction/
│
├── Artifacts/
├── Notebook_Experiments/
├── src/
├── static/
├── templates/
├── app.py
├── requirements.txt
├── setup.py
└── README.md
```

---

## Installation

### Clone the Repository

```bash
git clone <repository-url>
cd Airbnb-Price-Prediction
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows

```bash
venv\Scripts\activate
```

Linux/Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Application

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

## Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Model Deployment
8. Price Prediction

---

## Machine Learning Models

- CatBoost Regressor
- XGBoost Regressor
- Random Forest Regressor
- Linear Regression (Baseline)

The best-performing model is selected based on evaluation metrics such as:
- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## Input Features

The prediction model considers features such as:

- Property Location
- Room Type
- Number of Bedrooms
- Number of Bathrooms
- Accommodates
- Amenities
- Availability
- Review Scores
- Other Listing Attributes

---

## Future Improvements

- Real-time data integration
- Interactive dashboards
- Cloud deployment
- Advanced feature engineering
- Model monitoring and retraining

---

## Author

Krishna Shree

---

## License

This project is developed for educational and learning purposes.
