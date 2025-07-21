 # 📧 Email Spam Detection System 🚨 | Python + ML

![Spam Detector](https://img.shields.io/badge/Spam-Ham%20Detector-brightgreen?style=for-the-badge&logo=python)
![Python](https://img.shields.io/badge/Python-ML-blue?style=for-the-badge&logo=python)
![License](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

<p align="center">
  <img src="https://github.com/Sangeetha-K-04/EmailSpamDetection/blob/main/spam%20filter.png?raw=true" alt="Spam Detection" width="600"/>
</p>

> ✨ A smart, interactive, and AI-powered email filter built with Python and Machine Learning to detect **Spam** vs **Ham** mails with high accuracy. It goes beyond simple classification and even allows users to take real-time action like **reporting**, **blocking**, or **deleting** suspicious messages.  

---

## 🚀 Features

- 🔍 **Spam Detection** using Natural Language Processing and Logistic Regression
- 📊 **TF-IDF Vectorization** to transform textual data into meaningful features
- 🧠 Trained model with **Balanced Class Weights** for improved performance on imbalanced data
- 🗂 Interactive CLI: Users can take actions on spam (Report, Block, Delete)
- 📈 Performance metrics for training and testing sets
- 💬 Real-time user input for mail checking
- ✅ Built-in **Spam Reporting System**
- 🚫 Maintains a list of **Blocked Senders**

---

 ## 📁 Project Structure

```text
📁 Email-Spam-Detection
│
├── 📄 mail_data.csv           # Dataset containing emails labeled as 'spam' or 'ham'
├── 🧠 spam_detector.py        # Core script for training and prediction
├── 📈 model & vectorizer      # Model and TF-IDF transformer
└── 📄 README.md               # This beautiful documentation 😄
```

---

## 📂 Dataset

We used a labeled dataset of emails (`mail_data.csv`) with the following fields:
- **Category**: `ham` or `spam`
- **Message**: The actual email content

The `Category` is mapped to binary labels:
- `1` → Ham (Not Spam)  
- `0` → Spam

---

## ⚙️ How It Works

1. **Preprocessing**: Missing values handled, categories encoded.
2. **Vectorization**: TF-IDF applied to convert messages into numerical format.
3. **Model Training**: Logistic Regression model trained with balanced weights.
4. **Prediction**: User inputs are classified in real-time.
5. **Spam Actions**:
   - Report Spam
   - Block Sender
   - Delete Message

---

## 🔢 Sample Prediction Output

