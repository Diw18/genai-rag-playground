# GenAI RAG Playground
Minimal experiments with Retrieval-Augmented Generation (RAG): indexing, retrieval quality, and prompt strategies.

## Quickstart
```bash
python -m venv .venv && source .venv/bin/activate  # on Windows: .venv\Scripts\activate
pip install -r requirements.txt
python app.py

Plan/Roadmap
 Add a tiny dataset + embeddings
 Compare retrieval (BM25 vs dense)
 Prompt templates + evaluation
 Wrap in FastAPI + simple UI
