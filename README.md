# 🤖 Effective AI Agent Design Patterns with LangGraph & CrewAI

This repository presents a structured implementation of **AI agent design patterns** using two powerful frameworks: **LangGraph** and **CrewAI**. Inspired by the *"Building Effective Agents"* methodology, the notebooks demonstrate modular, reusable patterns like prompt chaining, parallel workflows, evaluator-optimizer loops, and routing agents.

---

## 📌 Objective

- Implement and compare **agent design patterns** using LangGraph and CrewAI  
- Demonstrate workflows involving **tool use**, **reasoning loops**, and **autonomous task planning**  
- Use **LangSmith traces** for LangGraph and **Groq-compatible CrewAI flows** for performance  
- Provide side-by-side implementations for learning and benchmarking  

---

## 🎥 Video Walkthroughs

| Topic                | Link     |
|----------------------|----------|
| LangGraph Agent Demo | [Watch here](#) |
| CrewAI Agent Demo    | [Watch here](#) |

*Replace `#` with the actual YouTube or Drive video links.*

---

## 📘 LangGraph-Based Notebooks

| Notebook                              | Description |
|----------------------------------------|-------------|
| `LangGraph_Agent_Design_Patterns.ipynb` | Complete set of agent design patterns:  
- ✅ Prompt Chaining  
- ⚡ Parallelization  
- 🔁 Orchestrator–Worker  
- 🧪 Evaluator–Optimizer  
- 🧭 Router Pattern  
- 🔄 Autonomous Looping Agent  

🛠️ Includes LangSmith trace support for each pattern.

---

## 🧠 CrewAI-Based Notebooks

| Notebook           | Description |
|--------------------|-------------|
| `CrewAI_Groq.ipynb` | Implements equivalent patterns using CrewAI with Groq LLaMA3:  
- ✅ Prompt Chaining  
- 🔁 Orchestrator–Worker  
- 🤖 Autonomous Agent with Internal Reasoning  

Uses Groq-hosted LLaMA 3 models for blazing fast inference. Ideal for students with no OpenAI key.

---

## 🔁 Design Patterns Covered

| Pattern                 | Description |
|-------------------------|-------------|
| **Prompt Chaining**     | Pass output of one agent/task to the next  
| **Parallel Execution**  | Multiple agents work simultaneously  
| **Orchestrator–Worker** | One manager delegates and combines outputs  
| **Evaluator–Optimizer** | Generator followed by a feedback critic  
| **Routing Agent**       | Route input to the correct sub-agent  
| **Autonomous Agent Loop** | Retry/reflective logic until goal is met  

---

## 🧪 Requirements

- Python 3.10+  
- `crewai`, `litellm`, `langgraph`, `duckduckgo-search`, `langchain-community`  
- Free-tier accounts on [Groq Cloud](https://console.groq.com) and [LangSmith](https://smith.langchain.com) (optional)  

---

## 📂 Folder Structure

```bash
.
├── LangGraph_Agent_Design_Patterns.ipynb   # All LangGraph patterns in one
├── CrewAI_Groq.ipynb                       # All CrewAI + Groq agent workflows
├── README.md                               # You're here
