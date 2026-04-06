
# 🛡️ SmartShield Workspace

## 📌 Description

SmartShield Workspace is a Python-based authentication system that implements adaptive security using OTP and behavior-based verification. The system continuously validates the user even after login to prevent unauthorized access.

## 🚀 Features

* Adaptive Binary OTP Authentication 🔑
* Behavior-Based Continuous Verification 🧠
* Failed Attempt Tracking 🚫
* Automatic System Lock after Suspicious Activity 🔒
* SQLite Database Integration 🗄️
* Object-Oriented Design (OOP) 🧩

## 🛠️ Technologies Used

* Python 🐍
* SQLite (Database)
* OOP (Object-Oriented Programming)

## ⚙️ How It Works

1. User enters username and password
2. System generates adaptive OTP
3. User verifies OTP
4. System performs continuous behavior checks
5. Suspicious activity triggers system lock

## ▶️ How to Run

```bash
python app.py
```

## 📂 Project Structure

```
project-folder/
│
├── app.py
├── users.db
└── README.md
```

## 🎯 Key Highlights

* Risk-based OTP length adjustment
* Behavior-driven authentication
* Lightweight and efficient system

## 📈 Future Improvements

* Password encryption (hashing)
* Email/SMS OTP delivery
* GUI interface
* Machine learning-based behavior detection
