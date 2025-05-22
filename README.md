# Student Mark Prediction Application 🎓📊

This is a **machine learning web application** built using **Flask**, **HTML**, **CSS**, and **Python** to predict student performance based on their input attributes. It allows users to input student data and receive predicted marks using a trained regression model.

---

## 📁 Project Structure

```
├── artifacts/              # Saved model, preprocessor, and other serialized objects
├── logs/                   # Log files
├── notebook/               # Jupyter notebooks for EDA and model training
│   ├── data/               # Raw datasets
│   └── catboost_info/      # CatBoost logs if used
├── src/
│   ├── components/         # Scripts for data ingestion, transformation, model training
│   ├── pipeline/           # Training and prediction pipeline
│   ├── exception.py        # Custom exception handling
│   ├── logger.py           # Logging configuration
│   └── utils.py            # Utility functions like model saving, evaluation
├── static/                 # CSS files
│   └── style.css
├── templates/              # HTML templates
│   ├── index.html
│   └── home.html
├── app.py                  # Flask app entry point
├── requirements.txt        # Python dependencies
├── setup.py                # Package setup
└── README.md               # Project overview and instructions
```

---

## 🚀 Features

- Train ML model on student data
- Web interface to input attributes like gender, ethnicity, lunch type, etc.
- Predict final marks (e.g., reading, writing scores)
- Stylish frontend with HTML & CSS
- Error logging and modular structure

---

## ⚙️ Setup Instructions

1. **Clone the Repository**

```bash
git clone <repository-url>
cd student-mark-predictor
```

2. **Create and Activate a Virtual Environment**

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. **Install Dependencies**

```bash
pip install -r requirements.txt
```

4. **Run the Flask App**

```bash
python app.py
```

5. Open your browser and go to `http://127.0.0.1:5000/`

---

## 🧠 Machine Learning Pipeline

- **Data Ingestion**: Load CSV data
- **Data Transformation**: Preprocessing using `ColumnTransformer`
- **Model Training**: Train multiple regressors (Random Forest, XGBoost, etc.)
- **Model Evaluation**: Use R² score to evaluate performance
- **Web Deployment**: Serve model via Flask with interactive UI

---

## ✨ Technologies Used

- Python, Pandas, NumPy
- Scikit-learn, XGBoost, CatBoost
- Flask, HTML5, CSS3
- VSCode / PyCharm for development

---

## 📬 Contact

For queries or contributions, please reach out to the project maintainer.
