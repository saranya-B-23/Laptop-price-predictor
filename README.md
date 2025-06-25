
# 💻 Laptop Price Predictor

A machine learning-based Streamlit web app that predicts the price of a laptop configuration. Built using scikit-learn and XGBoost with preprocessing pipelines.

---

##  Project Overview

This application takes user inputs such as laptop brand, processor, screen specs, storage, and more, then predicts the **expected market price** using a trained machine learning model.

---

##  Features

- Brand and Type-based prediction
- Screen size, resolution, and PPI calculation
- HDD / SSD / RAM input handling
- Touchscreen and IPS screen awareness
- Uses Stacked ML models: `XGBoost`, `RandomForest`, and `LinearRegression`
- Lightweight and runs on **Streamlit**

---

##  Tech Stack

- Python 3.x
- Streamlit
- scikit-learn
- XGBoost
- NumPy / pandas / matplotlib

---

##  ML Pipeline

Model trained on real laptop pricing data with features like:
- Company
- CPU / GPU Brand
- SSD / HDD
- Screen size + PPI
- OS, RAM, weight
- Touchscreen, IPS display

Training handled in `Laptop_price_predictor.ipynb`, model saved in `pipe.pkl`.

---

## 📁 Project Structure

```plaintext
 Laptop_Price_Predictor/
├── .gitignore
├── app.py                        # Streamlit web application
├── pipe.pkl                     # Trained ML pipeline
├── df.pkl                       # Processed DataFrame used by app
├── laptop_data.csv              # Original cleaned dataset
├── Laptop_price_predictor.ipynb # Jupyter notebook for training
├── requirements.txt             # All dependencies
```

---


##  How to Run the App

```bash
streamlit run app.py
```

---


## 👩‍💻 Author

**Saranya B**  
🔗 [GitHub: @saranya-B-23](https://github.com/saranya-B-23)

---

##  Disclaimer

> This project is developed for academic and learning purposes. Predictions are based on historical data and may not reflect real-time market pricing.
