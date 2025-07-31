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

### 4. `airline-assistant`

An interactive AI customer support chatbot for an airline company ("FlightAI"). It uses GPT-4o-mini with function calling to fetch ticket prices and store reservations, generate personalized DALL·E tickets, translate responses into Hebrew, and speak responses using text-to-speech.

**Features:**

- Function calling for ticket pricing and reservation handling
- Tool-use logic to interact with external actions (like writing to file)
- DALL·E integration to generate image-based boarding passes
- Voice output using OpenAI `tts-1`
- Real-time English–Hebrew translation
- Gradio interface for chat + translation window

**Stack:**

- Python
- OpenAI (GPT-4o-mini, DALL·E, TTS)
- Gradio
- dotenv
- PIL (image handling)
- `simpleaudio` + `IPython.display` (for voice playback)

---

## 🛆 Requirements

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

## ✨ Getting Started

```bash
cd project-name
conda activate llms
jupyter lab
```

Make sure you add a `.env` file in each project with your API keys.

---

## ✍️ Author

Eyal Ankri – AI & LLMs

