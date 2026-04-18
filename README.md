# 🎄 Holiday AI Agent (ADK + MCP + Gemini)

An AI agent that doesn't just respond — it creates.

This project demonstrates a context-aware AI agent built with Google ADK, MCP, and Gemini — now enhanced and deployed as a live interactive application.


🚀 Live Demo

👉 https://holiday-app-194383643137.us-central1.run.app/

⸻

🧠 What’s new (Update)

Originally built as a simple codelab project, this version has been upgraded with:

* ✨ Personalized AI interactions
* 🧠 Memory-enabled agent structure
* 🎨 Interactive 3D UI (React + Three.js)
* ☁️ Live deployment on Google Cloud Run

⸻

🛠️ Tech Stack

* Google ADK
* MCP (Model Context Protocol)
* Gemini 2.5 Flash
* Python (Backend)
* React + Three.js (Frontend)
* Google Cloud Run

⸻

🧩 Features

* Context-aware AI agent
* Multi-step task execution
* Memory-based responses
* Interactive 3D interface
* Real-time AI interaction

  🖼️ Project Preview
  
💡 What I Learned

* Building AI agents with memory
* Structuring agent-based systems
* Integrating LLMs with UI
* Deploying full-stack AI applications
* Combining AI with interactive 3D experiences

⸻

📂 Project Structure

* backend/ → AI agent & API
* frontend/ → React + 3D UI
* static/ → generated outputs

## Before the upgrate

This project demonstrates a context-aware AI agent built using Google ADK, MCP (Model Context Protocol), and Gemini 2.5 Flash, capable of orchestrating multiple tools and steps to complete complex tasks autonomously.

### 🎄 Holiday Scene

![Holiday Scene](static/generated_scene.png)

### 👕 Sweater Pattern
![Sweater Pattern](static/generated_pattern.png)

### 🤖 Web UI
![Web UI](agent_chat.png)

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

This diagram shows how the agent orchestrates multiple tools to generate the final output.

![Architecture](static/architecture_diagram.png)

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

### 👩‍💻 Author

Beyza Uzun

AI & Data Enthusiast
