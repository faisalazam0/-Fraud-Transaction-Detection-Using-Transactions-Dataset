# Fraud Transaction Detection

## 📝 Project Overview
This project focuses on detecting fraudulent financial transactions using a simulated dataset. It applies machine learning techniques to classify whether a transaction is legitimate or fraudulent based on various conditions and behaviors simulated in the dataset.

## 📊 Dataset Description
The dataset consists of the following key columns:
- **TRANSACTION_ID**: Unique identifier for each transaction
- **TX_DATETIME**: Timestamp of the transaction
- **CUSTOMER_ID**: Unique ID for each customer
- **TERMINAL_ID**: ID of the terminal where transaction occurred
- **TX_AMOUNT**: Amount involved in the transaction
- **TX_FRAUD**: Target label (0 = Legitimate, 1 = Fraudulent)

### 📌 Fraud Simulation Logic
1. Transactions over a certain amount (e.g., 220) are marked fraudulent.
2. Random terminals are compromised and flagged over a 28-day window.
3. Customers are targeted where some transactions are multiplied in amount to simulate fraud.

These simulated patterns help in building and evaluating fraud detection models.

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 🚀 How to Run
1. Clone the repository or download the notebook.
2. Open `fraud_detection.ipynb` using Jupyter Notebook or Google Colab.
3. Run all the cells in sequence.
4. Evaluate the model performance and fraud detection logic.

## 📈 Results
The notebook explores data preprocessing, EDA, model training, and evaluation using metrics such as accuracy, precision, and recall.

## 📁 File Structure
- `fraud_detection.ipynb` – Main notebook
- `Fraud Transaction Detection.pdf` – Project objective and dataset details

## 📜 License
This project is developed for educational and demonstration purposes only.
