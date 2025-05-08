
# 🧠 QDocBERT – Intelligent PDF Question Answering System

QDocBERT is a smart document-based question answering platform that enables users to extract relevant insights from PDF documents using natural language queries. Built using BERT, it provides accurate, context-aware answers, empowering users across research, education, law, and healthcare.

![Home Page](screenshots/home.png)
![Query Page](screenshots/query.png)

---

## 🚀 Features

- 🤖 **BERT-powered context extraction** for high accuracy
- 💬 Ask questions in natural language
- 📄 Upload multiple PDF documents
- 🧠 Extracts answers directly from PDF content
- 🔐 User authentication and password reset with OTP
- 📊 Knowledge base dashboard to track uploads
- ⚙️ Flask-based backend with a modern UI

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, Bootstrap, JavaScript, jQuery
- **Backend:** Python, Flask
- **ML/NLP:** HuggingFace Transformers, PyTorch, BERT
- **Database:** SQLite
- **Deployment Ready:** Works locally or on any WSGI server

---

## 📂 Folder Structure

```
.
├── app.py                  # Main Flask application
├── generate.py             # OTP and utility functions
├── cdqa_bert.py            # BERT model logic and PDF processing
├── templates/              # HTML templates
├── static/                 # CSS, JS, images
├── docs/                   # Uploaded PDF documents
├── assets/
│   ├── pem.db              # SQLite DB
│   ├── models/             # Pretrained BERT model
│   └── credentials.json    # For email-based OTP
└── requirements.txt        # Python dependencies
```

---

## 💡 How to Run Locally

1. **Clone the repository**

2. **Create virtual environment and activate it**
```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Run the Flask app**
```bash
python app.py
```

---

## 🧪 Screenshots

| Sign Up | Sign In | Home | Query |
|--------|---------|------|-------|
| ![signup](screenshots/signup.png) | ![signin](screenshots/signin.png) | ![home](screenshots/home.png) | ![query](screenshots/query.png) |

---

## 🔒 Security Features

- Passwords are hashed using MD5 (recommend migrating to SHA256 or bcrypt for production)
- Email OTP for secure password reset
- Role-based SQLite schema

---

## 📚 References

- [BERT Paper (Google AI)](https://arxiv.org/pdf/1810.04805.pdf)
- [Transformers Library](https://github.com/huggingface/transformers)
- [Flask Documentation](https://flask.palletsprojects.com)

---


