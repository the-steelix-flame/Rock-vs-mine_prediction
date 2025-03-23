# Rock vs Mine Prediction Using Machine Learning

This repository contains a **Machine Learning model** that classifies sonar signals as either **rock** or **mine** using **Logistic Regression** in Python.

---

## 📌 Project Overview

- Uses the **Sonar Dataset** to distinguish between rocks and underwater mines.
- Implements **Logistic Regression** for classification.
- Measures **accuracy on training and test data**.
- Accepts **custom input** for real-time predictions.

---

## 📂 Dataset

- The dataset used is a sonar-based dataset, where:
  - **"R"** represents a **Rock**.
  - **"M"** represents a **Mine**.
- It consists of **60 numerical features** extracted from sonar signals.

---

## 🚀 Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/rock-vs-mine-prediction.git
cd rock-vs-mine-prediction
```
### 🔹 Step 2: Install Dependencies
```bash
pip install numpy pandas scikit-learn
```
### 🔹 Step 3: Run the Flask App
```bash
python main.py
```

---

## 📜 Code Breakdown

### 🔹 Data Preprocessing
- Reads the dataset using Pandas.
- Splits it into features (`X`) and labels (`Y`).
- Uses train-test split (90%-10%).

### 🔹 Model Training
- Implements Logistic Regression using `sklearn.linear_model`.
- Trains the model on the training data.

### 🔹 Accuracy Evaluation
- Measures accuracy on both training and test datasets.

### 🔹 Prediction on New Data
- Accepts custom input in the form of a NumPy array.
- Reshapes input data for prediction.
- Predicts if the object is Rock or Mine.

---

## 🎯 Example Output

accuracy on test data: 0.8571  
accuracy on training data: 0.8392  
  
Prediction: ['M']  
The object is a Mine



---

## 🤝 Contributions

Contributions are welcome! Feel free to:
1. Fork the repository.
2. Improve the model or add more ML algorithms.
3. Create a pull request.

---

## 📜 License

This project is open-source under the [MIT License](LICENSE).

---

## 🔗 Connect

- **GitHub:** [Akash Kumar](https://github.com/the-steelix-flame)
- **LinkedIn:** [Akash](https://www.linkedin.com/in/ak-a-sh/)

---

### **Next Steps:**
1. Replace `yourusername` with your actual GitHub username.
2. Add a **dataset link** if it’s publicly available.
3. Consider adding a **Jupyter Notebook (.ipynb) file** for better visualization.

---
