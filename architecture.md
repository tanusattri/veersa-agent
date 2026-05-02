# Multi-Agent Research System- Architecture

An AI-powered research automation system that utilizes a sequential pipeline of specialized intelligent agents to transform a research topic into a comprehensive, evaluated report.

## 🏗️ System Overview

The system is built on a modular architecture consisting of a user interface, a pipeline orchestrator, and a suite of specialized agents. Each agent is responsible for a specific stage of the research lifecycle, ensuring high-quality, structured, and actionable outputs.

---

## 🛠️ Tech Stack

- **Core Logic:** Python
- **Framework:** LangChain
- **Web Interface:** Streamlit
- **LLM Provider:** Groq (Llama-3.3-70B)
- **Data Extraction:** BeautifulSoup, Requests
- **Search Engine:** SerpAPI (Google Search)

---

## 🧩 Architectural Components

### 1. User Interface (Streamlit Application)
Provides a web-based portal where users can:
- Enter research topics.
- Configure search and model parameters.
- Monitor real-time progress.
- Download the final research report.
