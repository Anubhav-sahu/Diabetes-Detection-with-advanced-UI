# Diabetes-Detection-with-advanced-UI
🧠 A machine learning-based web app to predict diabetes using the PIMA Indian Diabetes dataset. Trained with Random Forest and deployed using Streamlit for live testing.



## 📌 Features

- Predict diabetes based on user input features
- Built using PIMA Indian Diabetes Dataset
- Clean and interactive **Streamlit UI**
- Shows prediction result and probability
- Complete code for model training and deployment included

---


## 📂 Project Structure

```
diabetes_ml_project/
├── diabetes.csv              # Dataset
├── train_model.py            # ML pipeline: preprocessing + training + saving model
├── diabetes_model.pkl        # Trained Random Forest model
├── scaler.pkl                # Feature scaler
├── diabetes_ui.py            # Streamlit web app
└── README.md                 # Project documentation
```

---

## ⚙️ Technologies Used

- **Python 3**
- **pandas, numpy** - data manipulation
- **matplotlib, seaborn** - EDA & visualization
- **scikit-learn** - ML modeling, preprocessing, metrics
- **joblib** - Model persistence
- **Streamlit** - Web app frontend
- **VS Code + Virtual Environment (venv)**

---

## 💻 How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/your-username/diabetes-prediction-app.git
cd diabetes-prediction-app
```

### 2. Create and activate virtual environment
```bash
python -m venv venv
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Train the model (optional, already included)
```bash
python train_model.py
```

### 5. Launch Streamlit app
```bash
streamlit run diabetes_ui.py
```

---

## 🧠 Model Info

- **Algorithm**: Random Forest Classifier
- **Accuracy**: ~77% on test set
- **Input Features**:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age

---

## 📘 Dataset

- **Name**: PIMA Indians Diabetes Dataset  
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

---

## 📈 Example Output

> Prediction: ✅ Not Diabetic  
> Probability: Diabetic (28%) | Not Diabetic (72%)

---


