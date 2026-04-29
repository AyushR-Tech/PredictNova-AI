# 🎓 PredictNova AI

A **Flask web application** that predicts student exam scores based on:
- 📚 Study habits  
- 📅 Attendance  
- 📊 Previous scores  
- 😴 Sleep hours  
- 💡 Motivation level  

using a **pre-trained SVM machine learning model**.

---

## 🚀 Features

- 🎯 Predicts exam scores using ML
- 🖥️ User-friendly web interface
- 📈 Personalized performance feedback
- 📱 Fully responsive design

---

## 📁 Project Structure

```
Student-Performance-System/
│
├── app.py
├── requirements.txt
├── scaler.pkl
├── svm_model.pkl
│
├── static/
│   └── css/
│       ├── style.css
│       └── style2.css
│
└── templates/
    ├── index.html
    └── index2.html
```

---

## ⚙️ Setup Instructions

1. **Clone the repository**  
   ```bash
   git clone https://github.com/AyushR-Tech/Student-Performace-System.git
   cd Student-Performace-System
   ```

2. **Install required dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Make sure model files are available**  
   - `svm_model.pkl`
   - `scaler.pkl`  
   *(Both should be in the project root directory)*

4. **Run the Flask application**  
   ```bash
   python app.py
   ```

5. **Open your browser and go to**  
   [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 🧠 Usage

1. Fill in the required form inputs:
   - Hours Studied
   - Attendance (%)
   - Previous Scores
   - Sleep Hours
   - Motivation Level (1–10 scale)

2. Click **Predict**  
   📉 Your predicted exam score and 📢 feedback will appear instantly.

---

## 📄 File Descriptions

- `app.py` – Flask backend application
- `requirements.txt` – Python dependencies
- `templates/index.html` – Main web interface
- `static/css/style.css` – Main stylesheet
- `svm_model.pkl`, `scaler.pkl` – ML model and feature scaler

---

## 👨‍💻 Developed By

**Ayush Rewatkar**  
MIT Academy of Engineering, Alandi (D), Pune

---

## 📜 License

© 2024 Student Performance System. All rights reserved. 🚀
