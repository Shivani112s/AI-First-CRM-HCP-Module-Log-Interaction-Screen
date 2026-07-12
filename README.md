# AI-First CRM HCP Module

## Overview

An AI-powered CRM system for Healthcare Professional (HCP) interaction management.

The application allows sales representatives to log interactions through:

- Structured Forms
- Conversational Chat Interface

The system uses LangGraph and Groq LLM to automatically generate summaries, extract entities, and provide follow-up recommendations.

---

## Tech Stack

### Frontend
- React
- Redux
- Google Inter Font

### Backend
- FastAPI
- Python

### AI Framework
- LangGraph

### LLM
- Groq Gemma2-9B-IT

### Database
- PostgreSQL

---

## LangGraph Tools

1. Log Interaction
2. Edit Interaction
3. HCP Profile Retrieval
4. Follow-up Recommendation
5. Meeting Summary & Insights

---

## Run Backend

cd backend

pip install -r requirements.txt

python -m app.seed

uvicorn app.main:app --reload --port 8000

---

## Run Frontend

cd frontend

npm install

npm run dev

---

## Features

- HCP Interaction Logging
- AI Generated Summaries
- Topic Extraction
- Attendee Extraction
- Follow-up Recommendations
- Editable Interactions
- PostgreSQL Storage
