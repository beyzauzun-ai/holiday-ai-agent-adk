# 🎄 Holiday AI Agent (ADK + MCP + Gemini)

An AI agent that doesn't just respond — it creates.

This project demonstrates a context-aware AI agent built using Google ADK, MCP (Model Context Protocol), and Gemini 2.5 Flash.

## 🚀 Features
- Context-aware AI agent with a defined persona
- MCP tool integration for image generation workflows
- Holiday scene generation
- Sweater pattern generation
- Web-based testing with ADK UI

## Tech Stack
- Python
- Google ADK
- MCP
- Gemini 2.5 Flash

## Demo
This project can:
- generate festive holiday scenes
- create themed sweater patterns
- use connected MCP tools through an AI agent interface

## Project Structure
- `root_agent/` — agent definition and configuration
- `mcp_server.py` — MCP server and tools
- `static/` — generated demo outputs
- `pyproject.toml` — project configuration

## How to Run
```bash
cd 01-starter
uv run adk web --port 8000 --allow_origins "regex:https://.*\.cloudshell\.dev"
```
### Then open the web preview on port 8000.

### Example Prompts
Hi! Who are you?
Create a holiday scene with a snowy village
Create a sweater pattern with pizza slices
