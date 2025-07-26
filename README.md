# UX Final Project – Car Price Prediction Platform

## 📝 Project Overview

This project presents a web-based application for second-hand car price prediction, integrating user experience (UX) principles with machine learning. The platform allows users to enter vehicle details and receive accurate price estimations, along with recommendations for similar cars. The system is designed to be accessible, visually modern, and user-friendly.

## 🚀 Features

- 🔍 **Price Prediction**: Instant estimation based on car specifications.
- 🧠 **Machine Learning Models**: Uses trained regression models (XGBoost, Gradient Boosting, etc.).
- 🧾 **Similar Cars Suggestion**: Recommends cars within the estimated price range.
- 🌗 **Dark Mode**: User interface supports light/dark themes.
- 🌐 **Multilingual Support**: Interface available in multiple languages.
- 🖼️ **Enhanced UI**: Uses visual components like cards, forms, and styled navigation for better engagement.

## 🛠️ Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask)
- **Machine Learning**: scikit-learn, XGBoost, pandas, numpy
- **Deployment**: Flask local server (or compatible hosting)
- **Data Visualization**: Matplotlib, Seaborn

## 📦 Installation & Running

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/project-repo-name.git
   cd project-repo-name
   ```

2. **Set up Python environment**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Flask app**:
   ```bash
   python app.py
   ```

4. **Open your browser**:
   ```
   http://127.0.0.1:5000/
   ```

## 🧠 Machine Learning Details

- Models trained on structured car data using regression techniques.
- Feature engineering includes brand, model, year, mileage, fuel type, gear type, etc.
- XGBoost and Gradient Boosting were found to perform best in predicting non-linear price patterns.

## 📁 Project Structure

```
├── static/               # CSS, JS, images
├── templates/            # HTML files
├── models/               # Trained ML models
├── app.py                # Flask backend
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

## 👥 Contributors

- [Your Name] – UX Design, Frontend Developer
- [Teammate 1] – Backend Developer
- [Teammate 2] – ML Engineer

## 📌 License

This project is for educational purposes only.
