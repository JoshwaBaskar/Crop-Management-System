# 🌿 Crop Management System

**Crop Management System** is an advanced, machine-learning-powered platform designed to revolutionize modern agriculture. By leveraging predictive analytics and environmental data, it provides farmers with actionable insights, ranging from crop selection to yield forecasting.

---

## 🚀 Key Features

* 🌱 **Intelligent Crop Prediction** — Recommends the optimal crop based on geographical location and season.
* 🌾 **Advanced Crop Recommendation** — Suggests crops tailored to specific soil nutrient profiles (N, P, K) and weather conditions.
* 💊 **Precision Fertilizer Recommendation** — Identifies the most effective fertilizer based on soil type, moisture, and crop type.
* ☔ **Rainfall Forecasting** — Provides accurate rainfall predictions for specific regions to aid in irrigation planning.
* 📈 **Yield Estimation** — Forecasts expected crop yields to help in financial and logistical planning.

---

## 🧰 Technology Stack

* **Backend & ML Engine:** Python (scikit-learn, pandas, numpy)
* **Web Core:** PHP (Custom Routing & Execution Engine)
* **Frontend:** HTML5, CSS3, Modern Bootstrap 4/5 Integration
* **Interactivity:** JavaScript (ES6)

---

## 📦 Installation & Setup

1. **Clone the Repository**

   ```bash
   git clone <your-new-repo-link>
   cd agriai
   ```
2. **Install Machine Learning Dependencies**
   Ensure you have Python installed, then install the required packages:

   ```bash
   pip install -r requirements.txt
   ```
3. **Deploy Web Server**

   * Use an Apache server (like [XAMPP](https://www.apachefriends.org/index.html) or WAMP).
   * Place the project directory into your `htdocs` or `www` folder.
   * Start Apache and navigate to `http://localhost/agriai` (or your specific directory name) in your browser.

---

## 🧪 Architecture Overview

The system utilizes a decoupled architecture where the PHP web core communicates with the Python ML Engine via a centralized `MachineLearningEngine` class located in the `core/` directory. This ensures secure execution and easy scalability.

---

## 📄 License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).
