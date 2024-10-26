# News Aggregator using Swarm, DuckDuckGo, and Llama Model

This project implements a **news aggregation and summarization workflow** using:
- **Swarm framework** for orchestrating AI agents.
- **DuckDuckGo Search API** for fetching news articles.
- **Ollama's Llama3.2:latest model** for AI-powered content generation and editing.

The workflow involves two agents:
1. **News Agent** – Fetches the latest news articles on a given topic.
2. **Editor Agent** – Summarizes and edits the articles into a publish-ready version.

## Prerequisites

Make sure the following are installed:
- **Python 3.8+**
- **Ollama** (for running the Llama model locally)
- **pip packages**: `pandas`, `python-dotenv`, `duckduckgo-search`, `swarm`
- **Llama3.2 model** via Ollama (already downloaded locally)
