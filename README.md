# AgentSuite - Intelligent Automation Platform

An AI-powered multi-agent digital workforce platform with human-in-the-loop control.

## Tech Stack
- **Frontend**: React 18, TypeScript, Vite, Tailwind CSS, React Flow, TanStack Query
- **Backend**: FastAPI, SQLAlchemy, PostgreSQL, Celery, Redis
- **AI**: Gemini, OpenAI, Anthropic (via config)

## Quick Start

### Backend
```bash
cd backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
cp .env.example .env  # Edit with your credentials
uvicorn app.main:app --reload --port 8000