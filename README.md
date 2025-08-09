## Fraud-Detection-Machine-Learning-Project
This project focuses on detecting fraudulent financial transactions using machine learning.   It involves data cleaning, feature engineering, model training, and evaluation using **Python** and **XGBoost**.   The goal is to accurately classify transactions as fraudulent or genuine, even when the dataset is highly imbalanced.
---

## 📂 Project Structure
## ⚙️ Technologies Used
- **Python 3.10+**
- **Pandas / NumPy** — Data manipulation
- **Matplotlib / Seaborn** — Visualization
- **Scikit-learn** — Model training & evaluation
- **XGBoost** — Main classification model
- **imbalanced-learn** — SMOTE for handling class imbalance

---

## 📊 Workflow
1. **Data Exploration (EDA)**  
   - Checked missing values and data types  
   - Visualized distributions and transaction types

2. **Feature Engineering**  
   - Created `log_amount`, `balance changes`, and time-based features  
   - Encoded categorical features

3. **Correlation Analysis**  
   - Generated a correlation heatmap to detect multicollinearity

4. **Data Balancing**  
   - Applied **SMOTE** to oversample the minority (fraud) class

5. **Model Training**  
   - Used **XGBoost Classifier** with tuned parameters  
   - Split data into training and test sets

6. **Evaluation**  
   - ROC-AUC score  
   - Precision-Recall curve  
   - F1-score & Best Threshold selection

---

## 🚀 How to Run
1. **Clone the Repository**
   ```bash
   git clone https://github.com/nuragajraj/Fraud-Detection-Machine-Learning-Project.git
   cd fraud-detection
   
2. **Install Dependencies**
  ```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn
```
3. **Run the Notebook**
```bash
jupyter notebook FraudDetection.ipynb
```


## 🧠 Key Learnings
  - How to handle imbalanced datasets using SMOTE
  - Importance of feature engineering for fraud detection
  - Using ROC-AUC & Precision-Recall curves for model evaluation

## 📜 License
  - This project is for educational purposes only.
  - Feel free to fork and experiment! 🚀

