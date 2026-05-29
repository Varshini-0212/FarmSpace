# 🌾Farmspace

[![Python](https://img.shields.io/badge/Python-3.14+-4B8BBE?logo=python&logoColor=white)](https://www.python.org/)
[![UV](https://img.shields.io/badge/UV-Setup-111827?logo=python&logoColor=white)](https://docs.astral.sh/uv/)
[![Flask](https://img.shields.io/badge/Flask-3.1-111827?logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![Pandas](https://img.shields.io/badge/Pandas-2.x-0C7BDC?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-2.x-4DABF7?logo=numpy&logoColor=white)](https://numpy.org/)
[![scikit--learn](https://img.shields.io/badge/scikit--learn-1.x-FBBF24?logo=scikitlearn&logoColor=111827)](https://scikit-learn.org/)
[![SQLite](https://img.shields.io/badge/SQLite-DB-0F766E?logo=sqlite&logoColor=white)](https://www.sqlite.org/)
[![Joblib](https://img.shields.io/badge/Joblib-Model-8B5CF6?logo=python&logoColor=white)](https://joblib.readthedocs.io/)
[![MIT License](https://img.shields.io/badge/License-MIT-EC4899?logo=open-source-initiative&logoColor=white)](LICENSE)


FarmSpace is an AI-powered agriculture platform that combines machine learning, weather intelligence, and e-commerce features to assist farmers in making informed agricultural decisions.

The platform predicts suitable crops based on environmental conditions, provides weather-based planning support, and offers a marketplace for agricultural supplies such as fertilizers and pesticides.

🚀 Features

🤖 Crop Recommendation & Yield Prediction

* Predicts suitable crops using Machine Learning
* Utilizes weather and soil parameters
* Generates intelligent farming recommendations

🌦 Weather Intelligence

* Automatic location-based weather lookup.
* Weekly weather forecasting.
* Planning support for farming activities.

🛒 Farm Supply Marketplace

* Browse agricultural products.
* Add products to cart.
* Quantity-based cart management.
* Checkout functionality.

👤 User Management

* User Registration
* Login & Logout
* Secure account management

📦 Order Management

* Order placement
* Order history tracking
* Detailed order information

## 📂 Project Structure

```text
FarmSpace
│
├── main.py   -  Flask application and CLI entrypoint; contains routes, database setup, weather APIs, cart, and orders
├── model.py    - ML training and prediction logic
├── crop_yield_dataset.csv    - Training dataset
│
├── artifacts/
│   └── Trained ML Models
│
├── static/
│   ├── CSS
│   └── Images
│
└── templates/
    └── HTML Templates
```
🛠 Technology Stack

Backend
* Python
* Flask

Machine Learning
* Pandas
* NumPy
* Scikit-Learn
* Joblib

Database
* SQLite

Frontend
* HTML
* CSS
* JavaScript

## uv install 
```bash
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

## Quick Start

1. Install dependencies:

   ```bash
   uv sync
   ```

2. Train the model and create the artifact:

   ```bash
   uv run python model.py
   ```

3. Run the Flask app:

   ```bash
   uv run python main.py
   ```

4. Open the app in your browser:

   ```
   http://127.0.0.1:5000
   ```
🎯 Learning Outcomes

This project helped strengthen knowledge in:

Machine Learning Model Development
Flask Web Development
SQLite Database Integration
User Authentication
E-Commerce Workflow Implementation
Weather API Integration
Full Stack Application Development
🔮 Future Enhancements
Real-Time Weather Alerts
Crop Disease Detection
Market Price Prediction
Farmer Community Portal
Mobile Application Support

## License

This project is licensed under the [MIT License](LICENSE).


👩‍💻 Author

**Varshini Keerthi**

GitHub: https://github.com/Varshini-0212
