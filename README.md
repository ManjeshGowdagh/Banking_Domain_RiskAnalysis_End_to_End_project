# 📊 Banking Dashboard & EDA – Risk Analytics in Banking

## 📌 Project Overview
This project explores **risk analytics in banking and financial services** using both **Python-based Exploratory Data Analysis (EDA)** and **Power BI dashboards**.  
It helps banks and financial institutions **minimize the risk of loan defaults** by analyzing client profiles, deposits, loans, and engagement history.  

---

## 🛠️ Tools & Technologies
- **Python (Pandas, Matplotlib, Seaborn)** → Exploratory Data Analysis  
- **Jupyter Notebook** → Analysis workflow  
- **Power BI** → Interactive dashboards  
- **DAX (Data Analysis Expressions)** → Calculations & KPIs  

---

## 📊 Part 1 – Exploratory Data Analysis (EDA)
Performed in Python to understand data before visualization.  

### Key Steps:
- **Data Cleaning** → Handling missing values, formatting  
- **Feature Engineering** → Created `Engagement Days`, `Income Bands`, `Processing Fees`  
- **Univariate & Bivariate Analysis** → Income groups, loan vs deposits, gender-based analysis  
- **Correlation Analysis** → Loans vs deposits, income vs fees  

📓 Detailed analysis is available in `BankEDA (Version 2).ipynb`

---

## 📈 Part 2 – Power BI Dashboard
Built dashboards to provide **business-ready insights** with filters for year, gender, and banking relationship.  

---

## 📸 Dashboard Pages

### 🏠 Home Dashboard
<img width="1371" height="770" alt="image" src="https://github.com/user-attachments/assets/17921f8b-6911-43a5-9508-b9d4dbbd8bd3" />
 
- Provides a **high-level overview** of banking operations.  
- KPIs include: **Total Clients (131)**, **Total Loan (187.81M)**, **Total Deposit (170.15M)**, **Checking Accounts (39.53M)**, **Savings Accounts (33.91M)**, **Business Lending (113.07M)**.  
- 📌 *Insight*: Quickly shows overall client volume, deposits, and loan exposure by demographic filters.  

---

### 💳 Loan Analysis
<img width="1367" height="768" alt="image" src="https://github.com/user-attachments/assets/306cd93f-5336-485d-9d26-c8900437be5e" />
 
- Focuses on **loan-related metrics** with deep dive filters.  
- Metrics: **Total Loan (88.31M)**, **Bank Loan (35.04M)**, **Business Lending (53.05M)**, **Credit Card Balance (215.6M)**.  
- Visuals:  
  - **Loan by Income Band** → Medium band holds ~60.47% of loans.  
  - **Loan by Banking Relationship** → Private banks dominate.  
  - **Loan by Occupation** → Certain professions borrow the most.  
  - **Loan by Nationality** → Regional differences in borrowing.  
- 📌 *Insight*: **Credit card balances dominate loan exposure**, and medium-income clients form the largest borrower group.  

---

### 🏦 Deposit Analysis
<img width="1371" height="766" alt="image" src="https://github.com/user-attachments/assets/0b308d77-fb56-43c3-9cee-c1373144bb1d" />
  
- Provides insights into **deposit behavior**.  
- Metrics: **Total Deposit (89.94M)**, **Bank Deposit (50.12M)**, **Savings (17.45M)**, **Checking (20.43M)**.  
- Visuals:  
  - **Deposits by Income Band** → Medium income contributes ~78.92%.  
  - **Deposits by Banking Relationship** → Private banks lead.  
  - **Deposits by Occupation** → Job categories influence deposit amounts.  
  - **Deposits by Nationality** → Regional savings differences.  
- 📌 *Insight*: Deposits are **heavily skewed towards medium-income groups**, showing strong saving capacity.  

---

### 📊 Summary Dashboard
<img width="1370" height="763" alt="image" src="https://github.com/user-attachments/assets/5f00dc11-9a89-4725-8abd-c4d9c7113faf" />

- Acts as a **consolidated view** of all KPIs.  
- Metrics: **Total Clients (248)**, **Total Loan (361.43M)**, **Bank Loan (145.48M)**, **Business Lending (215.14M)**, **Total Deposit (328.53M)**, **Bank Deposit (179.62M)**, **Checking (78.18M)**, **Savings (63.37M)**, **Foreign Currency (7.35M)**, **Engagement Accounts (501K)**.  
- 📌 *Insight*: Offers a **one-page snapshot** for decision-makers to assess total banking performance across loans, deposits, and engagement.  

---

## 🔢 Key KPIs
- **Total Clients** → Unique client count  
- **Total Loan** → Bank Loan + Business Lending + Credit Card Balance  
- **Total Deposits** → Checking, Savings, Foreign Currency, Bank Deposits  
- **Processing Fees** → Based on fee structures  
- **Engagement Days & Length** → Client relationship duration  

---

## 📈 Insights & Results
- **Private banks** have more clients compared to public banks  
- **Nationality-wise loan distribution** shows high-risk client groups  
- **Mid-income clients** contribute the majority of deposits and loans  
- Longer **engagement duration** correlates with repayment capacity  

---

## 🚀 Future Enhancements
- Build **Machine Learning models** to predict loan defaults  
- Deploy dashboards to **Power BI Service** for real-time updates  
- Automate ETL pipelines with **SQL & Python**  
- Expand analysis to include **customer churn prediction**  

---

## 👨‍💻 Author
**A Manjesh Gowda** – Data Analyst & Power BI Developer

🔗 [LinkedIn](https://linkedin.com/in/a-manjesh-gowda) | [GitHub]([https://github.com/Manjeshgowdagh](https://github.com/ManjeshGowdagh))  
📧 Contact: manjeshvirat11@gmail.com  

---
