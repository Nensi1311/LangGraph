## LangGraph

Build reliable, stateful agent workflows with LangGraph. This repository provides a clean starting point to design, run and iterate on graph-based LLM applications (tools, agents, routers, evaluators).

### Prerequisites
- Python 3.10 or newer

- An LLM provider key (e.g., `OPENROUTER_API_KEY`, `OPENAI_API_KEY`, `ANTHROPIC_API_KEY`) for the quickstart

### Setup
1) Clone and enter the project
```bash
git clone <your-repo-url> LangGraph
cd LangGraph
```

2) Create and activate a virtual environment
```bash
python -m venv .venv
# Windows PowerShell
.venv\Scripts\Activate.venv
# macOS/Linux
source .venv/bin/activate
```

3) Install dependencies
```bash
pip install -U pip
pip install "langgraph>=0.2" "langchain>=0.3" "pydantic>=2" python-dotenv
```

4) Configure environment
Create a `.env` file in the repository root:
```bash
# .env
OPENROUTER_API_KEY=<YOUR_KEY>
# or
OPENAI_API_KEY=<YOUR_KEY>
# or
ANTHROPIC_API_KEY=<YOUR_KEY>
```