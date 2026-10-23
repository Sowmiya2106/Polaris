# Polaris
POLARIS is an AI-powered Police Proposal Intelligence and Institutional Precedent Retrieval System that combines semantic search, BGE-M3 embeddings, ChromaDB, and Google Gemini to help authorized officers retrieve historical proposals, explore recorded decision reasons, and access relevant information through a secure web dashboard.
# POLARIS 🚔
### Police Proposal & Institutional Retrieval Intelligence System

**Smarter Retrieval. Better Decisions.**

POLARIS is an AI-powered web application developed for the **Intelligent Proposal Management & Precedent Retrieval System** problem statement at Puducherry Police Hackathon 2026.

The system helps authorized police personnel discover relevant historical proposals using semantic search and interact with proposal records through an AI-powered question-answering interface. By combining vector-based retrieval with generative AI, POLARIS aims to make institutional knowledge more accessible and support informed, evidence-based decision-making.

## ✨ Key Features

- **Semantic Search:** Retrieve related historical proposals based on meaning rather than exact keyword matches.
- **AI-Powered Question Answering:** Ask natural-language questions about proposal records using Google Gemini.
- **Historical Precedent Retrieval:** Explore relevant proposals and their recorded decision reasons.
- **Proposal Status Dashboard:** View available proposal records and their approval statuses.
- **Secure Authentication:** Protect application endpoints using JWT-based authentication and password hashing.
- **Multilingual Queries:** Supports testing of Tamil and English queries.
- **Supporting Records:** Review retrieved proposal information to understand the context behind AI-generated answers.

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Frontend | React, Vite |
| Backend | Python, FastAPI |
| Embedding Model | BGE-M3 |
| Vector Database | ChromaDB |
| Generative AI | Google Gemini API |
| Structured Database | SQLite |
| Authentication | JWT, Argon2 |
| Development Tools | VS Code, Python, Node.js |

## ⚙️ How It Works

1. An authorized officer logs in to the application.
2. The officer searches for a historical precedent or enters a question in natural language.
3. BGE-M3 converts the query into an embedding representation.
4. ChromaDB retrieves semantically similar proposal records.
5. For AI-assisted questions, the retrieved records are provided as context to Google Gemini.
6. POLARIS displays the generated answer and available supporting proposal information.

## 🎯 Project Objective

The goal of POLARIS is to reduce the effort involved in manually searching historical proposal records, improve access to recorded decision reasons, and support informed decision-making through AI-assisted information retrieval.

## 🔮 Future Enhancements

- Improve retrieval relevance and ranking.
- Add status-aware proposal filtering.
- Enhance source traceability and audit logging.
- Expand testing with larger, authorized datasets.
- Strengthen multilingual retrieval and answer evaluation.
- Develop more comprehensive proposal management workflows.

## ⚠️ Disclaimer

POLARIS is a prototype developed for demonstration and hackathon purposes. Its current dataset contains fictional proposal records. AI-generated responses should be verified against source records, and final decisions must remain with authorized human personnel.

## 👩‍💻 Project Information

**Project Name:** POLARIS  
**Event:** Puducherry Police Hackathon 2026  
**Problem Statement:** Intelligent Proposal Management & Precedent Retrieval System
