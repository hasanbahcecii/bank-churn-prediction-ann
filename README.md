# 🧠 Neural Network Projects: ANN in TensorFlow

This repository contains deep learning projects implemented using **TensorFlow/Keras**.

🏦 **Artificial Neural Network (ANN)** – Customer churn prediction for a bank.

Each project includes complete data preprocessing, model building, training, and evaluation steps.

---

## 🏦 ANN – Bank Customer Churn Prediction

This project uses an **Artificial Neural Network (ANN)** to predict whether a customer will leave the bank based on their personal and financial information.

It is a **binary classification problem** where the output indicates:

- 1 → Customer leaves the bank  
- 0 → Customer stays  

---

## 📂 Dataset

The dataset `Churn_Modelling.csv` is included in the repository.

It contains customer information such as:

- Credit score  
- Geography  
- Gender  
- Age  
- Tenure  
- Balance  
- Number of products  
- Credit card status  
- Active membership  
- Estimated salary  

---

## ⚙️ Workflow

### 1️⃣ Data Preprocessing

- Label Encoding → Gender  
- One-Hot Encoding → Geography  
- Train/Test split (80/20)  
- Feature Scaling using **StandardScaler**

### 2️⃣ Building the ANN

The model is implemented using the **Keras Sequential API**:

- Dense (6 units, ReLU)
- Dense (6 units, ReLU)
- Dense (1 unit, Sigmoid)

### 3️⃣ Training

- Optimizer: **Adam**
- Loss function: **Binary Crossentropy**
- Batch size: **32**
- Epochs: **100**

### 4️⃣ Evaluation

- Test set predictions  
- Confusion matrix  
- Accuracy score  

### 5️⃣ Single Customer Prediction

The trained model can predict whether a specific customer will churn.

---

## 📊 Example Output

The model predicts whether the customer will:

**Stay in the bank** or **Leave the bank**

based on the input features.

---

## 🙏 Acknowledgements

- ANN dataset: **Churn Modelling dataset** (commonly used in ML courses)  
- Built for educational and portfolio purposes  

---

## 📜 License

This project is licensed under the MIT License:  
https://opensource.org/license/mit