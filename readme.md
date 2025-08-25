# EmbedCart Backend

A backend service for a Walmart-like shopping assistant, built with FastAPI and OpenAI Agents. 

This project provides an intelligent, natural-language shopping assistant capable of:
- **Product Discovery:** Semantically searching and recommending products using a Retrieval-Augmented Generation (RAG) pipeline connected to a vector database (MongoDB).
- **Cart Management:** Allowing users to add, remove, and view items in their cart entirely through conversational prompts via AI Agent tool-calling capabilities.
- **Workflow Orchestration:** Seamlessly handing off user intents between a generalized shopper agent, specialized cart-manager agent, and the RAG-retriever for highly specific queries.
