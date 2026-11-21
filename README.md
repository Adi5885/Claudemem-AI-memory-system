<img width="1717" height="916" alt="ClaudeMem AI Memory Dashboard" src="https://github.com/user-attachments/assets/0c710a99-8154-44be-ba73-f90d560770c1" />
 ClaudeMem – Persistent AI Memory Management System





ClaudeMem is an AI-powered memory management system designed to store, retrieve, and manage conversational context across multiple interactions.

## Features

- Persistent conversational memory
- Automatic memory extraction
- Semantic search and retrieval
- Embedding generation
- Context-aware AI responses
- Long-term memory storage
- Memory management and retrieval

## Architecture

1. User interacts with the AI assistant.
2. The system extracts relevant information from conversations.
3. Extracted memories are converted into vector embeddings.
4. Memories are stored in a vector database.
5. Relevant memories are retrieved during future conversations.
6. Retrieved context is supplied to the LLM to generate personalized responses.

## Tech Stack

- Python
- FastAPI
- LLM APIs
- Vector Database
- Embeddings
- REST APIs

## Project Structure

```text
claudemem-ai-memory-system/
├── backend/
│   ├── main.py
│   ├── memory/
│   ├── services/
│   └── database/
├── frontend/
├── tests/
├── requirements.txt
├── .env.example
└── README.md
```

## Getting Started

Clone the repository:

```bash
git clone https://github.com/Adi5885/claudemem-ai-memory-system.git
cd claudemem-ai-memory-system
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Configure your environment variables in `.env`.

Run the backend:

```bash
uvicorn backend.main:app --reload
```

## Project Status

In Development.

## Author

Aditya Danve
