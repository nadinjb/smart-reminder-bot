# 🧠 Smart Reminder Bot

A smart and flexible reminder system built in Python.  
Supports conditional rules, user-based reminders, and future integrations with Redis, scheduling tools, and messaging platforms.

---

## 📌 Features (planned)

- [ ] Create and store reminders with content and scheduled time  
- [ ] Basic condition: "Only remind me if it's Friday and I have no other events today"  
- [ ] Support for recurring reminders  
- [ ] CLI tool to create and view reminders  
- [ ] Background job that checks for reminders and sends notifications  
- [ ] Redis for efficient reminder queueing  
- [ ] Telegram/Mail/Console notifications  
- [ ] API with FastAPI or Flask  
- [ ] User management and multi-user support  

---

## 🧱 Tech Stack

- Python 🐍  
- SQLAlchemy + PostgreSQL (or SQLite for local dev)  
- Redis (planned)  
- APScheduler / Celery (for scheduling – planned)  
- FastAPI or Flask (for API – optional)  

---

## 🚀 Getting Started

> Not implemented yet – coming soon :)

---

## 📂 Project Structure (planned)

smart-reminder-bot/
├── app/
│   ├── models.py        # DB models (User, Reminder)
│   ├── db.py            # DB connection logic
│   ├── logic.py         # Conditional logic engine
│   ├── scheduler.py     # Background jobs / reminder checks
│   └── cli.py           # CLI interface
├── requirements.txt
├── README.md
└── config.py



---

## 📆 Roadmap

- Add CLI to create reminders  
- Add logic to evaluate conditions  
- Implement background scheduler  
- Redis integration  
- Notifications via console → telegram/email  
- API (optional)  
- Dockerize the app (maybe later)  

---

## 👩‍💻 Author

Created by [Nadin Jbara] – feel free to fork, star, or contribute!

---

