# 🤖 AI Research & Blog Generator (CrewAI Agent System)

An **Agentic AI application built with CrewAI, Groq LLM, and Streamlit** that automatically researches any topic and generates a well-structured blog article.

The system uses **multiple AI agents working together**:

* 🔎 Research Agent – gathers reliable web data
* ✍️ Content Writer Agent – converts research into a blog article

This project demonstrates **Agentic AI architecture, multi-agent workflows, and LLM orchestration.**

---

# 🚀 Features

* Multi-Agent AI workflow using CrewAI
* Web research using Serper API
* Blog generation using Groq LLM
* Interactive UI with Streamlit
* Download generated article as Markdown
* Adjustable temperature control
* Source citation support

---

# 🧠 Agent Architecture

Agent 1: **Senior Research Analyst**

* Performs web research
* Finds trends and statistics
* Verifies sources
* Creates research report

Agent 2: **Content Writer**

* Converts research into a blog
* Maintains citations
* Produces structured markdown article

Workflow:

User Input
↓
Research Agent
↓
Content Writer Agent
↓
Blog Output

---

# 🛠 Tech Stack

* Python
* CrewAI
* Groq LLM (Llama 3.1)
* Serper Search API
* Streamlit UI

---

# 📦 Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/crewai-research-blog-agent.git
cd crewai-research-blog-agent
```

Create virtual environment

```bash
python -m venv venv
source venv/bin/activate     # Mac/Linux
venv\Scripts\activate        # Windows
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 Environment Variables

Create a `.env` file in the root directory.

```
SERPER_API_KEY=your_serper_key
GROQ_API_KEY=your_groq_key
```

---

# ▶️ Run the Application

Start Streamlit app

```bash
streamlit run streamlit_app.py
```

Open browser:

```
http://localhost:8501
```

---

# 👨‍💻 Author

**Rohit Shirsat**

AI / Full Stack Developer
Java • Spring Boot • Angular • AI Systems

---

# ⭐ If you like this project

Give it a star on GitHub ⭐
