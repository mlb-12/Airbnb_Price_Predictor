# 🏠 Airbnb Price Prediction

A machine learning web application that predicts the estimated nightly price of an Airbnb listing based on its location, room type, availability, and other listing characteristics.

The application is built using **Python, Scikit-learn, Pandas, and Streamlit** and provides an interactive interface for entering listing details and obtaining a price prediction.

## 🚀 Live Demo

**Try the application here:** [(https://airbnbpricepredictor-hainm5wh4uvhdqm3edk6xp.streamlit.app/)]

## ✨ Features

* Predicts the estimated nightly price of an Airbnb listing.
* Accepts geographical coordinates (latitude and longitude).
* Supports different neighbourhood groups in New York City.
* Supports multiple room types.
* Considers minimum nights, number of reviews, and reviews per month.
* Uses host listing counts and annual availability as input features.
* Provides an interactive web interface built with Streamlit.

## 🛠️ Technologies Used

* **Python** — Programming language
* **Pandas** — Data manipulation and preprocessing
* **Scikit-learn** — Machine learning and model training
* **Streamlit** — Interactive web application
* **Joblib** — Saving and loading the trained machine learning model

## 📂 Project Structure

```text
airbnb-price-prediction/
│
├── app.py
├── rental_final_model.joblib
├── requirements.txt
└── README.md
```

## 📊 Dataset

The project uses the New York City Airbnb dataset containing information about Airbnb listings.

The dataset includes information such as:

* Neighbourhood group
* Room type
* Latitude and longitude
* Minimum nights
* Number of reviews
* Reviews per month
* Host listing count
* Availability throughout the year
* Listing price

The listing price is the target variable that the regression model learns to predict.

## 🤖 Machine Learning Model

The project uses regression algorithms to estimate Airbnb nightly prices.

The model development process includes:

1. Data loading and exploration.
2. Data preprocessing and missing-value handling.
3. Numerical feature scaling.
4. Categorical feature encoding.
5. Training and evaluating regression models.
6. Hyperparameter tuning.
7. Saving the selected model for deployment.

The final trained model is loaded by the Streamlit application to generate predictions for new listings.

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/mlb-12/REPOSITORY-NAME.git
```

Replace `REPOSITORY-NAME` with your actual GitHub repository name.

### 2. Navigate to the project directory

```bash
cd REPOSITORY-NAME
```

### 3. Create a virtual environment (optional)

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 5. Run the application

```bash
python -m streamlit run app.py
```

Streamlit will provide a local address where you can open the application in your browser.

## 🌐 Deployment

The application can be deployed using Streamlit Community Cloud.

General steps:

1. Push the project files to GitHub.
2. Open Streamlit Community Cloud.
3. Connect your GitHub account.
4. Select the repository and `app.py`.
5. Deploy the application.
6. Add the generated public application URL to the **Live Demo** section above.

## ⚠️ Disclaimer

This project is intended for educational and demonstration purposes. Predictions are estimates based on the dataset and trained model. Actual Airbnb prices may vary depending on demand, seasonality, location, property condition, and other factors.

## 👩‍💻 Author

**GitHub:** [mlb-12](https://github.com/mlb-12)

---


