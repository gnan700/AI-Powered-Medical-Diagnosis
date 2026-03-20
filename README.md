# 🧠 Medical Diagnosis AI Web App
An AI-powered full-stack Django web application that predicts multiple medical conditions using supervised machine learning models with 85%+ accuracy. This project demonstrates the integration of machine learning models into a real-world web application using Django’s MVT architecture. 

## 🚀 Features
- 🩺 Predicts 5 different medical conditions
- 🤖 Machine Learning models built using scikit-learn
- 🌐 Full-stack implementation using Django (MVT architecture)
- 🎨 Responsive UI with Bootstrap
- 🗄️ Lightweight database using SQLite
- ⚡ Real-time prediction based on user input
- 📊 Clean and user-friendly interface

## 🛠️ Tech Stack
### Frontend:
- **HTML**
- **CSS**
- **Bootstrap**

### Backend
- **Django (Python)**

### Machine Learning:
- **scikit-learn**
- **Numpy**
- **Pandas**

### Database:
- **SQLite**

## ⚙️ Installation & Setup

1. **Clone the Repository**
```
git clone https://github.com/gnan700/AI-Powered-Medical-Diagnosis.git
cd medical-diagnosis-ai
```
2. **Create Virtual Environment**
```
python -m venv venv
venv\Scripts\activate   # Windows
```
3. **Install Dependencies**
```
pip install -r requirements.txt
```
4. **Apply Migrations**
```
python manage.py migrate
```
5. **Run the Server**
```
python manage.py runserver
```

## 🤖 Machine Learning Workflow
1. Data collection & preprocessing
2. Model training using supervised learning algorithms
3. Model evaluation (accuracy > 85%)
4. Model serialization using pickle
5. Integration with Django backend
6. Real-time predictions via user input

## ⚠️ Known Issues
- ⚠️ Model version mismatch warnings (if sklearn versions differ)
- ⚠️ Requires retraining models for different sklearn versions

## 🔮 Future Improvements
- Add more diseases and improve accuracy
- Add user authentication system
- Store prediction history
- Improve UI with React or modern frameworks
