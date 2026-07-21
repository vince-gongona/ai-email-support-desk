# AI Email Support Desk

An AI-powered email support workflow built with n8n that automatically classifies incoming emails, retrieves relevant knowledge from a vector database, generates intelligent responses, routes requests based on priority, and logs every processed ticket.

---

## Workflow Overview

This solution consists of two workflows:

1. **AI Email Support Desk** – Monitors incoming emails, classifies requests, generates AI-powered responses, routes tickets, and logs all actions.
2. **Knowledge Base Ingestion** – Automatically processes uploaded documents, generates embeddings, and stores them in Pinecone to keep the AI knowledge base up to date.

### Features

- Gmail inbox monitoring
- AI email classification
- Retrieval-Augmented Generation (RAG)
- Pinecone knowledge base
- Automatic reply generation
- Human review routing
- Slack notifications
- Google Sheets ticket logging
- Automated email labeling

---

## Workflow

### AI Email Support Desk

1. Monitor Gmail inbox
2. Prepare email content
3. Retrieve relevant knowledge from Pinecone
4. AI classifies the request
5. Generate response
6. Route based on AI decision
7. Send reply or notify support team
8. Label processed email
9. Log support ticket

### Knowledge Base Ingestion

1. Monitor Google Drive
2. Download new knowledge document
3. Split document into chunks
4. Generate embeddings
5. Store vectors in Pinecone

---

## Tech Stack

- n8n
- OpenAI GPT-4.1 Mini
- OpenAI Embeddings
- Pinecone
- Gmail
- Google Drive
- Google Sheets
- Slack

---

## Screenshot

> *(Add workflow screenshots here later.)*

---

## Author

Built by **Vince Gongona**
