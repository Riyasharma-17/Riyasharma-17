<h1 align="center">Riya Sharma</h1>

<p align="center">
  <b>I build GenAI backends designed for the day an LLM provider fails.</b><br>
  RAG pipelines · LangGraph agents · multi-provider LLM apps<br>
  3rd-year B.Tech CCE @ Amrita Vishwa Vidyapeetham (2028)<br><br>
  <a href="https://linkedin.com/in/riyaasharma17">LinkedIn</a> ·
  <a href="mailto:riyasharmaptn1717@gmail.com">Email</a> ·
  <b>Open to AI/GenAI Engineer internships and collaborations</b>
</p>

---

## The idea behind my work

LLMs are unreliable parts, so I wrap them in structure: Pydantic-validated outputs, Groq → Gemini fallback, deterministic rules where decisions matter, and tests for the failure paths.

## Featured projects

### 🛡️ [AI Governance Interview Agent](https://github.com/Riyasharma-17/gov-interview-agent)
LangGraph agent that interviews teams about new AI systems and fills a Pydantic profile where every field tracks value, source and confidence. It flags conflicts with a policy document for human review instead of guessing.
- Zero-LLM rule engine makes the final Yes/No/Unknown calls
- Review queue backed by an append-only SQLite audit log
- Eval: caught 3/3 planted conflicts, 0 false flags (small hand-written set)

`LangGraph · Pydantic · SQLite · Groq → Gemini fallback · Gradio`

### 🔎 [JD Intelligence Tool](https://github.com/Riyasharma-17/jd-intelligence-tool) · [Live demo](ADD-HF-LINK)
Turns messy job descriptions into structured insight (skills, seniority, culture signals, red flags) and compares roles side by side.
- Pydantic-validated outputs, automatic Groq → Gemini fallback
- 10/10 pytest tests, two-service Docker Compose setup

`FastAPI · LangChain · Pydantic · Gradio · Docker`

### 💬 [Multi-Provider AI Chatbot](https://github.com/Riyasharma-17/CLI-Multi-Provider-AI-Chatbot) · [Live demo](https://multi-provider-ai-chatbot-ui.onrender.com)
Groq, Gemini and OpenRouter behind one adapter interface, so adding a provider needs zero changes to existing logic. Grew over five phases: CLI → FastAPI → LangChain → Gradio → Docker.
- Live on Render with streaming, CI, and pytest coverage

`FastAPI · LangChain (LCEL) · Docker · GitHub Actions`

### 📚 [AI Study Assistant](https://github.com/Riyasharma-17/ai-study-assistant)
RAG pipeline built from scratch with no frameworks (PDF → chunking → keyword retrieval → Gemini), to understand the mechanics before moving to LangChain.

`Python · Gemini API · PyPDF2`

---

## Toolkit

| | |
|---|---|
| **GenAI** | LangGraph, LangChain (LCEL), RAG, prompt engineering, Groq, Gemini, OpenRouter |
| **Backend** | Python, FastAPI, Pydantic, async/await, streaming, SQL/SQLite |
| **Infra** | Docker, Render, GitHub Actions CI, Azure (Functions, Blob Storage) |
| **Testing** | pytest, unittest.mock |
| **Frontend** | Gradio, JavaScript, React (basics) |

## Currently learning
Vector databases (ChromaDB) and multi-agent systems.

## Contact
📧 riyasharmaptn1717@gmail.com · 💼 [LinkedIn](https://linkedin.com/in/riyaasharma17)
