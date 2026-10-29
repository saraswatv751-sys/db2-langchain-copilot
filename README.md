# IBM Db2 Smart Copilot: Natural Language to SQL Assistant

## 📌 Problem Statement
Business analysts, managers, and non-technical staff frequently struggle to write SQL queries to access data stored in enterprise IBM Db2 databases. Relying on database administrators for every simple data pull creates bottlenecks and delays decision-making.

## 💡 Solution Overview
The **IBM Db2 Smart Copilot** bridges this gap using LangChain and generative AI. It allows users to ask plain English questions (e.g., *"Show top 5 sales regions this quarter"*). The system automatically:
1. Inspects the Db2 database schema.
2. Synthesizes a valid, safe SQL query.
3. Executes it against IBM Db2.
4. Returns a simple, readable summary to the user.

## 🛠️ Architecture & Tech Stack
- **Database Engine:** IBM Db2
- **Agentic Framework:** LangChain (SQL Toolkit & Agent Executor)
- **Language:** Python 3.10+
- **Driver:** `ibm_db` / SQLAlchemy

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/saraswatv751-sys/db2-langchain-copilot.git](https://github.com/saraswatv751-sys/db2-langchain-copilot.git)
   cd db2-langchain-copilot
