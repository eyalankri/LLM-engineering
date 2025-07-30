# 🧠 AI Projects Collection

This repository contains multiple AI projects exploring Large Language Models (LLMs), UI interfaces, and integrations with modern tools like OpenAI, Gradio, and Jupyter.

---

## 📁 Projects

### 1. `code-explainer`

A Jupyter-based tool for explaining code snippets using OpenAI GPT models with a simple Gradio UI.

**Stack:**

- Python
- Ollama (for running local LLMs)
- OpenAI (GPT-4o-mini)
- Gradio
- Jupyter Lab
- dotenv

### 2. `store-chatbot`

Simulates a clothing store assistant using GPT, with streaming responses and behavior logic to promote specific items (like hats).

**Stack:**

- Python
- OpenAI
- Gradio
- dotenv

### 3. `generate-brochure`

AI-powered brochure generator that intelligently scrapes and summarizes content from company websites. Built as a notebook-driven prototype.

**Stack:**

- Python
- OpenAI
- Jupyter Notebook
- BeautifulSoup (web scraping)
- Requests
- dotenv

---



## 📦 Requirements

Each project includes its own `environment.yml` or `requirements.txt`.

---

## 🔐 .env File

Each project uses a `.env` file to store sensitive information like API keys. This keeps secrets out of your codebase and lets you load them securely using the `dotenv` package.

Example `.env` file:

```
OPENAI_API_KEY=your-openai-key
ANTHROPIC_API_KEY=your-anthropic-key
GOOGLE_API_KEY=your-google-key
```

## 🚀 Getting Started

```bash
cd project-name
conda activate llms
jupyter lab
```

Make sure you add a `.env` file in each project with your API keys.

---

## ✍️ Author

Eyal Ankri – AI & LLMs

