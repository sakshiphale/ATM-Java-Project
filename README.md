
# 🏧 ATM Simulator System

> A fully functional desktop-based ATM simulator application built with Java Swing and MySQL.  
> Developed by **Sakshi Mahesh Phale**.

---

## 📌 Project Overview

This ATM Simulator System replicates the basic functionalities of an actual ATM machine. The user can:

- 📝 Open a new bank account
- 💳 Receive a unique card number and secure 4-digit PIN
- 💰 Deposit and withdraw cash
- ⚡ Use Fast Cash for quick transactions
- 📄 View transaction history (Mini Statement)
- 🔐 Change ATM PIN
- 📊 Check account balance

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Java       | Core language for GUI and logic (Java Swing for UI) |
| MySQL      | Relational database for storing user and transaction data |
| JDBC       | For database connectivity between Java and MySQL |
| Git & GitHub | For source control and version tracking |

---

## 📂 Project Structure

```
ATM-Simulator-Sakshi/
├── src/
│   └── ASimulatorSystem/
│       ├── Signup.java
│       ├── Signup2.java
│       ├── Signup3.java
│       ├── Login.java
│       ├── Transactions.java
│       ├── Deposit.java
│       ├── Withdrawl.java
│       ├── FastCash.java
│       ├── BalanceEnquiry.java
│       ├── MiniStatement.java
│       ├── Pin.java
│       ├── Conn.java
│       └── Practice.java
├── icons/
│   └── atm.jpg, logo.jpg, etc.
├── README.md
├── LICENSE
```

---

## 🚀 How to Run the Project

### ✅ Prerequisites
- Java JDK 8 or later  
- MySQL Server or XAMPP  
- Eclipse/IntelliJ IDE

### ⚙️ Setup Instructions

1. **Download the Project**
   - You can download the ZIP file from GitHub or clone it using:
     ```
     git clone https://github.com/sakshiphale/ATM-Simulator-Sakshi.git
     ```

2. **Import into IDE**
   - Open Eclipse or IntelliJ  
   - Import as Java Project

3. **Setup the Database**
   - Create a MySQL database named: `bankmanagementsystem`
   - Tables will be created automatically via JDBC if not present

4. **Run the Application**
   - Start with `Signup.java` or `Login.java`

---

## ✨ Features Implemented

- Interactive Java Swing GUI
- JDBC MySQL integration
- Modular Java architecture
- Realistic ATM-like workflow
- Form validations and error handling

---

## 🙋‍♀️ Developer Info

**Sakshi Mahesh Phale**  
🎓 B.E. Computer Science and Engineering (2021–2025)  
💻 Passionate about Java and Web Development  
🌐 GitHub: [sakshiphale](https://github.com/sakshiphale)  

---

## 📸 Screenshots

_You can add images like:_  
- 🧾 Account registration form  
- 💸 Transaction page  
- 💳 Deposit/Withdraw UI

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
