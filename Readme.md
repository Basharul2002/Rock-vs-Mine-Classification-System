<h1 align="center">🪨 Rock vs Mine Classification System ⛏️</h1>

<p align="center">
  A machine learning-based system to classify sonar signals between rocks and mines! 🔍🚢
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue" />
  <img src="https://img.shields.io/badge/Scikit--learn-0.24-orange" />
  <img src="https://img.shields.io/badge/Pandas-1.3.3-yellowgreen" />
  <img src="https://img.shields.io/badge/NumPy-1.21-lightblue" />
  <!-- <img src="https://img.shields.io/github/license/basharul2002/Rock-vs-Mine-Classification" /> -->
</p>

---

## 📖 Overview

The **Rock vs Mine Classification System** is designed to classify sonar signals into **Rocks** or **Mines**. This project uses **Logistic Regression** to analyze and predict based on sonar frequencies reflected off objects.

## 💡 Features
- **Data Preprocessing**: Clean and prepare sonar data for analysis.
- **Model Training**: Train a machine learning model using **Logistic Regression**.
- **Object Classification**: Classify whether an object is a **Rock** or a **Mine** based on sonar readings.
- **Accurate Predictions**: Achieve reliable performance through testing and evaluation.

## 🛠️ Technologies Used

- **Python**: Main programming language for model development.
- **NumPy**: Used for numerical operations and matrix manipulations.
- **Pandas**: For handling and preprocessing sonar data.
- **Scikit-learn**: To implement Logistic Regression and model evaluation.

---

## 🚀 How It Works

1. **Data Preprocessing**: The dataset is loaded, and features (sonar signal readings) are extracted. Missing values are checked, and the data is split into training and test sets.

2. **Model Training**: A **Logistic Regression** model is trained using 90% of the dataset, while the remaining 10% is used to evaluate model performance.

3. **Prediction System**: Users can input new sonar data to classify whether the object is a **Rock** or a **Mine**.

---

## ⚙️ How to Run

Follow these steps to run the system locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/basharul2002/Rock-vs-Mine-Classification.git
```

### 2️⃣ Install Dependencies
Ensure the necessary libraries are installed. Run:
```bash
pip install numpy pandas scikit-learn
```

### 3️⃣ Run the Python Script
Make sure the sonar dataset is available and execute the script:
```bash
python rock_vs_mine_classification.py
```

### 4️⃣ Enter Sonar Data
Input the sonar signal data when prompted, and the system will classify it as a **Rock** or a **Mine**.

---

## 📊 Example Output

```bash
Model Accuracy: 85.3%

Enter the sonar readings: [0.031, 0.025, 0.021, ...]
Prediction: The object is a Mine.
```

---

## 📂 Directory Structure

```
Rock-vs-Mine-Classification/
│
├── data/
│   └── sonar_dataset.csv     # Sonar readings dataset
├── rock_vs_mine_classification.py  # Main Python script
└── README.md                 # Documentation
```

<!--
---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
-->
