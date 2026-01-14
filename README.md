# Multiple Linear Regression – California Housing Price Prediction

This project implements a **Multiple Linear Regression (MLR)** model using Python to predict house prices based on multiple input features from the California Housing dataset.

---

## 📌 Project Objectives

The main goals of this project are:

- Understand the concept of Multiple Linear Regression
- Perform Exploratory Data Analysis (EDA)
- Preprocess real-world data
- Train a regression model using Scikit-learn
- Evaluate model performance using standard metrics
- Visualize relationships between variables
- Build a clean, reproducible ML pipeline

---

## 📂 Project Structure

```
multiple-linear-regression/
│
├── data/
│   └── california_housing.csv
│
├── notebooks/
│   └── MLR-2.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 📊 Dataset

The dataset used is the **California Housing Dataset** from `sklearn.datasets`.

### Features:
- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

### Target Variable:
- **Median House Value**

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/akashsmb10/multiple-linear-regression.git
cd multiple-linear-regression
```

### 2️⃣ (Optional) Create virtual environment

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run notebook

```bash
jupyter notebook
```

Open: `notebooks/MLR-2.ipynb`

---

## 📈 Model Evaluation

The model is evaluated using:

- R² Score
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 🚀 Future Improvements

- Add feature scaling
- Try Ridge & Lasso regression
- Add Polynomial Regression
- Convert to Python script
- Add Streamlit UI

---

## 👤 Author

**Akash Bailwad**  
GitHub: https://github.com/akashsmb10
