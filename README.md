# Air Quality Index (AQI) Prediction System

![Python](https://img.shields.io/badge/Python-3.7%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-2.0%2B-green?style=for-the-badge&logo=flask&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-150458?style=for-the-badge&logo=pandas&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

## 📖 Overview

In an era where environmental awareness is paramount, monitoring air quality has become a critical necessity for public health and urban planning. This **Air Quality Index (AQI) Prediction System** is a cutting-edge Machine Learning application designed to forecast air quality levels with high precision. By analyzing key environmental parameters—such as Particulate Matter (PM 2.5), ground-level ozone, carbon monoxide, sulfur dioxide, and nitrogen dioxide—the system provides actionable insights into air pollution trends.

The core of this application consists of a robust **Random Forest Regression** model, trained on extensive historical dataset records to understand complex non-linear relationships between weather conditions and air quality. Whether for researchers, environmentalists, or general users concerned about their local atmosphere, this tool serves as a reliable platform for real-time AQI assessment. The web interface is engineered for simplicity and speed, ensuring that complex data science processes are accessible through a user-friendly experience.

## 🚀 Key Features

*   **Advanced ML Algorithms**: Utilizes the **Random Forest Regressor**, a powerful ensemble learning method, to deliver highly accurate and stable AQI predictions by averaging multiple decision trees.
*   **Interactive Web Interface**: A sleek, responsive frontend built with **HTML5** and **CSS3**, powered by **Flask**, allowing users to interact with the model seamlessly.
*   **Batch Prediction Capability**: sophisticated data processing pipeline that can ingest CSV files (e.g., `real_2018.csv`), process the data using **Pandas**, and generate bulk predictions instantly.
*   **Scalable Architecture**: Designed with deployment in mind, featuring a `Procfile` for easy integration with cloud platforms like Heroku, ensuring the app can scale to meet user demand.

## 🛠️ Technologies & Tools Used

The project is built using a comprehensive stack of modern data science and web development tools:

| Category | Technologies |
| :--- | :--- |
| **Programming Language** | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) |
| **Web Framework** | ![Flask](https://img.shields.io/badge/-Flask-000000?style=flat&logo=flask&logoColor=white) |
| **Machine Learning** | ![Scikit-Learn](https://img.shields.io/badge/-Scikit%20Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white) ![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white) |
| **Data Processing** | ![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas&logoColor=white) |
| **Frontend** | ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) |
| **Deployment** | ![Gunicorn](https://img.shields.io/badge/-Gunicorn-499848?style=flat&logo=gunicorn&logoColor=white) ![Heroku](https://img.shields.io/badge/-Heroku-430098?style=flat&logo=heroku&logoColor=white) |

## 📂 Project Directory Structure

```plaintext
AQI_Deployment/
├── static/                  # CSS, JavaScript, and image assets
├── templates/               # HTML templates for the UI (home.html, result.html)
├── app.py                   # Main Flask application logic and routing
├── random_forest_regression_model.pkl  # Pre-trained ML model file
├── real_2018.csv            # Sample dataset for testing predictions
├── requirements.txt         # Project dependencies and libraries
├── Procfile                 # Heroku deployment configuration
├── LICENSE                  # License information
└── README.md                # Project documentation
```

## ⚙️ Installation & Usage

Follow this guide to set up the project on your local machine.

### 1. Clone the Repository
```bash
git clone <repository_url>
cd AQI_Deployment
```

### 2. Set Up a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Application
```bash
python app.py
```

### 5. Access the Interface
Open your browser and navigate to `http://127.0.0.1:5000/` to start using the prediction system.

## 🤝 Contribution
Contributions are welcome! If you have suggestions for improvements or new features, feel free to fork the repository and submit a pull request.

## 📜 License
This project is licensed under the [MIT License](LICENSE).

## 👤 Author
Arnab Ghosh