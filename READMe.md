# Customer Segmentation Streamlit App

This project implements a **Customer Segmentation** pipeline using Python, Scikit-learn, and Streamlit.  
It includes Exploratory Data Analysis (EDA), feature engineering, scaling, model training, and a web-based prediction interface.

---

## Features
- **Exploratory Data Analysis (EDA)**:  
  - Descriptive statistics
  - Missing value checks
  - Distribution plots for numerical features
  - Correlation heatmap
  - Outlier detection
- **Feature Engineering**:
  - Creation of derived features (e.g., `Total_Spending`)
  - Encoding categorical variables
  - Scaling numerical variables with `StandardScaler`
- **Model Training**:
  - Clustering or classification-based segmentation (KMeans)
  - Hyperparameter tuning
- **Streamlit App**:
  - User-friendly UI for feature input
  - Scales input data using the trained scaler
  - Predicts customer segment with the trained model
  - Displays results instantly

---

## Project Structure
Customer_Segmentation/
│
├── cust_seg.py # Main Streamlit app for predictions
├── kmeans_model.pkl # Trained segmentation model
├── scaler.pkl # Trained scaler
├── Customer_seg.ipynb # Jupyter Notebook with EDA, training, saving model
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── data/
└── customers_segmentation.csv # Raw dataset (not included in repo)

---

## Installation

1. **Clone the repository**
```bash
git clone https://github.com/your-username/customer-segmentation.git
cd customer-segmentation

pip install -r requirements.txt

streamlit run cust_seg.py


