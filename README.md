# 🧠 LangChain Medical Info Assistant

A LangChain-based medical information assistant powered by **Groq LLaMA 3.3** and **SerpAPI**.  
It searches trusted healthcare sources and explains medicines with structured sections:  
**uses, benefits, risks, and citations**. Includes error handling and fallback for reliable results.

---

## 🚀 Features
- Uses **LangChain ReAct agent** for tool-driven reasoning.
- Integrates **Groq LLaMA 3.3-70B** for consistent outputs.
- Fetches authoritative data via **SerpAPI** (Google Search).
- Returns clean JSON results with titles, links, and snippets.
- Outputs structured answers with inline citations.
- Fallback mechanism for parsing errors.

---

## 📦 Installation
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
