# 🩺 Multiple Disease Prediction System

A Streamlit web application that predicts the likelihood of three diseases — **Diabetes**, **Heart Disease**, and **Parkinson's Disease** — using trained Machine Learning models.

---

## 🚀 Features

- 📌 Predict **Diabetes** based on 8 medical features  
- 📌 Predict **Heart Disease** based on 13 health parameters  
- 📌 Predict **Parkinson’s Disease** using voice measurements  
- 📊 Clean UI with sidebar navigation  
- ✅ Real-time predictions with simple form inputs  
- 🔒 Built-in model integration using `pickle`  

---

## 🛠️ Built With

- **Python 3**  
- **Streamlit** – web framework  
- **Scikit-learn** – model training  
- **Pickle** – model serialization  
- **Pandas / Numpy** – data manipulation  
- **Streamlit-Option-Menu** – UI sidebar navigation  

---

## 📁 Directory Structure

```
.
├── diabetes_model.sav
├── heart_disease_model.sav
├── parkinsons_model.sav
├── app.py
└── README.md
```

---

## ▶️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Multiple-Disease-Prediction.git
cd Multiple-Disease-Prediction
```

### 2. Install Required Packages

```bash
pip install streamlit scikit-learn pandas numpy streamlit-option-menu
```

### 3. Run the App

```bash
streamlit run app.py
```

---

## 📌 Model Files

Make sure the following `.sav` model files are in the project folder:

- `diabetes_model.sav`  
- `heart_disease_model.sav`  
- `parkinsons_model.sav`  

If not available, you can train your own models using scikit-learn and save them using `pickle`.

---



## 🙌 Author

**Vasanthi Mada**  
B.Tech CSE | Machine Learning Enthusiast  
[LinkedIn](https://www.linkedin.com/in/VasanthiMada) • [GitHub](https://github.com/VasanthiMada)




