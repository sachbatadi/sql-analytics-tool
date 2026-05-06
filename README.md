# 🧠 SQL Analytics Tool

An AI-powered SQL query generator and data visualizer built with Python.
Just describe what you want to know — the tool writes the SQL, runs it, and charts the results automatically.

---

## 🚀 Features

- 🤖 Natural language to SQL using AI
- 🗄️ Connects to local SQLite databases
- 📊 Auto-generates charts and visualizations
- ⚡ Demo mode to test instantly without setup

---

## 🛠️ Tech Stack

- Python
- SQLite
- Matplotlib / Seaborn
- Anthropic Claude API (AI query generation)
- Streamlit (UI)

---

## 📁 Project Structure
sql-analytics-tool/
│
├── app.py                  # Main Streamlit app
├── demo.py                 # Demo script to test the tool
├── requirements.txt        # Python dependencies
│
└── src/
├── database.py         # Database connection handler
├── schema.py           # Schema reader
├── sql_generator.py    # AI SQL generation
├── executor.py         # Query executor
└── visualiser.py       # Chart generator
---

## ⚙️ Setup & Installation

```bash
# 1. Clone the repo
git clone https://github.com/sachbatadi/sql-analytics-tool.git
cd sql-analytics-tool

# 2. Create virtual environment
python -m venv venv
venv\Scripts\activate      # Windows
source venv/bin/activate   # Mac/Linux

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the demo
python demo.py

# 5. Launch the app
streamlit run app.py
```

---

## 👤 Author

**Sach Batadi**
[github.com/sachbatadi](https://github.com/sachbatadi)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
