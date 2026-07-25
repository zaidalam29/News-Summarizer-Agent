# News Summarizer Agent

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/Framework-LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/LLM-GPT--4o--mini-412991?style=flat-square&logo=openai&logoColor=white)
![NewsAPI](https://img.shields.io/badge/Data-NewsAPI-FF4B4B?style=flat-square&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

Fetches news articles on any topic and produces a structured briefing with key themes and insights.

**Author:** Zaid Alam — Senior Full Stack Developer & GenAI/ML Engineer

---

## Tech Stack

| Component      | Technology                                    |
|-----------------|-----------------------------------------------|
| Framework       | LangChain                                     |
| LLM             | GPT-4o-mini                                   |
| Data            | NewsAPI (optional — runs with mock data without a key) |

---

## Setup

```bash
pip install -r requirements.txt
cp .env.example .env
```

---

## Usage

```bash
python agent.py --topic "artificial intelligence"
python agent.py --topic "climate change" --count 10
```

> Works without a NewsAPI key using sample data. For real news, get a free key at newsapi.org.

---

## About the Author

**Zaid Alam**  
Senior Full Stack Developer & GenAI/ML Engineer  
Building production-grade agentic AI systems using LangGraph, RAG pipelines, and MCP-based tool orchestration.