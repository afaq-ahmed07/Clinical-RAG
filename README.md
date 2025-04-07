# Clinical QA with RAG using Ollama and MIMIC-IV Data

This project demonstrates how to build a Retrieval-Augmented Generation (RAG) pipeline using clinical documents from the MIMIC-IV-Extended dataset. It leverages domain-specific embeddings and the **Ollama** inference server (e.g., Mistral) to answer clinical queries.

---

## 🚀 Features

- Loads and preprocesses clinical notes from the MIMIC-IV-Extended dataset.
- Chunks documents into smaller passages to optimize memory usage and retrieval.
- Builds a vectorstore using domain-specific embeddings.
- Creates a RAG QA chain using a local Ollama model (e.g., Mistral).
- Runs sample clinical queries through the RAG pipeline.
- Optionally evaluates the retrieval and generation quality if ground-truth is available.

---

## 🛠 Requirements

- Python 3.8+
- Ollama (https://ollama.com/)
- Required Python packages (install via pip):

```bash
pip install -r requirements.txt
```
---

## Running the Demo
Make sure you have Ollama running and a model like mistral pulled locally:

```bash
ollama run mistral
```


