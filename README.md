# 🧠 AI Code Explainer – Jupyter + Gradio + OpenAI

Welcome to my personal project exploring how to build AI-powered tools using:
- 🔍 OpenAI (GPT)
- 💬 Gradio (UI)
- 📒 Jupyter (experiments + demos)
- 🧪 Python (`openai`, `gradio`, `dotenv`, etc.)

---

## 📁 Project Structure

```
.
├── app.ipynb                # Main Jupyter notebook
├── explain_code_open_ai.py # Python function that sends code to OpenAI
├── .env                     # Contains OpenAI API key
├── requirements.txt         # All required packages
└── README.md                # You're here!
```

---

## 🚀 Features

- Input code (Python or other)
- Send to OpenAI using `chat.completions`
- Display Markdown-formatted explanation using Gradio
- Support for future improvements: streaming, syntax highlighting, RAG

---

## 🔧 Setup

1. **Clone repo / open project folder**
2. Create a virtual environment (optional but recommended)
3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Add your `.env` file:

```
OPENAI_API_KEY=sk-...
```

5. Run the app:

```bash
jupyter lab
```

Then run the cell:

```python
view.launch(share=True)
```

---

## ✅ Dependencies

- `gradio`
- `openai`
- `python-dotenv`
- `IPython` (for local Markdown display, optional)
- `jupyterlab` (if using notebook)

---

## 📌 Notes

- This is part of a learning journey to build AI agents.
- The notebook grows over time as features are added.
- Markdown-based explanations are preferred over plain text for clarity.
- If you're using `gr.Markdown` – remember: it doesn’t support `label`.

---

## ✍️ Author

Eyal Ankri  
Working with C#, .NET Core, NHibernate – now learning AI with Python  
Israel, 2025  
