# 🦜 LangChain Summarizer: Summarize YouTube & Website Content

![Powered by LangChain](https://img.shields.io/badge/Powered%20By-LangChain-blue?style=for-the-badge)  
![Model: LLaMA 3.3‑70B](https://img.shields.io/badge/Model-LLaMA3.3--70B-yellow?style=for-the-badge)

A lightweight Streamlit app that leverages **LLaMA 3.3‑70B** via the **Groq API** and **LangChain** to generate concise, 300‑word summaries from **YouTube videos** or **webpage URLs**.

---

## 🚀 Features

- 📺 **YouTube Video Summaries**  
  Paste a YouTube link and get a 300‑word summary.

- 🌐 **Webpage Summaries**  
  Works with any public website URL.

- ⚡ **High‑Performance Inference**  
  Runs open‑source LLaMA 3.3‑70B on Groq’s super‑fast accelerators.

- 🧠 **LangChain Prompting & Chains**  
  Custom prompt templates and summarization chain for high‑quality output.

- 🔐 **Secure API Key Input**  
  Enter your Groq API key via the sidebar—no hard‑coding.

---

## 🎯 Tech Stack

- **Streamlit** — Interactive web UI  
- **LangChain** — LLM orchestration & chains  
- **Groq API** — LLaMA 3.3‑70B inference  
- **Pydantic** — Input validation  
- **YoutubeLoader** & **UnstructuredURLLoader** — Content extraction

---

## 📦 Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/your-username/langchain-summarizer.git
   cd langchain-summarizer

# Create virtual environment
python -m venv .venv

# Activate it
source .venv/bin/activate      # macOS/Linux
.venv\Scripts\activate         # Windows

pip install --upgrade pip
pip install streamlit langchain langchain-core langchain-community langchain-groq unstructured[all] validators


streamlit run app.py
