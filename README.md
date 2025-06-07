# Air Pollution Prediction using Machine Learning 🌫️🤖

This project aims to predict air pollution levels using machine learning techniques by analyzing historical air quality data, meteorological conditions, and traffic-related indicators. The system is implemented as a Django-based web application with real-time prediction and visualization features, helping stakeholders make informed environmental and health decisions.

## 🚀 Project Overview

Air pollution is a major global concern impacting public health and the environment. Traditional monitoring systems are expensive and geographically limited. This project proposes a scalable and cost-effective solution using supervised machine learning algorithms to forecast air quality levels like PM2.5, NO₂, and O₃.

The web platform supports three roles:
- **Admin**: User authorization
- **Service Provider**: Dataset management, model training/testing
- **Remote User**: Pollution prediction based on inputs

## 🧠 Machine Learning Models Used
- Decision Tree Classifier
- Random Forest
- Gradient Boosting
- K-Nearest Neighbours (KNN)
- Logistic Regression
- Naïve Bayes
- Support Vector Machine (SVM)

## 🛠️ Tech Stack

| Component       | Technology        |
|----------------|-------------------|
| Language        | Python            |
| Backend         | Django            |
| Frontend        | HTML, CSS, JavaScript |
| Database        | MySQL (via WAMP)  |
| ML Libraries    | scikit-learn, pandas, NumPy |
| Server          | WAMP              |

## 🔍 Features

- Predict air quality index (AQI) using historical and real-time data.
- Dynamic visualization of pollution levels.
- Downloadable reports for trained datasets.
- User authentication and role-based access.
- Admin approval workflow.

## 📊 Data Sources

- Historical air quality datasets
- Meteorological data (temperature, humidity, wind speed)
- Traffic indicators

## 🖥️ How to Run Locally

1. **Clone the Repository**
    ```bash
    git clone https://github.com/your-username/air-pollution-prediction-ml.git
    cd air-pollution-prediction-ml
    ```

2. **Set up MySQL Database**
    - Start WAMP server
    - Create a database named: `prediction_of_air_pollution`
    - Import the provided `.sql` file (if available)

3. **Create Virtual Environment & Install Requirements**
    ```bash
    python -m venv venv
    source venv/bin/activate  # or venv\Scripts\activate for Windows
    pip install -r requirements.txt
    ```

4. **Run Server**
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    python manage.py runserver
    ```

5. **Visit in Browser**
    ```
    http://127.0.0.1:8000/
    ```

## 📁 Folder Structure
├── Remote_User/
├── Service_Provider/
├── templates/
├── static/
├── db.sqlite3
├── manage.py
└── prediction_of_air_pollution/



## ✅ Testing Strategy

- Unit Testing
- Integration Testing
- User Acceptance Testing
- Output and Validation Testing

## 📌 Future Enhancements

- Integrate with live IoT sensor data
- Deploy to cloud platforms (AWS, GCP)
- Add LSTM or other deep learning models for time-series analysis
- Mobile app support

## 🙌 Acknowledgements

- Department of AI & ML, CMR Institute of Technology
- World Health Organization reports on AQI
- Public datasets from government air quality and weather monitoring portals

## 📃 License

This project is for academic and educational use only.

---

*Let’s build smarter cities with cleaner air! 💨*
