# QueryCraft

QueryCraft is an **AI-powered Natural Language → SQL converter** designed to help anyone query databases without writing SQL manually. Whether you're a student, developer, analyst, or non-technical professional, QueryCraft makes data extraction simple, intuitive, and fast.

---

## 🚀 Features

- **Natural language → SQL translation**
- Clean and simple **web interface**
- **AI-powered** using the `T5-LM-Large-text2sql-spider` model
- Automatic SQL execution + **result preview**
- Supports:
  - SELECT  
  - WHERE  
  - JOIN  
  - GROUP BY / Aggregates  
- Export & documentation-ready **screenshots**
- Pluggable with any SQL database (SQLite/MySQL/Postgres)

---

## 🧠 Tech Stack

**Frontend:**  
- HTML, CSS, optional Jinja/JavaScript

**Backend:**  
- Python (Flask or FastAPI)

**Database:**  
- SQLite / MySQL / any SQL database

**Libraries Used:**  
- Hugging Face Transformers  
- torch  
- Flask or FastAPI  
- reportlab/fpdf (optional for PDF export)

---

## 📦 Installation & Setup

```bash
git clone https://github.com/tanishk001-ai/QueryCraft.git
cd QueryCraft

python3 -m venv venv
source venv/bin/activate
# On Windows: venv\Scripts\activate

pip install -r requirements.txt
python app.py

Once started, access the app at:
👉 http://127.0.0.1:5000
```
---

## 📌 Roadmap

- 🌍 Multi-language query support  
- 🔐 User authentication + query history  
- 🎤 Voice-based natural language input  
- 🧩 Support for more advanced SQL structures  
- 📊 Analytics dashboard & data visualizations

---

## 🤝 Contributing

[Tanishk Tiwari](https://github.com/tanishk001-ai)

---

## 📜 License

This project is licensed under the **MIT License**.

---



