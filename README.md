# News-AI-Agent-using-CrewAI-with-Llama-Groq-LLM-Models

This project demonstrates a fully functional AI Agent System built using CrewAI, powered by Groq's blazing-fast LLaMA 3.1-70B model via langchain_groq, and integrated with real-time search tools (Serper API) for live intelligence gathering.

This multi-agent system autonomously:

- Researches the latest developments in a chosen tech topic
- Writes a compelling article based on the findings
- Proofreads & finalizes the content for publication with proper structure, grammar, and citations

All agents collaborate in a sequential workflow, simulating a real-world editorial pipeline for technology journalism.

**Tech Stack:**
LLM: groq/llama-3.1-70b-versatile via Groq API

Agents & Workflow: CrewAI

Tooling: SerperDevTool for real-time Google search

LangChain Groq integration for lightning-fast inference

**Installations:**
pipenv install crewai
pipenv install langchain_groq
pipenv install crewai_tools

**Execution:**
pipenv run python crew.py
