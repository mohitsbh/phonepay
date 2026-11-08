📊 UPI Transaction Analytics | Python & Power BI

📌 Project Overview

This project focuses on analyzing UPI (Unified Payments Interface) transactions using Python and Power BI to identify transaction trends, payment behavior, bank performance, geographical patterns, and potential transaction risk indicators.

The objective is to transform raw transaction data into meaningful business insights that can support data-driven decision-making in the digital payments industry.

🎯 Project Objectives

- Analyze UPI transaction volume and total payment value.
- Monitor transaction success and failure rates.
- Identify transaction trends across months, days, and hours.
- Analyze state-wise transaction performance.
- Compare bank-wise transaction volumes and success rates.
- Understand payment type and merchant category distribution.
- Identify rule-based transaction risk indicators.
- Build an interactive Power BI dashboard.

🛠️ Tools & Technologies

Tool| Purpose
Python| Data analysis
Pandas| Data manipulation
NumPy| Numerical operations
Matplotlib| Data visualization
Seaborn| Statistical visualization
Jupyter Notebook| Exploratory Data Analysis
Power BI| Interactive dashboard
CSV| Dataset format

📂 Project Structure

phonepay/
│
├── phonepay.ipynb
│
├── UPI_Transaction_Analytics.pdf
│
├── UPI_Transaction_Analytics phonepay.pbit
│
├── cleaned_upi_transactions.csv
│
└── README.md

Note: Add the CSV file to the repository if it is not already uploaded.

📊 Dataset Information

The project analyzes a synthetic/sample UPI transaction dataset containing:

- 250,000 transactions
- Transaction period: January–December 2024
- Transaction amount
- Transaction status
- Sender bank
- Sender state
- Payment type
- Merchant category
- Device information
- Rule-based fraud indicator

Important: This is a synthetic/sample dataset and does not contain actual PhonePe customer transactions or confidential customer information.

📈 Key Performance Indicators (KPIs)

Metric| Result
Total Transactions| 250,000
Total Transaction Value| ₹328 Million
Transaction Success Rate| 95.05%
Failed Transactions| 12,376
Flagged Transactions| 480
Average Transaction Value| ₹1.31K

🔍 Key Business Insights

1. Transaction Performance: Overall transaction success rate is 95.05%, while 4.95% of transactions failed.

2. Geographical Analysis: Maharashtra recorded the highest transaction volume with 37,427 transactions.

3. Bank Performance: SBI recorded the highest transaction volume with 62,693 transactions.

4. Payment Behavior: P2P transactions contributed 44.98% of total transaction volume.

5. Time Analysis: 7 PM was the peak transaction hour, with 21,232 transactions.

6. Risk Analysis: 480 transactions (0.192%) were flagged by rule-based indicators.

7. Merchant Analysis: Shopping contributed the highest payment value, approximately ₹7.69 crore.

📊 Power BI Dashboard

The project includes the following analytical sections:

- Executive Overview
- Geographical Analysis
- Time & Trend Analysis
- Bank & Payment Behaviour
- Transaction Risk Indicators

The dashboard helps visualize transaction performance, payment behavior, and potential risk patterns.

⚙️ How to Run the Project

1. Clone the Repository

git clone https://github.com/mohitsbh/phonepay.git

2. Navigate to the Project Directory

cd phonepay

3. Install Required Libraries

pip install pandas numpy matplotlib seaborn jupyter

4. Launch Jupyter Notebook

jupyter notebook

5. Open the Notebook

Open "phonepay.ipynb" and execute the cells sequentially.

Make sure the CSV dataset is available at the file path specified in the notebook.

💡 Business Value

This project demonstrates how transaction-level data can be used to:

- Monitor digital payment performance.
- Understand customer payment behavior.
- Identify transaction failure patterns.
- Compare bank and geographical performance.
- Monitor potential transaction risks.
- Support business intelligence and operational decisions.

⚠️ Disclaimer

This project is developed for educational and portfolio purposes using synthetic/sample transaction data.

Rule-based flagged transactions represent potential risk indicators and should not be interpreted as confirmed fraudulent transactions.

This project is independent and is not affiliated with or endorsed by PhonePe.

👨‍💻 Author

Mohit Bhosale

Aspiring Data Analyst | Python | SQL | Power BI | Data Analytics

GitHub: https://github.com/mohitsbh

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback.
