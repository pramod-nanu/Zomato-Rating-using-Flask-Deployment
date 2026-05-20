# Zomato Restaurant Rating Prediction 🍽️⭐

A Machine Learning web application built using **Flask**, **Random Forest Regressor**, and **Python** to predict restaurant ratings based on different restaurant features like online order, table booking, votes, location, cuisines, cost, etc.

---

# 🚀 Project Demo

This application predicts the expected Zomato restaurant rating using a trained Machine Learning model.

---

# 📌 Features

- Predict restaurant ratings instantly
- User-friendly web interface
- Machine Learning model using Random Forest Regressor
- Flask-based backend
- Responsive frontend using HTML & CSS

---

# 🛠️ Technologies Used

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- HTML
- CSS
- Pickle
- Streamlit (optional deployment)

---

# 📂 Project Structure

```bash
├── model.pkl
├── Zomato_df.csv
├── requirements.txt
├── streamlit_app.py
└── README.md
```

---

# 📊 Machine Learning Model

Model Used:

```python
RandomForestRegressor(
    n_estimators=650,
    random_state=245,
    min_samples_leaf=0.0001
)
```

Accuracy Score (R² Score):

```python
0.88
```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/zomato-rating-predictor.git
```

Move into project folder:

```bash
cd zomato-rating-predictor
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# ▶️ Run Application

For Streamlit:

```bash
streamlit run streamlit_app.py
```

---

# 📈 Input Features

The model takes inputs such as:

- Online Order
- Book Table
- Votes
- Location
- Restaurant Type
- Cuisines
- Cost
- Menu Item

---

# 🌐 Deployment

This project can be deployed using:

- Streamlit Cloud
- Render
- Railway

---

# 👨‍💻 Author

Pramod Gaikwad

GitHub:  
https://github.com/pramod-nanu

---

# ⭐ If you like this project

Give this repository a star ⭐ on GitHub.
