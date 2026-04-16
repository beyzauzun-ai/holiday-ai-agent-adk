# Holiday AI Agent with ADK and MCP

An AI agent built with Google ADK, MCP tools, and Memory for generating holiday scenes and sweater patterns.

## Features
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
