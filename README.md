 # 📧 Email Spam Detection System 🚨 | Python + ML

![Spam Detector](https://img.shields.io/badge/Spam-Ham%20Detector-brightgreen?style=for-the-badge&logo=python)
![Python](https://img.shields.io/badge/Python-ML-blue?style=for-the-badge&logo=python)
![License](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

<p align="center">
  <img src="https://github.com/Sangeetha-K-04/EmailSpamDetection/blob/main/spam%20filter.png?raw=true" alt="Spam Detection" width="600"/>
</p>

> ✨ A smart, interactive, and AI-powered email filter built with Python and Machine Learning to detect **Spam** vs **Ham** mails with high accuracy. It goes beyond simple classification and even allows users to take real-time action like **reporting**, **blocking**, or **deleting** suspicious messages.

>  🎓 This is an academic project I completed to demonstrate how machine learning can be used to classify emails as spam or ham using Python and scikit-learn.


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

![Spam Detection](https://github.com/Sangeetha-K-04/EmailSpamDetection/blob/main/output%20spam.png?raw=true)

---

## 🎯 Accuracy

| Dataset       | Accuracy 📈 |
|---------------|--------------|
| Training Set  | 98–99% ✅     |
| Testing Set   | ~96% 🔥       |

> Consistent and robust model even on unseen messages. Handles class imbalance using `class_weight='balanced'`.

---

## 💻 Technologies Used

- Python 🐍
- pandas & numpy
- scikit-learn (LogisticRegression, TfidfVectorizer)
  
---

## 📎 Project Resources

Dive deeper into the academic analysis and professional presentation of this project:

- 📄 [📥 Download Full Report (DOCX)](https://drive.google.com/file/d/1QiFD1c8EDp5rSMb6GrLzoHBP29mwDauG/view?usp=drive_link)
- 🎞️ [📥 Download Presentation Slides (PPTX)](https://docs.google.com/presentation/d/1R46GywupohF_NQ2OTmckatAARLkabNsy/edit?usp=drive_link&ouid=114852303107730781591&rtpof=true&sd=true)

> Note: Due to GitHub limitations, file previews might not be available — but you can still download and explore the full content!

---

## 🧠 Future Enhancements

- 📨 Integrate with a real email client (like Gmail API)
- 📬 UI Dashboard using Streamlit or Flask
- 📌 Store spam logs in a database

---

## 🌟 Show Your Support

If you liked this project, please ⭐ the repo and follow me for more data science & ML projects! 🤗

---

## 📬 Contact

For collaborations, ideas, or suggestions:  
📧 pearlynsangeetha.12@gmail.com  

---

> “In a world full of spam, be a ham.” 😄  
