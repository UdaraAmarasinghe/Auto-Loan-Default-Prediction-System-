# 🚗 Auto Loan Default Prediction System

Auto loan defaults have become a critical issue for financial institutions, particularly Non-Banking Financial Institutions (NBFIs), as they heavily rely on vehicle loans. This study focuses on identifying the factors contributing to auto loan defaults, such as:

- Loan term length  
- Economic downturns  
- Interest rate fluctuations  
- Consumer financial literacy  

Rising defaults — fueled by high auto prices, soaring interest rates, and negative equity — strain NBFIs’ profitability and increase risk exposure. This analysis emphasizes the importance of **predictive modeling** to assess borrowers' repayment capabilities, enabling NBFIs to mitigate risks and enhance decision-making.

This system predicts auto loan risk levels based on demographic and financial factors. It leverages machine learning models and includes a user-friendly interface for interacting with the predictions.

## 🛠️ Tech Stack

| **Frontend**      - React.js                            
| **Backend**       - Flask (Python)                      
| **Machine Learning** - Scikit-learn, Pandas, NumPy       
| **Visualization**  - Matplotlib, Seaborn    
| **Data Processing** - Pandas                            
| **Language**      - Python                              

## 📊 Features

- Predicts loan default risk using ML models
- Clean and interactive React UI for user input
- Data visualization and exploration
- End-to-end ML workflow: preprocessing, training, and prediction
- Scalable architecture separating frontend and backend

## 📁 Project Structure

Auto-Loan-Default-Prediction-System/
│
├── frontend/             # React frontend
│   ├── public/
│   └── src/
│       └── components/
│
├── backend/              # Flask backend with ML logic
│   ├── app.py
│   └── model/
│
├── data/                 # Dataset and cleaning scripts
├── models/               # Saved trained models
└── README.md             # Project overview

## 🚀 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Auto-Loan-Default-Prediction-System.git
````

2. **Backend (Flask)**

   ```bash
   cd backend
   pip install -r requirements.txt
   python app.py
   ```

3. **Frontend (React)**

   ```bash
   cd frontend
   npm install
   npm start
   ```
