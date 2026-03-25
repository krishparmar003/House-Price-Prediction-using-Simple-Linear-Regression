# House Price Prediction App

An end-to-end ML web app that predicts house prices based on size using Simple Linear Regression — from model training to live deployment.

**Live Demo:** [house-price-prediction-using-simple-linear-regression-krish3.streamlit.app](https://house-price-prediction-using-simple-linear-regression-krish3.streamlit.app/)

---

![App Screenshot](<img width="1886" height="907" alt="Screenshot" src="https://github.com/user-attachments/assets/99fd6558-b205-43e4-8ed4-4f38e7600753" />
)

---

## What it does

Enter a house size (in sq ft) and the app instantly predicts its price and visualizes it on an interactive scatter plot.

---

## End-to-End Pipeline

1. **Data** — Synthetic dataset generated using NumPy (normal distribution)
2. **Model Training** — Simple Linear Regression trained using Scikit-learn
3. **Prediction** — Model predicts price for user-inputted house size
4. **Visualization** — Live Plotly scatter plot with prediction highlighted in red
5. **Deployment** — Hosted on Streamlit Community Cloud

---

## Setup

```bash
git clone https://github.com/YOUR_USERNAME/House-Price-Prediction-using-Simple-Linear-Regression.git
cd House-Price-Prediction-using-Simple-Linear-Regression
pip install -r requirements.txt
streamlit run main.py
```

---

## Tech Stack
- **Model** — Simple Linear Regression (Scikit-learn)
- **UI** — Streamlit
- **Visualization** — Plotly Express
- **Deployment** — Streamlit Community Cloud

> Note: Uses synthetically generated data for demonstration purposes.
