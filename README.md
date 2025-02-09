# 🚢 Analyzing the Titanic Passengers Dataset Using Advanced MySQL Queries

## 📌 Project Overview
The **Titanic dataset** contains detailed information about passengers, including **name, age, class, fare, survival status**, and other attributes. The goal of this project is to analyze this data using **advanced MySQL techniques** to gain insights into **passenger demographics, survival rates, and relationships between different attributes**.

## 🎯 Problem Statement
The objective is to perform **in-depth data analysis** on the Titanic dataset using key MySQL concepts, such as:
- **Subqueries**
- **Views**
- **Stored Procedures**
- **Common Table Expressions (CTEs)**
- **Window Functions** (LEAD, LAG, RANK, DENSE_RANK)

## 🛠️ Technologies Used
- **Database:** MySQL
- **Querying Techniques:** CTEs, Views, Stored Procedures, Window Functions
- **Tools:** SQL Workbench, MySQL CLI

---

## 📂 Dataset Information
### **1️⃣ Titanic Passengers Dataset**
| Column Name     | Description |
|----------------|-------------|
| **Passenger_No** | Unique identifier for each passenger  |
| **First_Name**  | Passenger's first name  |
| **Last_Name**  | Passenger's last name  |
| **Survived**  | 1 = Survived, 0 = Did not survive  |
| **Pclass**  | Passenger class (1st, 2nd, 3rd)  |
| **Sex**  | Gender of the passenger  |
| **Age**  | Age of the passenger  |
| **Parch**  | Number of parents/children aboard  |
| **Fare**  | Ticket fare paid  |
| **Embarked**  | Port where passenger boarded (C = Cherbourg, Q = Queenstown, S = Southampton)  |
| **Deck**  | Deck location (if available)  |
| **Embark_Town**  | Town associated with embarkation  |
| **Alive**  | 'Yes' if the passenger survived, 'No' otherwise  |

---

## 🚀 SQL Query Objectives

### **1️⃣ Find the Name and Age of the Oldest Survivor**
Retrieve the **name and age of the oldest passenger who survived**.

### **2️⃣ Create a View for Passenger Information**
Create a **view** to display **passenger survival status, class, age, and fare**.

### **3️⃣ Stored Procedure for Passenger Age Range**
Create a **stored procedure** to **retrieve passengers** based on a **given age range**.

### **4️⃣ Categorize Passengers Based on Fare Paid**
Write a query to classify passengers into **Low, Medium, or High fare categories**.

### **5️⃣ Compare Passenger Fares Using LEAD()**
Show each passenger's **fare and the fare of the next passenger**.

### **6️⃣ Compare Passenger Ages Using LAG()**
Show each passenger's **age and the age of the previous passenger**.

### **7️⃣ Rank Passengers by Fare (With Gaps)**
Write a query to **rank passengers based on their fare**, allowing **gaps in ranking**.

### **8️⃣ Rank Passengers by Fare (Without Gaps)**
Write a query to **rank passengers by fare** while ensuring **no gaps in ranking**.

### **9️⃣ Assign Row Numbers Based on Fare Order**
Use **ROW_NUMBER()** to **assign row numbers** based on fare values.

### **🔟 CTE for Average Fare Calculation**
Use a **CTE (Common Table Expression)** to calculate the **average fare** and find passengers who **paid more than the average**.

---

## 📂 Folder Structure
```
Titanic-Analysis/
│── 📜 README.md               # Project documentation
│── 📂 SQL-Scripts/            # Contains all SQL queries
│   ├── oldest_survivor.sql
│   ├── create_passenger_view.sql
│   ├── stored_procedure_age.sql
│   ├── categorize_fares.sql
│   ├── fare_lead_function.sql
│   ├── age_lag_function.sql
│   ├── rank_passengers_gaps.sql
│   ├── rank_passengers_no_gaps.sql
│   ├── row_number_fare.sql
│   ├── cte_avg_fare.sql
│── 📂 Reports/                # Analysis reports & insights
│── 📂 Data/                   # Sample datasets (if applicable)
```

---

## 🚀 How to Use
1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/Titanic-Analysis.git
   ```
2. **Import the dataset** into **MySQL**.
3. **Run the SQL scripts** to execute queries and analyze the dataset.
4. **Modify constraints and stored procedures** for custom insights.

---

## 📈 Expected Insights
- **Survival rates across different classes & fares**
- **Age patterns among passengers**
- **Passenger rankings based on ticket fare**
- **Identifying passengers who paid premium fares**



📌 **Author:** P Rohith Raveendran  
🔗 [GitHub Profile](https://github.com/rohithr2511) | 🔗 [LinkedIn Profile](https://www.linkedin.com/in/p-rohith-raveendran-dataanalyst/)  

