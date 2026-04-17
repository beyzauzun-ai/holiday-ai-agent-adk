# 🎄 Holiday AI Agent (ADK + MCP + Gemini)

An AI agent that doesn't just respond — it creates.

This project demonstrates a context-aware AI agent built using Google ADK, MCP (Model Context Protocol), and Gemini 2.5 Flash, capable of orchestrating multiple tools and steps to complete complex tasks autonomously.

### 🎄 Holiday Scene

![Holiday Scene](static/generated_scene.png)


## ✨ Overview

Instead of a basic chatbot, this AI agent:

- Understands context with a defined persona
- Uses tools via MCP to perform actions
- Generates visual outputs through multi-step workflows


## 🎯 Capabilities

The agent can generate:

- 🎄 Holiday scenes  
- 🧶 Sweater patterns  
- 👕 Characters wearing custom designs  
- 🖼️ Final composed images  

---

## 🔁 Example Workflow

User prompt:

"Create a snowy holiday scene and design a pizza-themed sweater"

Agent execution:

1️⃣ Generate holiday scene  
2️⃣ Create sweater pattern  
3️⃣ Generate character wearing it  
4️⃣ Compose final image  

➡️ All steps are executed automatically via MCP tools.

## 🏗️ Architecture

User → Root Agent → MCP Tools → Image Generation Pipeline → Final Output

## 🧠 What Makes This Project Interesting

Instead of just calling a model, this project demonstrates:

- Context-aware behavior using memory  
- Tool usage via MCP  
- Iterative agent development  
- Real-time testing with a web UI  

👉 This reflects how modern AI systems move beyond prompts and become **structured, functional agents**.

---

## 🛠️ Tech Stack

- Python  
- Google ADK (Agent Development Kit)  
- MCP (Model Context Protocol)  
- Gemini 2.5 Flash  
- FastAPI / Uvicorn  


## 📸 Example Outputs

### Final Output
![Final Output](final_ai_agent_output.png)

### 👕 Sweater Pattern
![Sweater Pattern](static/generated_pattern.png)

### 🤖 Web UI
![Web UI](agent_chat.png)


## 🚀 Getting Started

```bash
git clone https://github.com/beyzauzun-ai/holiday-ai-agent-adk.git
cd holiday-ai-agent-adk
pip install -r requirements.txt
```

### 🔑 Set your API key:

export GOOGLE_API_KEY=your_api_key_here

### ▶️ Run the agent:

python main.py

### 📌 Next Steps

Improve customization options

Add more tools and workflows

Deploy as a production-ready AI agent system


### 👩‍💻 Author

Beyza Uzun

AI & Data Enthusiast
